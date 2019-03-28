# Java 命名规范

## 基本原则
1、在无歧义的前提下，命名力求简洁
2、在语义明了的前提下，命名力求省力，如果可以同时不按shift，则不按
3、一个标识符最好一个单词，尽量不要超过3个单词，每个单词尽量不要超过10个字符
4、单词应当拼写正确完整

#### 驼峰命名法
大驼峰 -> UpperCamelCase, Camel
小驼峰 -> lowerCamelCase, camel

#### 缩写
缩写可单独使用，可用作前缀，例如:
```
// 正确
btn, txt, btnSubmit, txtName 
// 错误
submitBtn, isTxtName
```

#### 拼音
拼音与英文单词不能混用
拼音单词(概念)组合使用时只有第一个字母大写
拼音缩写可单独作为单词使用，尽量不要与英文混用
例：
```
// 正确
pinyin, mingzi 
btnDing, btnDuobao
yyb(应用宝), rmb(人民币)
// 错误
pinYin, pinyinField
```

#### 包名(package)
全小写，最好一个单词
例：
```
package, examplepackage, multiwordpackage
```

#### 类名(class)
采用大驼峰
例：
```
MyClass, YourClass
```

#### 常量名(const)
常量全大写，单词间用下划线(_)分隔
例：
```
EVENT_CLICK, HUMAN_STATUS_OK
```

#### 参数(parameter) 变量(variable) 方法(method)

采用小驼峰，最好一个单词
方法通常以动词开头
例：
```
isOk, data, beginTime  
checkName, validatePhone
```

#### 表判断(Boolean)
可用于[var,field,property,method]
情态动词(can/should/need/will)+动词
系词(is)+名词
系词(is)+形容词
例：
```
canDelete, canEnter, shouldDie, needDecode, willRain
isCard, isVip, isBoss, isMonster
isBeautiful, isVestmented, isRunning
```

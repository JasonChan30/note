# Gradle

![image](https://github.com/user-attachments/assets/f03a332c-53b5-4899-877a-d3442608ea83)

## Concepts
https://docs.gradle.org/current/userguide/gradle_basics.html#gradle_core_concepts

### Language  
[Groovy](https://docs.gradle.org/current/dsl/index.html)  
[Kotlin](https://docs.gradle.org/current/kotlin-dsl/index.html)  
Settings 跟 build file 里面使用的语言


### Settings file
主要是为了声明该项目包含几个**子项目**
项目init阶段会寻找对应的settings，创建project实例

#### Content
主要内容有定义plugins，root project信息，包含哪几个sub project  
详见：https://docs.gradle.org/current/userguide/writing_settings_files.html#writing_settings_files  

### Build File
主要是声明**Project**里面的配置  
Gradle会在configuration阶段找到对应的.gradle file，进行配置  

#### Content
在build file可以定义plugins，定义依赖，定义依赖来源，还有一些属性（项目属性，插件用到的属性等），还可以引用一些task，还可以写一些script（属性赋值，call方法，定义一些变量）  
{} block是一种方法调用，接受一些闭包啥的

### Life Cycle
![image](https://github.com/user-attachments/assets/d06045d3-e5b7-4517-b36a-d81d7c5e3c90)

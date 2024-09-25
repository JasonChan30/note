# Gradle

![image](https://github.com/user-attachments/assets/f03a332c-53b5-4899-877a-d3442608ea83)

## Concepts
https://docs.gradle.org/current/userguide/gradle_basics.html#gradle_core_concepts

### Settings file
The primary purpose of the settings file is to **add subprojects to your build**.
Gradle supports single and multi-project builds.
1. For single-project builds, the settings file is optional.
2. For multi-project builds, the settings file is mandatory and declares all subprojects.



### Build File
Every Gradle build comprises at least one build script.
In the build file, two types of dependencies can be added:
1. The **libraries and/or plugins** on which Gradle and the **build script depend**.
2. The libraries on which the **project sources (i.e., source code) depend**.

***Build scripts configure Project objects and their children.***

### Life Cycle
![image](https://github.com/user-attachments/assets/d06045d3-e5b7-4517-b36a-d81d7c5e3c90)

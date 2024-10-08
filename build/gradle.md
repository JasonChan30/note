# Gradle

![image](https://github.com/user-attachments/assets/f03a332c-53b5-4899-877a-d3442608ea83)

## Concepts
https://docs.gradle.org/current/userguide/gradle_basics.html#gradle_core_concepts

### Settings file
The primary purpose of the settings file is to **add subprojects to your build**.

#### Standard Settings properties
1. buildCache
2. plugins
3. rootDir
4. rootProject
5. settings

#### Standard Settings method
1. include()
2. includeBuild()

### Build File
Every Gradle build comprises at least one build script.
A build script configures a project and is associated with an object of type **Project**.

#### Standard project properties
1. name
2. path
3. description
4. dependencies
5. repositories
6. layout - Provides access to several important locations for a project.
7. group - The group of this project.
8. version

#### Standard Settings method
1. uri() - Resolves a file path to a URI, relative to the project directory of this project.
2. task()

### Life Cycle
![image](https://github.com/user-attachments/assets/d06045d3-e5b7-4517-b36a-d81d7c5e3c90)

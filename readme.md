# What is this project?
This project packages [firmata4j](https://github.com/kurbatov/firmata4j) 
into a jar file with all it's dependencies.
It uses the latest commit on the master branch when compiling firmata4j.

# How to download the jar with all the dependencies
1. Go to the [/release](/releases) folder
2. Go to the most recent folder date (latest release)
3. Download the `firmata4j-autopack-****.**.**-SNAPSHOT-jar-with-dependencies.jar`

**Note1:** In the `/separated` folder are the dependencies that were packaged inside the 
`firmata4j-autopack-**-SNAPSHOT-jar-with-dependencies.jar`.

**Note 2:** In the `/separated` folder you can see what commit of [firmata4j](https://github.com/kurbatov/firmata4j)
was used in the jar file by looking at the name:

For example if you have: firmata4j-master-firmata4j-2.3.8-g**9de0fd9**-12.jar

The commit hash would be: **9de0fd9**

You can see all firmata4j's commits here: https://github.com/kurbatov/firmata4j/commits
![image](https://user-images.githubusercontent.com/8143308/116429782-34962700-a814-11eb-8f74-3ff6fb1f1eb5.png)

# How to add the .jar to your java project
1. Copy the .jar to a /lib folder

![image](https://user-images.githubusercontent.com/8143308/116433922-f438a800-a817-11eb-96fc-1339eae0c394.png)

2. Add the jar to the build path

![image](https://user-images.githubusercontent.com/8143308/116434109-1d593880-a818-11eb-89ac-918c3a25e439.png)

3. enjoy!

![image](https://user-images.githubusercontent.com/8143308/116434384-5ee9e380-a818-11eb-808c-41d9584331c9.png)




# Why this repository?
See [docs/why.md](/docs/why.md)

# Need a new release?
Open an issue, this will trigger a github action that will package the .jar with all the dependencies from latest commit in the date of today. 

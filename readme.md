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
# Why this repository?
See [docs/why.md](/docs/why.md)

# Need a new release?
Open an issue, this will trigger a github action that will package the .jar with all the dependencies from latest commit in the date of today. The Github release tab will be updated with the new .jar.

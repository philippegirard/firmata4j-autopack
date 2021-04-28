# What is this project?
This project package [firmata4j](https://github.com/kurbatov/firmata4j) 
into a jar file with all it's dependencies.
It uses the latest commit on the master branch when compiling firmata4j.

# How to download the jar with all the dependencies
1. Go to the [/release](/releases) folder
2. Go to the most recent folder date (latest release)
3. Download the firmata4j-autopack-**-SNAPSHOT-jar-with-dependencies.jar

note: In the `/separated` folder are the dependencies that were packaged inside the firmata4j-autopack-**-SNAPSHOT-jar-with-dependencies.jar.

# Why this repository?
See [docs/why.md](/docs/why.md)

# Need a new release?
Open an issue, this will trigger a github action that will package the .jar with all the dependencies from latest commit. The Github release tab will be updated with the new .jar.

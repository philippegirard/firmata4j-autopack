# Why this repository?
https://github.com/kurbatov/firmata4j is an awesome. However, there was two shortcoming when I tried to use it on Windows:
1. Cannot download a .jar with all the dependencies packaged in it. This is useful when you don't use maven for your java project and just want to import a .jar lib into your project. 
2. I needed a more recent release than what was published on the Maven central repository. (https://github.com/kurbatov/firmata4j/issues/48)

# What is this repository
This repository takes the latest code from the master branch of https://github.com/kurbatov/firmata4j and package it into a .jar with all its dependencies.

# How to use this repository
1. Check the Github release tab of this repository. 
2. Download the .jar

# Need a new release? 
Open an issue, this will trigger a github action that will package the .jar with all the dependencies from latest commit. The Github release tab will be updated with the new .jar.

# What else I can do with this repository?
Check the /docs folder. I have put some personal hack in. For example, I show how to download all the dependencies in separate .jar files instead of being packaged into one.
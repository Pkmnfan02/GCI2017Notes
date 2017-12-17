# GCI2017Notes
Notes for helping to complete tasks on GCI.

# Task: Develop a simple interface screen
I'm going to be creating a new interface screen on the game Terasology.

Notes: I created a new Terasology Repo, and now I'm going to read this just to help get me started https://github.com/Terasology/TutorialNui/wiki/Quick-Start

Instead of making a new module for this task, I think they want me to use an exsiting module:https://github.com/Terasology/Sample

I noticed that when I went to fetch that module it didn't work:

```
jrr:~/wsrc/Terasology$ ./groovyw module get Sample
Caught: java.io.FileNotFoundException: gradle.properties (No such file or directory)
java.io.FileNotFoundException: gradle.properties (No such file or directory)
	at module.run(module.groovy:12)
	at org.gradle.wrapper.GroovyBootstrapMainStarter.start(GroovyBootstrapMainStarter.java:33)
	at org.gradle.wrapper.WrapperExecutor.execute(WrapperExecutor.java:108)
	at org.gradle.wrapper.GroovyWrapperMain.main(GroovyWrapperMain.java:61)
```
To find that, I ran ./gradlew idea again. It looks like I didn't have everything so it downloaded some things and the fetching of the module is working.

To get to the module and to nagivate to the folder, I used IntelliJ because in my opinion its easier than using the terimal.
Then I made the java class.

Im now on the end/testing part of step 3, I got this error message:
```
Caused by: com.google.gson.stream.MalformedJsonException: Unterminated object at line 6 column 4 path $.contents.text
```
so I am going back a step and just redoing everything.

# References
* https://guides.github.com/features/mastering-markdown/

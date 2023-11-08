# Gradle Scala Paper Template
This is a template for creating a Paper plugin in Scala.

## How to use
Firstly, clone this repository via `git clone https://github.com/Bluheir/scala-plugin-template`. You will then need to change a few things.

1) Rename the project in `plugin.yml` and `build.gradle` to the name you would like for your plugin.
2) Rename the group in `build.gradle` to your group.
3) Move `Plugin.scala` to the appropriate directory for your group.
4) Rename the package in `Plugin.scala`.
5) In `plugin.yml`, change the value for `main` to the canonical class name for your plugin.


## Build
```sh
gradle build
```
The jar file plugin will be located in `./build/libs`
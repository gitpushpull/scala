# Introduction

Learning [Scala](https://www.scala-lang.org/download/).

# Compiling

To compile a file, use  the following command

>`scalac hello.scala`

# Execution

To execute the generate scala bytecode use

>`scala HelloWorld`

where `HelloWorld` is the name of generate class.

# Specifying output directory

By default, `scalac` will generate class files in the current working directory, to specify a different output directory, when compiling, use

> `scalac -d classes hello.scala`

To execute use

> `scala -cp classes HelloWorld`

# SBT (Simple Build Tool)

[SBT](https://www.scala-sbt.org/) will be used to automate builds.

Download the `tgz` package from SBT website and extract at a convinient location.
Add `sbt/path` to system `PATH`. On Linux:

`PATH=$PATH:/path/to/sbt/bin/`





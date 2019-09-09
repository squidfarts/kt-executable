# ***Kotlin executable template.***
----------------------------------------

Code version Orio cookie.  A project template for a new Kotlin based exe 
using Gradle build.

### Projects current status
--------
[![GitHub](https://img.shields.io/github/license/squidfarts/kt-executable.svg?color=blue)](https://github.com/squidfarts/kt-executable)
[![Travis](https://travis-ci.com/squidfarts/kt-executable.svg?branch=master)](https://travis-ci.org/squidfarts/kt-executable)

### Table of contents
--------
> * [Project Name](#project-name)
>   * [Current status bar](#current-status-bar)
>   * [Table of contents](#table-of-contents)
>   * [About this project](#about-this-project)
>   * [Features found](#features-found)
>   * [Downloading required things](#downloading-required-things)
>   * [Downloading this project](#downloading-this-project)
>   * [Building this executable](#building-this-executable)
>     * [Build and run](#build-and-run)
>     * [Checking dependencies](#checking-dependencies)
>   * [Contact the developer](#contact-the-developer)


### About this project
--------

***Kotlin executable*** is a project that was designed to work out 
of the box using Gradle build system from day one.  The creation of
this started at a large codebase where the following languages are 
used to build programs C, C++, Dlang, Kotlin and Python.

The design of the project was meant for demonstrating a project
using the GitHub workflow super charged with continues integration.

However to make something that can defend agains hackers planting 
malicious software attacks or feed of data stored in your database
is mostly imposable and all that can be done is to mitigate the 
possibility of as many software attacks as posable.


### Features found
--------

- Gradle as the main tool for building your exe.
- Gradle as the tool for managing and packaging.
- Setup with Travis-ci.
- Simple project structure just for you. 
- Distributed under the Apache 2.0 license.
- Works 99.95% out of the box.

### Downloading required things

This project requires the following tools:

-----------------------------------------------------------------------------
| Tool being used.                               |  Version needed          |
|------------------------------------------------|--------------------------|
| [Gradle build system ](https://gradle.org)     | version 5.6.x or newer.  |
| [Java](https://www.oracle.com/index.html)      | version 12.0.x or newer. |
| [Kotlin language](https://kotlinlang.org/)     | version 1.3.x or newer.  |


### Downloading this project.
--------

* To install this project the simplest way is to grab it off github with
this command the Github command looks something like this:

```console
git clone https://github.com/squidfarts/kt-executable.git
```
* You can also download it as a zip if you prefer.


### Building this executable.
--------

#### Build and run

To run the the project just run this Gradle command:

```console
./gradlew run
```

#### Checking dependencies

And check compilation dependencies with:

```console
./gradlew dependencies
```

### Contact the developer
==========================

#### Developer and maintainer

- gmail : [squidfarts gmail](mailto:michaelbrockus@gmail.com)
- email : [squidfarts email](mailto:michaelbrockus@icloud.com)
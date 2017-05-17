# hello.world
### Say "Hello, World" in every language!
An open source, crowd assisted website to document every version of the `Hello, World` program.

## Contribution Guide
If you wish to contribute, simply add a `.md` file to the \_programs directory according to the template

You can also add your name and the language you wrote to the CONTRIBUTION.md file, which will be displayed in the Contributions page of the website, along with this Guide

**Please note that only one language per user will be accepted, to help get as many people involved as possible**

_If you want to help out more after submitting your language; tell a friend who can also submit one and tell their friends, and so on_

## Template file
When adding a language, please use the following template, replacing the variables in capitals with text relating to your submission

~~~md
---
author: NAME
lang: LANGUAGE_NAME
---

```LANGUAGE_CODE
PROGRAM
```
~~~

The difference between language name and language code can be seen in this example:

| Name |  Code  |
|:----:|:------:|
|  C#  | csharp |

For an example of what languages are supported, take a look at GitHub's [list of languages](https://github.com/github/linguist/blob/master/lib/linguist/languages.yml)

Here is a working example. The following is used to produce my Java snippet on the website:
~~~md
---
author: crnbrdrck
lang: java
---

```java
public class Hello{
    public static void main(String[] args){
        System.out.println("Hello, World");
    }
}
```
~~~

## License
Licensed under the MIT License

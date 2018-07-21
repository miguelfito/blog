---
layout: post
title:  "Mediator Features"
date:   2014-11-30 14:34:25
categories: mediator feature
tags: mediator
image: /assets/article_images/2014-11-30-mediator_features/night-track.JPG
image2: /assets/article_images/2014-11-30-mediator_features/night-track-mobile.JPG
---

# Mediator Formats and CSS features

Examples for different formats and css features

# Header Formats

# Header1
## Header2
### Header3
#### Header4
##### Header5
###### Header6

# Blockquotes
>Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus

# Lists
## Orderd lists
1. One
2. Two
3. Three

## Unorderd lists
- Apple
- Banana
- Plum


# Links
This is an [example link](http://example.com/ "With a Title").

# Code

```bash
# Shell Script
#!/usr/bin/env bash

MESSAGE="Hello World!"

echo -n $MESSAGE
```
---
```java
// Java program
/***************************************************************************
 *  Compilation:  javac HelloWorld.java
 *  Execution:    java HelloWorld
 *
 *  Prints "Hello, World". By tradition, this is everyone's first program.
 *
 *  % java HelloWorld
 *  Hello, World
 *
 *  These 17 lines of text are comments. They are not part of the program;
 *  they serve to remind us about its properties. The first two lines tell
 *  us what to type to compile and test the program. The next line describes
 *  the purpose of the program. The next few lines give a sample execution
 *  of the program and the resulting output. We will always include such
 *  lines in our programs and encourage you to do the same.
 *
 ***************************************************************************/

public class HelloWorld {

    public static void main(String[] args) {
        // Prints "Hello, World" to the terminal window.
        System.out.println("Hello, World");
    }

}
```
---
```Go
// Go program
package main
import "fmt"
func main() {
    fmt.Println("hello world")
}
```
---
```Python
# Python program
#!/usr/bin/env python
import os, requests, sys, json

username=sys.argv[2]
password=sys.argv[3]
filename = os.path.basename(sys.argv[1])

content=open(filename, 'r').read()

r = requests.post('https://api.github.com/gists',
                  json.dumps({'files':{filename:{"content":content}}}),
                  auth=requests.auth.HTTPBasicAuth(username, password))

print(r.json()['html_url'])
```

And now, without defining `language`:

```
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus
```

# Combinations
>Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus
>
> - Apple
> - Banana
> - Plum

---
sidebar:
  nav: "docs"

toc: true
toc_label: "Table of Contents"
toc_icon: "cog"



title: "Post: Web Exploitation - Cookies"
categories:
  - CTF
  - THM
tags:
  - CFT
  - THM
  - Web Exploitation
  - Cookies
---

# A Christmas Crisis

## Video

{% include video id="BJF84oWHmok" provider="youtube" %}


## Rooms

[Web Fundamentals](https://tryhackme.com/room/webfundamentals)

## Challenge

### Deploy your AttackBox


No answer needed


Enter the site and register a new user.

![](../.gitbook/assets/image%20%2821%29.png)

Login with the previous registered user.

![](../.gitbook/assets/image%20%2873%29.png)

### What is the name of the cookie used for authentication?


auth


### In what format is the value of this cookie encoded?

![](../.gitbook/assets/image%20%2876%29.png)


Hexadecimal


### Having decoded the cookie, what format is the data stored in?


JSON


Figure out how to bypass the authentication.

### What is the value of Santa's cookie?

![](../.gitbook/assets/image%20%2823%29.png)


7b22636f6d70616e79223a22546865204265737420466573746976616c20436f6d70616e79222c2022757365726e616d65223a2273616e7461227d


Now that you are the santa user, you can re-activate the assembly line!

![](../.gitbook/assets/image%20%2839%29.png)

### What is the flag you're given when the line is fully active?


THM{MjY0Yzg5NTJmY2Q1NzM1NjBmZWFhYmQy}



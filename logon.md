# logon

## Category
Web Exploitation

## Points
100

## Problem Description
The factory is hiding things from all of its users. Can you login as Joe and find what they've been looking at? 
https://jupiter.challenges.picoctf.org/problem/15796/ ([link](https://jupiter.challenges.picoctf.org/problem/15796/)) or http://jupiter.challenges.picoctf.org:15796


## Approach
On opening the link and entering the username and password as admin, no flag was obtained. However, when inspecting the the source code it was found that admin value was false thus, the value was changed to true as shown below.

![Alt text](/logon1.png)

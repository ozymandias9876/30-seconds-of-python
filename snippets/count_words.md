---
title: Count Words
tags: string
expertise: intermediate
firstSeen: 2022-11-20T05:00:00-04:00
---



- Take a input string.
- split the string when a ' ' is present.
- splitting of string will result in a list.
- return the length of the list to find the number of words.

```py
def countwords(s):
  # code
  word=s.split(' ')
  return len(words)
```

```py
countwords('Hi, my name is') # 4
countwords('Good morning, Everyone')#3
```

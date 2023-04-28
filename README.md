# MoJingScript README

The extension is a lint for script of Project Mojing.

## Known issues

We don't have language server now.


## Release Notes


### 0.1.0

First commit for MoJing basic script.

## The EBNF Syntax of MoJingScript

Here we list the simplified EBNF Syntax.

```
ScriptList := ScriptItem ScriptList
ScriptItem := ScriptTitle ScriptContent
ScriptTitle := '{' CharSequence '-' CharSequence '}'
ScriptContent := ScriptLine ScriptContent
ScriptLine := ScriptAttribute | ScriptSentense
ScriptAttribute := '[' CharSequence '=' CharSequence ']'
ScriptSentense := '(' CharSequence ')' CharSequence
CharSequence := Char CharSequence
Char := 'a' | 'b' | ... | 'z' | '0' | '1' | .. | '9' | '-'
```


**Enjoy!**

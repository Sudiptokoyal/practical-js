---
sidebar_position: 1
---

# Three Man Blocks

There are three coneptual main block in Javascript that you need to undestand first. And these are-

-   Syntax Parser
-   Lexical Enviroment
-   Execution Context

## Syntax Parser

A program that read your code and check the syntax of your code
Typically, it scan your code line by line and word by word. It can be a compiler or interpreter.

` Your code` - `Machine Code`

## Lexical Enviroment

It tells where you put your code or where you write is something important.

```js
function greet(givenName) {
	var name = givenName ? givenName : "Anonymus";
	console.log(`Hi ${name}!!`);
}
```

Like from above example, how name variable sits under _greet()_ function.

## Execution Context

A wrapper that manage code that is running.
There are lots of lexical enviroment. But which one is currently running is managed by execution context. It can contain things what is beyond that you have written in your code.

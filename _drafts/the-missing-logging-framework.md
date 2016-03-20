---
layout: post
title: The missing logging framework
description: "Log your application using code levels, not log levels."
date: 2013-05-31
category: articles
tags: [Logging]
comments: true
share: true
featured: true
---

Log your application using code levels, not log levels.

Let’s think back to the very first code we wrote in Javascript (or any other language for that matter). Big chances are 
that its main feature was `console.log(‘hello world’)`. Yep, back then logging was simple. And from that moment on we 
kept `console.log` close to out hearts when it comes to logging or even debugging. And we have even grown to writing 
bigger applications, and we have incorporated logging frameworks. But for me at least, something is still amiss.

### Logging is an aspect

When we write code, and want to have traceability (whether in development or production) we log our code. We start to
sprinkle logs all over our code. We write logs as we write the code itself. And as we write our logic for the code we 
have to think about logging as well. But logging is not a part of our logic. We are not writing a logging application.
And that makes logging an aspect of our program and we need to treat it that way. In Aspect Oriented Programming we 
take those aspects and we move them outside of the logic of our application, so we can have a clear separation of 
concerns, and we can clear our minds about an aspect as we code.

### Using decorators for aspects

Explain how I currently implement aspects with es7 decorators.

### Logging with execution depth level

Explain why writing log level for logs is problematic and logging using execution depth level can be better.

### Adding it all up

Show the usage of the logger

### Conclusion

Sum it up


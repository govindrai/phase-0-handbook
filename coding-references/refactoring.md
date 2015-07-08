# How to Refactor

Refactoring is an important step to becoming a world-class beginner, and it's important to look at your code fresh before refactoring. 

## Introduction

See this [Refactoring Intro](https://talks.devbootcamp.com/refactoring-intro) for a short tutorial that introduces refactoring. 

## Summary
Refactoring is not about solving the problem differently, it's about solving the problem well. 

Now is the time to go through the docs to find a method that does what you did from scratch. Because you have already solved the problem once, you'll have a better idea of what method you need to replace some code. 

For example, if you iterated through an array and needed to create a new array that had the same thing done to each element, you may look at the docs and see `#map` or `#collect` that would do what you did. It's important to get familiar with many different methods, so take your refactoring time seriously and do some research to find methods here. 

Also consider the following when you're refactoring:

Good solutions don't just work, they make it clear what they are doing by having:

- Clear names for variables and methods (see [Tips for Naming Variables](https://web.archive.org/web/20131212155508/http://www.makinggoodsoftware.com/2009/05/04/71-tips-for-naming-variables/))

- Readable, concise code.
See [Code Smells](http://blog.codinghorror.com/code-smells/). FYI: When he refers to "shorter methods" think of them as not necessarily short in terms of lines, but having a single thing to do. Avoid chaining too many methods together or having too much logic on one line.

    For example:
    
    ```ruby
      # the code below is gibberish, but that is what method chaining is. 
      It's easily recognizable due to the many methods chained together by "."
    
       "hello".split(//).join.match(/\w/).gsub
    ```

- [D.R.Y](http://programmer.97things.oreilly.com/wiki/index.php/Don't_Repeat_Yourself) (Don't Repeat Yourself) Code.  
- Sourcemaking's [Refactoring Course](https://sourcemaking.com/refactoring). This is a really in-depth resource on refactoring. 



If you can't think of a way to improve your code because you had an awesome solution the first time, write why you think it's great instead. Do not simply copy the initial solution or leave the refactoring section blank. It's a really important step in the development process!

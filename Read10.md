# JS Debugging

`Errors can (will) happen, every time you write some new computer code.`

## Code Debugging

* Programming code might contain syntax errors, or logical errors.

* Many of these errors are difficult to diagnose.

* Often, when programming code contains errors, nothing will happen. There are no error messages, and you will get no indications where to search for errors.

* Searching for (and fixing) errors in programming code is called code debugging.

## JavaScript Debuggers

>Debugging is not easy. But fortunately, all modern browsers have a built-in JavaScript debugger.

>Built-in debuggers can be turned on and off, forcing errors to be reported to the user.

>With a debugger, you can also set breakpoints (places where code execution can be stopped), and examine variables while the code is executing.

>Normally, otherwise follow the steps at the bottom of this page, you activate debugging in your browser with the F12 key, and select "Console" in the debugger menu.

**The `console.log()` Method is using in debugging steps.**

The `debugger` keyword stops the execution of JavaScript, and calls (if available) the debugging function.

If no debugging is available, the debugger statement has *no effect*.

With the debugger turned on, this code will stop **executing** before it executes the third line.

## Major Browsers' Debugging Tools

### *Chrome*
1. Open the browser.
2. From the menu, select "More tools".
3. From tools, choose "Developer tools".
4. Finally, select Console.

### *Firefox*
1. Open the browser.
2. From the menu, select "Web Developer".
3. Finally, select "Web Console".


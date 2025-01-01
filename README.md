This repository demonstrates a subtle bug in ActionScript 3's error handling within try-catch blocks when using the `trace()` function.  Specifically, runtime errors within the `try` block are silently caught without any output to the console or a trace statement executing even if the error is caught. This behavior can make debugging challenging.  The `bug.as` file shows the problem, and `bugSolution.as` demonstrates a workaround. 
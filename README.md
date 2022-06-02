# Synt Docs

# Table of Contents

## General
1. What is Synt?
    - Examples
2. Installation
    - Download
    - Move to Path
    - Add to Path
3. Modes
    - File
    - Interactive
    - Compile
    - Quit
    - SPyC
    - SPyC Run

## Learn Synt

1. Console Basics
2. Code Iterations
3. Commenting
    - General
    - Info
    - Command
4. Basic
    - Version
    - End
    - Output
    - Input
5. Variables
    - Meaning
    - Types
    - Creation
    - Using Collection Items
6. Functions
    - Meaning
    - Creation
    - Using
    - Call Syntax
    - Return Values
7. Operator
    - Add
    - Subtract
    - Multiply
    - Divide
    - Power
8. Logic
    - Check
    - Condition
    - Operators
9. Special Characters
10. Loop
    - Repeat
    - Loop
11. Iterable Functions
    - Count
    - Insert
    - Remove
    - Delete
12. File
    - Read
    - Write
13. Time
    - Ticks
    - Time
    - Reset Tick
    - Pause Tick
    - Resume Tick
    - Get Tick
14. Console
    - Console
    - Clear
15. Debug
    - Variable Type
    - Restore
    - Error
    - Warn
16. Modules
    - Importing

<h1 id="general-synt">
General
</h1>

<h2 id="what-is-synt">
What is Synt?
</h2>

Synt is a `programming language` and it is very suitable for beginners.
Code is `easy` and really `simple`.
`Syntax` is `user friendly` are really `readable` for person who can read and understand English.
<br><br>
Synt is `free` and `open source`.
It is made with `Python`.
Synt is the `next gen` programming language.
It is made so that updates are `easy` and `fast`.
Synt is made to make `software and game development` `easier` and `faster`.
<br><br>
For the history of Synt, it was initiated by <a href="https://attaditya.is-a.dev/">`Attachment Aditya`</a> in year `2020`.
It was initially expected to be worked for about `1-2 Months`.
Later as time went by, it was expanded to be a larger project.
It will most probably be getting updated and expanded in the future.


<h2 id="examples">
Examples
</h2>
<h3>
Hello Synt
</h3>

```
output "Hello Synt!"
```

<h3>
Create Variables
</h3>

```
var number my_num1 0
```

<h3>
Add Numbers
</h3>

```
var number my_sum 0
add my_sum 10 20 30 40 50 60
```

<h3>
Variable Referencing
</h3>

```
var text name "Synt"
output "Hello #name#!!! Welcome Back!!!"
```


<h2 id="installation">
Installation
</h2>

Synt is created in a way so that it can be run in any systems.
However, the major focus is for `Windows`.
For other system Synt has `Python Source Code` which can be run to use Synt.
In future, there might be versions of Synt targetted for other platforms.
<br><br>
This section is focussing to install synt on `Windows`.
<br><br>
For other platforms you need to have `Python` installed on your system.
After that install the `Source Code` of Synt from `GitHub`.
Run the `Python Source Code` using `Python` to use Synt.


<h3 id="download-synt">
Download Synt
</h3>

Download `Synt Executable` for you through <a href="https://synt.ml/#downloads">`Official Synt Site`</a>.


<h3 id="move-synt">
Move to Path
</h3>

Installing Synt just means moving it to the `Path` you want it to be.
It can be done manually.
This allows Synt to be used portably.
<br><br>
Generally, for `Windows`, it is recommended for `Apps` to be installed in `Programs Files`.
Although this is not mandatory, it is on the user where to install it.
<br><br>
```
Suggested Synt Folder: `C:\Program Files\Synt`
```


<h3 id="add-synt-to-path">
Add to Path
</h3>

Although you might have installed synt in the `Path` you want it to be in, but you still need to access it.
To access synt, you may need to use the `Path` again and again to refer to the `Synt Executable` that will run Synt Code.
<br><br>
A simple solution is to add the `Path` to your `Path` in your `Environment Variables`.
This might sound complicated, but it isn't really that hard.
<br><br>
First of all, copy the `Folder Path` you want to add to your `Path` to your `Environment Variables`.
Now, open your `Environment Variables`.
To do so, start `Run`(`Windows Key` + `R`).
In run, type `sysdm.cpl`.
Once this causes the `System Properties` to open, click on `Advanced`.
Now, click on `Environment Variables`.
Under `System Variables`, click on `Path` and click on `Edit`.
Now, click on `New` and then paste the `Folder Path`.
Finally, click on `Apply` and `OK` on all windows till all `System Properties` windows are closed.
<br><br>
Synt is now globally added to `Path`. You can just refer `Synt` to run Synt.


<h2 id="modes">
Modes
</h2>

On using Synt without console arguments, it asks you for modes.
Synt has two major running modes.
`File Mode` and `Interactive Mode`.
Apart from modes that can run code, there are more modes.
`Quit Mode` and `Compile Mode` are two of them.
Synt also allows code to convert into SPyC (SyntPythonCompiler) that can be run with `Python`.

<h3 id="file-mode">
File Mode
</h3>

To run an existing code using `File Mode` is suggested.
This mode will ask you file path.
It is the complete file location to your code file.
Once code completed it closes.
<br><br>
This mode can be also accesed from directly passing `source code file path` in command line arguments.
The mode key is `*f` and `*file`.
<br><br>
```
synt *f
```
```
synt *file
```
```
synt "main.synt"
```

<h3 id="interactive-mode">
Interactive Mode
</h3>

`Interactive Mode` or `Synteractive` is a good mode to learn and test commands.
This mode allows you to type and run code at same time.
As it runs at same time, it doesn't close until closing through code or force close.
<br><br>
The mode key is `*i` and `*interactive`.
<br><br>
```
synt *i
```
```
synt *interactive
```

<h3 id="compile-mode">
Compile Mode
</h3>

`Compile Mode` is a `command line arguments` based mode.
This mode `compiles` from `synt code` to an `distributable` application.
<br><br>
The mode key is `*c` and `*compile`.
<br><br>
```
synt *c "main.synt"
```
```
synt *compile "main.synt"
```

<h3 id="quit-mode">
Quit Mode
</h3>

`Quit Mode` just closes Synt.
<br><br>
The mode key is `*q` and `*quit`.
<br><br>
```
synt *q
```
```
synt *quit
```

<h3 id="spyc-mode">
SPyC Mode
</h3>

`SPyC Mode` is a `command line arguments` based mode.
This mode compiles from `synt code` to `Python Source Code`.
<br><br>
The mode key is `*spyc`.
<br><br>
```
synt *spyc "main.synt"
```

<h3 id="spyc-run-mode">
SPyC Run Mode
</h3>

`SPyC Run Mode` is a `command line arguments` based mode.
This mode directly exports and runs the `SPyC Output`.
<br><br>
The mode key is `**spyc`.
<br><br>
```
synt **spyc "main.synt"
```


<h1 id="learn-synt">
Learn Synt
</h1>

<h2 id="what-is-console">
What is Console?
</h2>

The console is the main window that opens when Synt or Synt Code is run.
It is the place where you can type and run code in Interactive Mode.
In file mode you can use console to see the outputs of code and give code inputs.


<h2 id="code-parsing">
How Synt Reads Code?
</h2>

First, obviously, Synt gets the code it needs to run.
This code can also be called as `source code`.
<br><br>
Then, Synt breaks the code into `blocks`.
The `blocks` into `tokens`.
<br><br>
Synt uses these blocks and tokens to recognize and execute corresponding commands and code.
Synt runs `block after block`.


<h2 id="commenting-algs">
Commenting in Synt
</h2>

There are three `Commenting Character` options in synt.
The functioning and working of all three is same.
All of them will be ignored during execution.
These are classified on the basis of organizing and how they are supposed to be used.


<h3 id="alg-comment">
General Comments
</h3>

Such comment is an algorithm in synt that will be ignored.
It has no use except for being used as placeholders and of course to comment in between code.
<br><br>
```
comment This is a comment. This will be ignored in execution.
```
```
$ This is a comment. This will be ignored in execution.
```


<h3 id="query-comment">
Info Comments
</h3>

This type of comment is used to `organize` code.
This should be generally used to convey what the following code is about and what it should do.
<br><br>
```
? This is a query comment. This will be ignored in execution.
```


<h3 id="ai-comment">
Command Comments
</h3>

This type of comment is used when using an `AI` to write or analyze code.
Its content will depend on the `AI's` and `custom mods` that are used.
<br><br>
```
> This is an AI command comment. If any AI or mod installed, this might do something.
> It won't do anything in execution.
```


<h2 id="basic-algs">
Basic Algorithms of Synt
</h2>

There are a few basic functions or so called `Algorithms` in synt.
These include basic `input` and `output` functions, as well as `version` function and `end` function.
These are the most primitive functions in synt.


<h3 id="version-alg">
Version
</h3>

This function just outputs the `version` of synt in console.
<br><br>
```
version
```


<h3 id="end-alg">
End
</h3>

This function just ends/pauses the execution of synt.
<br><br>
```
end
```


<h3 id="output-alg">
Output
</h3>

This function outputs the `arguments` passed into the function to the console.
<br><br>
```
output "Hello Synt!"
```


<h3 id="input-alg">
Input
</h3>

This function is slightly more complex than the `output` function.
The first argument it takes is the `Output Variable`.
This is the variable that the `Input` will be stored in.
The second argument is the `Input Prompt`.
This is basically the text that should output before user is asked to input something.
<br><br>
```
input input_var "Enter your input:"
```


<h2 id="var-algs">
Dynamic Programming in Synt with Variables
</h2>

<h3 id="var-means">
What is a Variable in Synt?
</h3>

Synt allows your program to be more `dynamic` with the help of `variables`.
`Variables` are a `sets of characters` that contain some `value` inside them.
It can also be said as `naming` some value and then using the name instead of value later on.


<h3 id="var-types">
Different Types of Variables
</h3>

Synt offers a few types of basic `variables`.
These include `number`, `decimal`, `text`, `binary`, `collection` and `nothing`.
<br><br>
A `number` is a `number` that can be `positive`, `negative` or `zero`.
It can't contain anything apart from `numeric characters` and `negative sign`.
A `decimal` is just like a `number type` that can contain `decimal point`.
A `text` is a `set of characters` enclosed between `double quotes(")`.
A `binary` is a `number` that can only contain `on` and `off`.
It can also be considered as `TRUE` or `FALSE` values, `0` or `1` and `empty` or `non-empty` values.
A `collection` is a `set of items` enclosed between `square brackets([])` and separated by `new line(\n)`.
These can contain other types inside themselves.
A `nothing` is a `variable` that has no value.
<br><br>
```
number ..., -3, -2, -1, 0, 1, 2, 3, ...
decimal ..., -3.5, -2.5, -1.5, 0.5, 1.5, 2.5, 3.5, ...
text "hello", "yo", "SYNT!!!!", "SYYYYYYYYYYYYYYYYYYYNT!!!!", ...
binary on, off
nothing
collection [
    "Text Type"
    "Another Text Type"
    10
    -10
    0
    0.72
    -55.22
    on
    off
]
```


<h3 id="var-decl">
Making a Variable
</h3>

To make a variable, you can use the `var` function.
<br><br>
```
var type var_name "var_value!"
```


<h3 id="var-ref">
Using a Variable
</h3>

To use a variable, you can use the `variable name` enclosed between `hash(#)`.
<br><br>
```
output "Use a variable like #var_name#"
```


<h3 id="coll-ref">
Using an Item in a Collection
</h3>

To get an item from a collection, first refer collection as a variable and then mention the `item index number` enclosed between `< >` just immediately after the collection variable reference.
`item index number` is the amount of items in a collection before the item you want to get.
In simple terms the `item index number` is the `position` of the item in the collection minus 1.
<br><br>
```
output "Lets say collection coll_name has item #coll_name#<0> and #coll_name#<1>!"
```


<h2 id="func-algs">
Avoiding Redundancy in Synt with Functions
</h2>

Repitition of code is a `bad practice` and can make your code cost more time to execute.
Synt however offers the ability to `avoid` this by using `functions`.


<h3 id="func-means">
Declaring a Function
</h3>

A `function` is a `set of instructions` that can be called/referenced to execute the `instructions` inside it for which it was defined.


<h3 id="func-decl">
Making a Function
</h3>

`custom functions` are defined by using the `alg` function.
They take name of list that will contain arguments which can later be used inside the instructions and the function name as parameters.
The `instructions` are enclosed between `{ }`.
<br><br>
```
alg func_name argument_collection {
    output "Created a function. Calling first argument of the function. #argument_collection#<0>!"
}
```


<h3 id="func-ref">
Using a Function
</h3>

After the function is defined it can be called simply by using the `function name` at the start of the line like other functions.
<br><br>
```
func_name
```


<h3 id="func-syntax">
Proper Syntax for a calling a custom Function in Synt
</h3>

`custom functions` can be called in Synt easily but they also take more parameters like the `return value variable` and the `arguments` passed.
<br><br>
```
func_name return_variable arg1 arg2 ...
```


<h3 id="func-rtrn">
Returning a Value from a Function
</h3>

To return a value from a function, use the `result` function.
<br><br>
```
alg func_name argument_collection {
    output "Created a function. Calling first argument of the function. #argument_collection#<0>!"
    result "Returned value!"
}
```


<h2 id="opr-algs">
Synt Mathematical Operations
</h2>

Synt allows user to perform some simple and complex mathematical operations on numbers, decimals, texts and other types.


<h3 id="opr-add">
Adding Numbers
</h3>

To add two numbers, use the `add` function.
<br><br>
```
add output_variable 2 3
? this sets output_variable to 5
```


<h3 id="opr-sub">
Subtracting Numbers
</h3>

To subtract two numbers, use the `subtract` function.
<br><br>
```
subtract output_variable 2 3
? this sets output_variable to -1
```


<h3 id="opr-mul">
Multiplying Numbers
</h3>

To multiply two numbers, use the `multiply` function.
<br><br>
```
multiply output_variable 2 3
? this sets output_variable to 6
```


<h3 id="opr-div">
Dividing Numbers
</h3>

To divide two numbers, use the `divide` function.
<br><br>
```
divide output_variable 6 3
? this sets output_variable to 2
```


<h3 id="opr-pow">
Power
</h3>

To get the power of a number, use the `power` function.
<br><br>
```
power output_variable 2 3
? this sets output_variable to 8
```


<h2 id="logic-algs">
Conditional Programming with Synt
</h2>

In many cases, you may want to perform some action based on some condition.
Synt provides a way to do this with conditional programming.
<br><br>
Synt has two functions for these cases.
The first one can be used to check if a condition is true or false.
The second one can be used to perform an action if the condition is true or false.


<h3 id="logic-chk">
Check and Return
</h3>

To check if a condition is true or false, use the `check` function.
<br><br>
```
check output_var compare_var_1 check_operation compare_var_2
? this sets output_var to on if the condition is true, and to off if the condition is false
```


<h3 id="logic-cond">
Check and Perform
</h3>

To perform an action if a condition is true or false, use the `condition` function.
<br><br>
```
condition compare_var_1 check_operation compare_var_2 {
    output "Condition is true!"
} {
    output "Condition is false!"
}
? this will output "Condition is true!" if the condition is true else "Condition is false!"
```
```
condition compare_var_1 check_operation compare_var_2 true_action false_action
? this will execute the true_action if the condition is true else the false_action
```


<h3 id="logic-opr">
All Conditional Operations
</h3>

Here's the list of all the conditional operations that can be used with `check` and `conditional` functions:
<br><br>
```
"equals to"               equals        =
"not equals to"           not           !=
"greater than"            greater       >
"less than"               less          <
"greater than equal to"   notless       >=
"less than equal to"      notgreater    <=
"contains"                contains      <-
"does not contain"        notcontains   !<-
"starts with"             starts        _%
"does not start with"     notstarts     !_%
"ends with"               ends          %_
"does not end with"       notends       !%_
```


<h2 id="str-spl">
Special Characters
</h2>

Sometimes a character might be needed in a text but it can't be used directly.
In such cases special character keywords are used which will replace the keyword with the special character.
<br><br>
Here's the list of special characters that can be used in Synt:
<br><br>
```
#NEWLINE       '\n'
#INDENT        '\t'
#BACKSPACE     '\b'
#START         '\r'
#SPACE         ' '
#LEFTSQUARE    '['
#RIGHTSQUARE   ']'
#LEFTCURLY     '{'
#RIGHTCURLY    '}'
#COMMA         ','
#DOT           '.'
#SEMICOLON     ';'
#COLON         ':'
#EQUAL         '='
#HASH          '#'
#QUESTION      '?'
#EXCLAMATION   '!'
#QUOTE         '"'
#APOSTROPHE    "'"
```


<h2 id="loop-algs">
Repitition and Looping Code
</h2>

When some code or function is needed to repeated `simultaneously` with some or no variation then the writing everything `manually` is really difficult.
And when repitition to be done according to a variable or till the condition is true, that is dynamically changing to a variable, then the writing is even more difficult.
<br><br>
To make the writing of such code easier, Synt also allows another common feature in programming languages called `looping`.
<br><br>
`Loops` are used to repeat a block of code a number of times.
<br><br>
In Synt, there are two types of loops.
One is `statically repeating` and the other is `dynamically repeating`.
<br><br>
Loops that are `statically repeating` just follow a given number of times and then stop.
These don't update the argument dynamically and are just a method to reduce `code redundancy`.
This type of loop can be used with the `repeat` function.
<br><br>
Loops that are `dynamically repeating` are used to repeat a block of code a number of times that isn't fixed.
These are used to update the argument dynamically.
This type of loop can be used with the `loop` function.


<h3 id="repeat-alg">
Statically Repeating Loops
</h3>

The `repeat` function is used to repeat a block of code a given number of times.
<br><br>
```
alg func args {
    output "Hello Synt!"
}
repeat 10 func
? executes func 10 times
```


<h3 id="loop-alg">
Dynamically Repeating Loops
</h3>

The `loop` function is used to repeat a block of code a number of times that is dynamically changing.
<br><br>
```
? count down
var number cd 10
var binary do_it

alg func args {
    output #cd#
    subtract cd #cd# 1
    check do_it cd >= 0
}

loop do_it func
? count downs to 0
```


<h2 id="itr-algs">
Functions for Collections and Other Iterables
</h2>

Iterables are the variable types that are made up of multiple values.
These include `text` composed of `characters` and `collections` containing `items`.
<br><br>
Sometimes you need to use an iterable to store multiple values and data.
In such cases you would need to get length, add, remove and do other stuff with the iterable.
Synt allows such functions.


<h3 id="count-alg">
Length of an Iterable
</h3>

To get the `length` of an `iterable`, you can use the `count` function.
<br><br>
```
var number len
count len obj
? returns the length of obj, obj is predefined
```


<h3 id="insert-alg">
Inserting an Item to an Iterable
</h3>

To insert an `item` into an `iterable`, you can use the `insert` function.
<br><br>
```
insert obj item index
? inserts item into obj at index, obj is predefined
```


<h3 id="remove-alg">
Removing an Item from an Iterable
</h3>

To remove an `item` from an `iterable`, you can use the `remove` function.
<br><br>
```
remove obj item limit
? removes item from obj, obj is predefined, removes limit amount of item
```


<h3 id="delete-alg">
Removing an Item at Given Index from an Iterable
</h3>

To remove an `item` at a given `index` from an `iterable`, you can use the `delete` function.
<br><br>
```
delete obj index
? removes item at index from obj, obj is predefined
```


<h2 id="file-algs">
Reading and Writing Files
</h2>

Synt allows you to access local files on your computer.
This could be helpful to create cache for next run or to save data.
<br><br>
Synt can read and write files.


<h3 id="read-alg">
Reading a File
</h3>

To read a file, you can use the `read` function.
Just note that the file should exists.
<br><br>
```
var text data
read data "file.txt"
? reads "file.txt" and stores it in data
```


<h3 id="write-alg">
Writing a File
</h3>

To write a file, you can use the `write` function.
If file does not exist, it will be created.
If file does exist, it will be overwritten.
<br><br>
```
write "file.txt" data
? writes data to "file.txt"
```


<h2 id="time-algs">
Synt Time and Ticking
</h2>

<h3 id="synt-ticking">
Ticks in Synt
</h3>

Synt has a customizable `tick system` that allows using and calculating time slightly easier.
One tick is equal to one millisecond.
Ticks can be reset, paused and resumed.
It can also be set to a specific value.


<h3 id="synt-time">
Time in Synt
</h3>

Synt also has a `time system`.
This system can not take any inputs.
It is made only for outputs.
It isn't affected by ticks.


<h3 id="reset_tick-alg">
Resetting Ticks
</h3>

To reset ticks, you can use the `reset_tick` function.
This will set the tick value to 0, which was initial value.
<br><br>
```
reset_tick
? resets ticks
```


<h3 id="pause_tick-alg">
Pausing Ticks
</h3>

To pause ticks, you can use the `pause_tick` function.
This will stop updating ticks until resumed.
<br><br>
```
pause_tick
? pauses ticks
```


<h3 id="resume_tick-alg">
Resuming Ticks
</h3>

To resume ticks, you can use the `resume_tick` function.
This will resume updating ticks.
This might give you an error if you try to resume ticks when they are already resumed.
<br><br>
```
resume_tick
? resumes ticks
```


<h3 id="get_tick-alg">
Getting Ticks
</h3>

To get ticks, you can use the `get_tick` function.
This will return the current tick value.
<br><br>
```
var number this_tick
get_tick this_tick
? returns ticks and stores it in this_tick
```


<h2 id="console-algs">
Handling Running Console with Synt
</h2>

When Synt is unable to do something directly, you might think to access console to run it through other means.
This is possible because Synt has the ability to access the console it is being run on.
You can also use console commands to change the other console properties.


<h3 id="console-alg">
Run Console Commands
</h3>

Synt has a `console` function that allows you to run console commands.
This is useful for changing the console properties that you want to but can't directly using Synt.
Not only console properties but if you want even run other console commands, you can use this function.
<br><br>
```
console "command"
? runs "command" in console
```


<h3 id="clear-alg">
Clearing Console
</h3>

To clear the console, you can use the `clear` function.
This will clear the console.
<br><br>
```
clear
? clears console
```


<h2 id="debug-algs">
Debugging in Synt
</h2>

Synt has an useful set of `debug functions` that can be used to debug your code.
Debugging means to find out what is happening in your code.
Generally it is used to find out what is wrong with your code, that is wy you are getting an error.
However, it can also be used to understand how your code works.


<h3 id="info-alg">
Get Variable Type
</h3>

To get the type of a variable, you can use the `info` function.
This will return the type of the variable.
<br><br>
```
var number this_number
var text type
info type this_number
? returns type of this_number and stores it in type
```


<h3 id="restore-alg">
Continuing Program after Error
</h3>

To continue the program after an error, you can use the `restore` function.
This will continue the program after an error.
<br><br>
```
restore
? continues program after error
```


<h3 id="error-alg">
Custom Error Messages
</h3>

To create a custom error message, you can use the `error` function.
This will create and run a custom error message.
<br><br>
```
error "message"
? displays error with "message" as content
```


<h3 id="warn-alg">
Custom Warning Messages
</h3>

To create a custom warning message, you can use the `warn` function.
This will create and run a custom warning message.
<br><br>
```
warn "message"
? displays warning with "message" as content
```


<h2 id="ex-res-algs">
Modules and External Resources
</h2>

Sometimes you want to organize your code in modules or other files that need to be run.
Synt allows you to import and run modules.
When you import a module, it will run the code in the module.
If there are any custom functions in the module, they will be available in the main file and while running in other modules that will be imported orderwise next.


<h3 id="module-alg">
Importing Local Files as Modules
</h3>

To import a local file as a module, you can use the `module` function.
This will import and run the module.
<br><br>
```
module "module_name"
? imports file "module_name.synt" as module and runs it
```


<a href="https://synt.ml">
Synt
</a>

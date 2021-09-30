# 2021-09-30

Greetings,

Today we have learned about the programming paradigms.  Specifically, he
covered ​​imperative, procedural, object-oriented, declarative,
logic, mathematical, reactive and functional paradigms. His presentation
includes code examples illustrating different paradigms. Please have a look at
the examples and try to spot the differences. Good work!

[github:prog-1/lesson09](https://github.com/prog-1/lesson09) repository
contains programs that we have discussed today. We have covered various
implementations of the min/max program. From these programs you need to
understand and remember:

-   various types of if-else statements and their differences:

-   if <condition> { ... }

-   if <condition> { ... } else { ... }

-   if <condition> { ... } else if { ... } ...

-   if <condition> { ... } else if { ... } else { ... } ...

-   [early return statement](https://golang.org/ref/spec#Return_statements)

-   tuple assignments and swapping variable values

-   min, max = max, min.

Also, we went through [more
examples](https://github.com/prog-1/lesson09/blob/main/07_conditions/conditions.go)
of integral types and conditions.

Your homework is the following:

-   [Here](https://github.com/prog-1/lesson09/blob/main/09_palindrome/palindrome.go)
    is a program that checks if a 3-digit number is a
    [palindrome](https://en.wikipedia.org/wiki/Palindrome), e.g. 232 is a
    palindrome, 223 is not. Please understand how this program works. Our next
    lesson will be based on this program (we will start talking about
    [for-loops](https://tour.golang.org/flowcontrol/3)). If you understand this
    program, the material of the next lesson won't be hard for you to
    understand.

-   Complete a quiz on the topic
    "Conditions". The test is for your self-assessment (there are no grades for
    the test). Next lesson we will discuss it.

-   Continue implementing exercises from [the assignment
    "conditions"](https://github.com/prog-1/conditions). The exercise
    submission deadline is 11.10.21. Partial implementation of the "speed
    conversion" task that we started today is
    [here](https://play.golang.org/p/gQ62_58Tn3w).

IMPORTANT: There will be a graded mid-term test on Monday, October 11. It will
contains a test and a programming task on the following topics:

-   working with files, git and GitHub

-   basic Go program structure

-   if statements.

If you are not fully familiar with these topics, please ensure that all your
questions are answered before the test. We are available to answer your
questions privately as well in our Telegram
group.

Best wishes,

Jaroslavs and Pavel

# 2021-09-27

Greetings,

We had our first lightning talk given today about the ABL programming language,
which is a strongly typed, late-bound, English-like programming language. Good
work!

Today we have covered few common mistakes with the home assignments and your workflows:

-   Your code should go between curly brackets in main.

-   Please use only the material known to everyone. Let us know if you find the
    assignments too easy, and we will come up with a dedicated project for you.

-   Please use meaningful commit messages.

-   Consider using the [short variable
    declaration](https://golang.org/ref/spec#Short_variable_declarations).

-   Open the cloned folders with Visual Studio Code! You should open folders
    that contain go.mod file to ensure the language server works in vscode (it
    gives you code completion, navigation, documentation, etc), and you can
    easily run the programs.

Relevant code from our lesson today is at
<https://play.golang.org/p/dL25ynO89iO>.

Our new topic was introduction to
[if-statements](https://golang.org/ref/spec#If_statements). We have used
[github:prog-1/lesson08](https://github.com/prog-1/lesson08) repository to
demonstrate if and if-else statement usage. Some extra material mentioned was:

-   Early exit using the [return
    statement](https://golang.org/ref/spec#Return_statements).

-   Comparing values using the [comparison
    operators](https://golang.org/ref/spec#Comparison_operators) ==, <, <=, >,
    >=, !=. E.g. if d < 0 { ... }.

-   Use of the integral int type (see the [numeric
    types](https://golang.org/ref/spec#Numeric_types)) and two
    [operators](https://golang.org/ref/spec#Arithmetic_operators):

-   Integer division (aka truncated division) "/", which returns the quotient.
    E.g. 13/4 == 3.

-   The remainder operator "%". E.g. 13%4 == 1.

IMPORTANT: This Thursday is the deadline for the [git-basics homework
assignment](https://github.com/prog-1/git-basics)!

Your homework is:

-   Continue with the [unit-conversions
    assignment](https://github.com/prog-1/unit-conversions).

-   Start solving [conditions
    assignment](https://github.com/prog-1/conditions). Familiarise yourself
    with the assignment.

Optional:

-   Implement programs from the [conditions
    assignment](https://github.com/prog-1/conditions) and create PRs on GitHub
    for us to check them.

Please use the lesson recording and do not hesitate to ask questions if you
have any. Feel free to discuss the homework assignments with your classmates,
and use our Telegram group for this - we absolutely support you sharing code
snippets, discussing issues and solving those together. Extra credits for doing
code reviews on GitHub for each other and helping with the assignments through
GitHub.

Cheers,

Jaroslavs and Pavel

# 2021-09-21

Greetings,

Congratulations! Today we had our first test. Woohoo (-; The results were
published. We don't accept any responses anymore.

Those of you who haven't submitted or haven't done the test will have a chance
to demonstrate ability to work with version control systems during the
semester. Given the fact that we consult online (virtually at any time) and
provide you with the recordings of the lessons, we expect that you get prepared
for tests, and participate timely. We won't allow you to handle testing
retrospectively. The same goes for your homework assignments.

We'd like to remind you that the final grade will contain several parts like
the final test, home and class work. Every grade will be weighted within its
group. It means that each individually taken value (except for the final test)
doesn't affect your semester grade too much.

Thank you for actively participating today! It was a pleasure for us. Next
lesson we won't get new materials, but rather focus on writing small Golang
programs. This will give you more practise and ensure you understand program
structure, math operations, output, variables, etc.

I seem to lose my presentation after someone presents their screen. Please
interrupt the lesson and ask me to ensure my screen is visible if this is
happening, otherwise my screen won't be visible to you from the recording. You
have pinged me once today with this, but please don't be shy and interrupt
immediately if you see this is happening again. My or Pavel's screens MUST be
visible for the recording.

Since my screen wasn't visible, I've created a recap video
<https://youtu.be/ZputPY4jXRA>. The video contains somewhat incorrect
information at 5:40 when I type that float64 contains numbers. In reality types
don't contain anything - variables do! Somewhat better phrasing would be
"variables of type float64 contain floating-point numbers".

Please let us know if there are more things missing and we'll do our best
answering those on the Telegram group, over email, and maybe even creating
extra video material.

Few aspects to focus on:

-   We "Open Folder..." (not a file or a workspace - a FOLDER)

-   We execute git mod init lesson06 to create Go specific workspace

-   We create a directory + main.go file per program e.g. hello/main.go or minmax/main.go

-   It's important to ensure your programs are saved!

-   We run our programs by executing git run ./hello or git run ./minmax from CLI

We also forked <https://github.com/prog-1/unit-conversions> to
<https://github.com/yarcat/unit-conversions> and implemented a [rectangle
program](https://github.com/yarcat/unit-conversions/blob/main/rectangle/rectangle.go).
During our class we had a problem with passing tests, because our tests
expected a very specific output format, which was [fixed by this set of
changes](https://github.com/yarcat/unit-conversions/compare/aed2a1959e3fa3059684276081579a9d7e0b743a...yarcat:1689057a45643d1eace6d9a8c35cca2697981539).

Your homework is

-   Self-study

-   <https://gobyexample.com/hello-world>

-   <https://gobyexample.com/values>

-   skip those true/false parts

-   <https://gobyexample.com/variables>

-   int is a numeric type that can contain only integral values, unlike
    float64, which can contain floating-point numbers

-   We haven't discussed the assignment operator "=", which assigns values to
    variables. When we use fmt.Scan(&x), we allow the Scan function to assign
    something into x, but x = 11.5 explicitly assigns 11.5 to x. We'll focus on
    this more next time. Try to understand it though.

-   Understand why min(a,b)=(a+b-|a-b|)/2 and max(a,b)=(a+b+|a-b|)/2

-   Fork and clone <https://github.com/prog-1/unit-conversions>

-   Understand the [rectangle
    implementation](https://github.com/yarcat/unit-conversions/blob/main/rectangle/rectangle.go)

-   Implement circle, speed and temperature programs. Those will be very similar to the rectangle.

-   The deadline for this assignment is 30/09/2021.

Best regards,

Jaroslavs and Pavel

# 2021-09-16

Hi all,

IMPORTANT ANNOUNCEMENT: Next time (20.09.2021) we will have a 5-7 minute long
test focused on a common git/github workflow. We expect you to

-   Understand how to create directories and files from the command line

-   Initialize new or clone existing git repos

-   Add/remove/modify the working directory

-   Commit local changes

-   Update the remote repository

-   Be able to execute the following scenario:

## Clone or pull (if it was already cloned) a remote repository.

git clone <git@github.com>:user/repo.git

## Enter the directory.

cd repo

## Modify working directory e.g. edit, add, mv, delete files.

## e.g. change or add a file

nano world.txt

## Stage changes.

git add world.txt

## Commit changes locally.

git commit -m 'modified world.txt'

## Push changes back to the remote repository.

git push

Today we have covered three important topics + an introduction to the Go
programming language:

1) Avoiding common mistakes when working with git

-   You need git init to initialize a new local repository.

-   Repositories cloned with git clone are already initialized. 

-   You have to work inside of the directory handled by git.

2) Collaborating with your classmates on a single repository. See [Inviting
collaborators to a personal
repository](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-user-account/managing-access-to-your-personal-repositories/inviting-collaborators-to-a-personal-repository)
for instructions.

3) Development environment setup. We have created a [playlist on
YouTube](https://youtube.com/playlist?list=PL4cEX28Krd-X1UbQ5245CNJM7peDr5YE-)
that should help you with the Go + VS Code setup process at home.

[Go (programming
language)](https://en.wikipedia.org/wiki/Go_(programming_language))

Go is a relatively young programming language developed by Google. It is
syntactically similar to C, but equipped with memory safety, garbage
collection, structural typing and built-in concurrency.

[A minimal Go program](https://play.golang.org/p/LZuktSFVCfX) looks like this:

package main

func main() {}

We've also looked at [a larger program](https://play.golang.org/p/jTtU09KwU9Q)
which contained:

-   Comments

-   Imports

-   Simple output functions

-   Output functions with formatting

-   Variables

We will be focusing more on the Go program structure, functions, variables,
algorithms and many other interesting things.

Your homework is

-   Prepare for the test

-   Complete the second (collaborative) part of the [git-basics](https://github.com/prog-1/git-basics) assignment

-   Setup Go + VS Code environment

Optional homework

-   Try to understand the [larger
    program](https://play.golang.org/p/jTtU09KwU9Q) blocks e.g. comments,
    output statements, etc. We will focus on this more in the future, so do not
    worry about it too much.

-   Check out https://gobyexample.com/ and https://tour.golang.org/

-   Play around and get used to reading documentation and examples

-   Familiarise yourself with the unit conversion
    [assignments](https://github.com/prog-1/unit-conversions) we will be
    covering next time. Try to
    [fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) the
    repository, clone it, and run the programs e.g.
    <https://youtu.be/m1ArTLmCVRE>

Best regards,

Jaroslavs and Pavel

# 2021-09-13

Hi all,

Today we had more practice using Git. Furthermore, we created
[GitHub](http://github.com/) accounts, configured them and learned about remote
repositories. Thank you for the many questions that you have asked.

We remind you that we have a Telegram group  for our lesson. Please join it, if
you haven't done so yet.

During the GitHub account setup it is important [to configure SSH keys for
authorization](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent).
At home you should be able to reuse the keys that you have created during the
class using a passphrase. If it doesn't work, you may reconfigure and add the
SSH keys again at home, similarly to how we did it during the class.

Your home work for the next lesson:

1.  Please fill [this form](https://forms.gle/BX1shzqRJvuMzvVx6) to send us
    your GitHub account name, if you haven't done so in the class. Optionally,
    you can send us your SSH keys (~/.ssh/id_ed25519 and ~/.ssh/id_ed25519.pub
    files), so that we can recover an access to your GitHub repositories in the
    class, in case you lose an access. You won't be able to submit assignments
    without sending us your account information.

2.  Create a GitHub repository as we did in the class and create a commit with
    a change (it can be any change) to the repository (see the recording for
    guidance).

3.  Create a repository from [this](https://github.com/prog-1/git-basics)
    (click "Use this template") template and complete the first part of the
    assignment (section "Working in your own GitHub repository"). This
    assignment is graded.

Best wishes,

Jaroslavs and Pavel

# 2021-09-09

Hi all,

Thanks for your active participation in the lesson today, presenting your
screens, following the tasks and asking questions. It is especially important
we interact, since we are remote teachers, and there is no other way for us to
provide you with the best learning experience.

Please join the Telegram group: [REDACT] and do not hesitate to ask us any time
you have questions, and we’ll do our best to answer those.

Today we have discussed Version Control (as a concept) and Version Control
System (as a software) with the focus on git-scm. Git is going to be our
primary collaboration tool in the future, and it is important you understand
its concepts and feel comfortable working with it.

Please go through the slides of the deck [1] discussed today (we will get to
repository hosting services next time). Watch the lesson recording [2], if
needed. Review Git commands in the Git Cheat Sheet [3]. Ensure you complete the
exercises from the deck, as well as this home work [4].

It is important that you feel comfortable working with CLI (command line
interface). Please ensure you can create, rename files and directories, edit
files (remember the nano editor [5] from today’s lesson?), navigate your file
system and do other operations from CLI. For that please play again the
file://maniac game using only (!!!) CLI and don’t forget about the commands
cheat sheet [6] from the last lesson.

Note: this is not a part of the official home work. Extra materials that you
may find useful include An Intro to Git and GitHub for Beginners (Tutorial)
[7], Learn Git Branching [8] and Git Exercises [9]. We expect you find the
material interesting, but you will (and should) have a gazillion of questions.
Those are highly welcome, and we’d be glad to discuss them in the Telegram
group.

Tip of the day: Modify your ~/.bashrc file and ensure it contains export EDITOR=nano [10].
Learning ViM [11] is also fun (-; Check out vimtutor [12] for some help!

[1] https://prog-1.github.io/syllabus/slides/03_vcs.pdf
[2] [REDACT]
[3] https://prog-1.github.io/syllabus/git.html
[4] https://prog-1.github.io/syllabus/tasks/03_git.html
[5] https://www.nano-editor.org/
[6] https://prog-1.github.io/syllabus/commands.html
[7] https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners
[8] https://learngitbranching.js.org/
[9] https://gitexercises.fracz.com
[10] https://askubuntu.com/a/915638
[11] https://www.vim.org/
[12] https://superuser.com/questions/246487/how-to-use-vimtutor


Best wishes,
Jaroslavs and Pavel

# 2021-09-06

Hi all,

Thank you for your active participation in the lesson on Monday. We saw that
you had fun playing the game just like we did!

You can find the lesson recording here: [REDACT]

Your home exercise until this Thursday is practicing using Windows Command
Prompt and Bash by playing the file://maniac game. You need to complete the
game three times: 1) using Windows File Explorer, 2) using Windows Command
Prompt, and 3) using Bash. Here is a cheat sheet with the commands that you may
need: https://prog-1.github.io/syllabus/commands.html.

You can download Git+Bash here: https://git-scm.com/download/win. Installation
instruction video: https://youtu.be/06_FZjebjEE.  You can download the
file://maniac game here:
https://born-frustrated.itch.io/filemaniac/download/eyJleHBpcmVzIjoxNjMwOTU2NjM1LCJpZCI6MzYyODAzfQ%3d%3d.s5XEnQfIn9d8gFiFGnPrGUH2ggY%3d.
Both downloads are available in the Google Drive directory: [REDACT].

From now on, the Google Drive directory, which includes all course materials,
will be accessed by the following link: [REDACT]

Please note that the Google Meet link for the further lessons will be the same:
[REDACT]. Please make sure that you can quickly access it at the beginning of
every lesson.


Best wishes,
Jaroslavs and Pavel


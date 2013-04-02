## Lesson 1: Linux basics

1. **Directory hierarchy on hard drive**

    ``
    /usr
    /tmp
    /home
    ``

2. **General stuff about the shell**
    * How commands are executed and parameters are passed
    * Tab completion (Repeat this until they throw up)

3. **Directory related commands**
    ``
    cd, ls, mkdir, cp, rm
    ``

4. **Editors and how to start them from the commandline**
    * ``gedit`` and ``kate`` are simple
    * ``vim`` and ``emacs`` are hard
    * I use vim, you probably shouldn't do so, yet!

5. **Permissions**
    * Used to grant r/w/x access to directories and files
    * Display via ``ls -la``
    * Owner, Group, All
    * Can make files executable ``chmod +x file``

6. **Shell scripting 1**
    * Somewhat similar to ``*.BAT`` files
    * Collection of shell commands
    * Basically text files
    * Should get file permissions to execute

7. **Shell scripting 2**
    * Either type ``bash <script>`` or give proper permissions and ``./script``
    * Shebang: Tells the shell which program *understands* the following code
    * Variables: define and access a variable

## Lesson 1: Linux basics

1. **Directory hierarchy on hard drive**

    ``
    /usr
    /tmp
    /home
    ``

    * Go into detail about $HOME/jens

2. **General stuff about the shell**
    * How commands are executed and parameters are passed
        * ``command`` followed by optional and then required arguments
        * ``-h`` or ``--help``
    * Tab completion (Repeat this until they throw up)
    * All programs that can be executed over the GUI menues can be executed from CLI!

3. **Directory related commands**
    ``
    cd, ls, mkdir, cp, rm
    ``
    * List current dir (``$HOME``)
    * Create new dir ``uni`` and ``cd`` into it
    * ``touch diplomarbeit.tex``, copy it to ``masterarbeit.tex`` and delete ``diplomarbeit`` after that


4. **Editors and how to start them from the commandline**
    * ``gedit`` and ``kate`` are simple
    * ``vim`` and ``emacs`` are hard
    * I use vim, you probably shouldn't do so, yet!

5. **Permissions**
    * Used to grant r/w/x access to directories and files
    * Display via ``ls -la``
    * Owner, Group, All
    * Can make files executable ``chmod +x [file]``

6. **Shell scripting 1**
    * Somewhat similar to ``*.BAT`` files
    * Collection of shell commands
    * Basically text files
    * Should get file permissions to execute

7. **Shell scripting 2**
    * Either type ``bash [script]`` or give proper permissions and ``./[script]``
    * Shebang: Tells the shell which program *understands* the following code
    * Variables: define and access a variable
    * Store output of a command in a variable

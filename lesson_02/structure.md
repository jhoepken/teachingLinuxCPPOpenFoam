# Lesson 2

## C++ - The very basics

1. **Simplified way from source to executable**

    ```
    +-----------+      +--------+       +----------+
    |Sourcefile |----->|Compiler|------>|Executable|
    |   .C      |      |  g++   |       |          |
    +-----------+      +--------+       +----------+
    ```

2. **The most basic C++ Program**
    
    ```
    // helloWorld.C
    int main()  // This is where any C++ program starts
    {
        return 0;   // it's an int and must return something
    }
    ```

    Explain:
    * How are lines ended?
    * What commands can be used? Is there a list for that?

3. **Compiling**
    
    The text file containing the source for our program (helloWorld.C) must be
    translated into something the computer understands: 1 and 0

    ```
    g++ -o helloWorld helloWorld.C
    ```

    Explain:
    * Compiler
    * Output file (the executable program)
    * Input file(s)

4. **Execution**

    ```
    ?> ./helloWorld
    ```
    The result is that *nothing* happens, because we told C++ so.

5. **Printing something**

    ```
    #include <iostream>
    int main
    {
        std::cout << "hello world" << std::endl;
        return 0;
    }
    ```

    Explain
    * ``include``
    * ``std::`` namespace (polluting global namespace, multiple usaage of same
            names, etc.)

6. **Improving the code**

    ```
    #include <iostream>
    using namespace std;
    int main
    {
        cout << "hello world" << endl;
        return 0;
    }
    ```

## C++ - Add all natural numbers $\left[1;1000\right]$

1. **Variable declaration**

    ```
    int i;
    int i = 0;
    int i(0);
    int a=0, b=3;
    unsigned int foo(3);
    ```

1. **Basic math**

    ```
    int i(0);
    i = i + 4;
    i += 4;
    i++;
    i /= 2;
    ```

2. **For loops**

    ```
    for (int n=1; n>=1000; n++)
    {
        cout << n << endl;
    }
    ```

# Hello, Rust

Let us begin with the classic Hello, World!

```
fn main() {
    println!("नमस्कार, विश्व!");
}
```

The above code prints "Hello, World!" in Sanskrit. 

If you already know programming lanagues such as C, you can already relate an equivalent code. ```fn main()``` servers as the main entry point of the program. ```println!``` is system macro that prints text on to the console. Note the ```!``` at the end of calling ```println``, this means that it is a macro and not a function that is being called. 

Few other things to note:
1. ```fn``` is the keyword used to define a function
2. ```main``` is a special function, which serves as the main entry point of the rust program. This is similar to many other compiled laguages influenced by C progrogramming language. 
3. ```;``` - semicolon is used as a statment terminator. Multiple statements can be present in one line, separated by a ```;``` - semicolon. However, it is good practise to have only one statement per line for better code readability. 
4. Unlike C/C++, there is no return statement at the end of the ```main()``` function, and no value is required to be returned. 
5. ``` { ... } ``` - curly braces are used to define a code block. In this case, the code block is associated with the function ```main()``` 

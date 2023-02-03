# Indecision-App

Classical To-Do app with [What should I do?] button which fires popup window with one of the options.

## What I learned?

- ES6 + JSX
- Setup Babel
- React basics
- Setup Webpack
- SASS basics

## Requirements

- Node 14
- x86_64 architecture. If you are using Mac with M1 chip you have to run the terminal with x86_64 instructions. You can add these two lines into your `.zshrc` file to be able to change architecture in your terminal: 
    ```
    alias arm="env /usr/bin/arch -arm64 /bin/zsh --login"`
    alias intel="env /usr/bin/arch -x86_64 /bin/zsh --login"
    ```
  now when you run `intel` command in the terminal it'll switch to x86_64 architecture. With `arm` command you can go back to arm64 architecture.
# Readme

# Menu
- Bootcamp
- Information
- Syntaxis

# 1. Bootcamp
<h1 align="center">Introduction to programming & Javascript - Week 1</h1>

# Week challenges week 1 
- <h1>(Tuesday 19/07/2022)</h1>
1. Create an explanation about Interpreted and Compiled programming Languages. 
    - Compiled languages: are converted directly into machine code that the processor can execute. As a result, they tend to be faster and more efficient to execute than interpreted languages. <br>
    <strong>Example: watching a movie fully dubbed.</strong><br>
    
    - Interpreted languages: are: Ran through a program line by line and execute each command. Interpreted languages were once significantly slower than compiled languages. But, with the development of just-in-time compilation, that gap is shrinking.<br>
    <strong>Example: watching a movie with subtitles (understanding is a bit slower).</strong><br>
    <br> 

2. Is Java compiled or interpreted, or both?
    - Java: Is first compiled into bytecode which JRE can understand. ByteCode is then interpreted by the JVM making it as interpreted language.
    <strong>(both complied and interpreted language)</strong><br>
    <br>
3. Pseudocode Currency Converter exercise.
    - START <br> 
    Amount (USD) <-- GET <br> 
    BTC rate <--  GET FROM(https://www.coindesk.com/price/bitcoin/)<br> 
    Total <-- Amount (usd) * BTC rate <br> 
    PRINT  Total <br> 
    END
4. Learn about High and Low level languages.
    - <strong>A Low Level programing language</strong> is considered machine language, and it´s how a program can comunicate with the computer without being compiled nor interpreted. they are very diffucult for humans to understand.

    - <strong>A high level programming Language</strong> is easy to read, write and maintain they are human friendly, As it's more understandable. 


- (Wednesday 20/07/2022)
1. Your date of birth in the matrix? exercise
    - 1994 -> 1024 + 512 + 256 + 128 + 64 + 8 + 2 <br>

    1994-1024=970<br>
    970-512=458<br>
    458-256=202<br>
    202-128=74<br>
    74-64=10<br>
    10-8=2<br>
    2-2=0<br>


    1024 - 512 - 256 - 128 - 64 - 32 - 16 - 8 - 4 - 2 - 1<br> 
    1  ------ 1 ---- 1 ---- 1 -- 1 --- 0 --- 0 - 1 - 0 - 1 - 0<br> 

    `Decimal: 1994`<br>
    `Binary: R/1 1 1 1 1 0 0 1 0 1 0`<br>
    <br>
2. MIPS Exercise<br> 
    <strong>Create a program to add two numbers given by the user:</strong><br>
```assembly
.data
        welcome: .asciiz "\nWelcome\n"
        result: .asciiz "\nThe result is: "
        number_one_msg: .asciiz "\nEnter the first number: "
        number_two_msg: .asciiz "\nEnter the second number: "
  .text
        main:
              # welcome message
              li $v0, 4
              la $a0, welcome
              syscall

              # user input
              li $v0, 4
              la $a0, number_one_msg
              syscall

              li $v0, 5
              syscall

              # saving user input
              move $t0, $v0

              # user input
              li $v0, 4
              la $a0, number_two_msg
              syscall

              li $v0, 5
              syscall

              # saving user input
              move $t1, $v0

              # adding the user numbers
              add $t2, $t0, $t1

              # showing result number
              li $v0, 4
              la $a0, result
              syscall

              # printing number
              li $v0, 1
              move $a0, $t2
              syscall
``` 
<br> 
    <strong>Program that display your name:</strong>

```assambly
.data
	      my_name: .asciiz "\nChristian\n"
  .text
	      main:
              li $v0, 4
              la $a0, my_name
              syscall
```


- (Thursday 21/07/2022)

1. Print special numbers exercise
2. Bad Code exercise
3. Bad Code 2 exercise
4. Follow Git Course

- (Friday 22/07/2022)


# Week challenges week 2
- (Tuesday)

- (Wednesday)
- (Thursday)
- (Friday)


# 2. Information
# 3. Syntaxis
- [markdown](markdown/README.md)
- [html](html/README.md)
- [css](css/README.md)
- [javascript](javascript/README.md)



asdf
# Readme

# Menu
- Bootcamp
- Information
- Syntaxis

# 1. Bootcamp
<h1 align="center">Introduction to programming & Javascript - Week 1</h1>

# Week challenges week 1 
- <h2>(Tuesday 19/07/2022)</h2>
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


- <h2>(Wednesday 20/07/2022)</h2>
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


- <h2>(Thursday 21/07/2022)

1. Print special numbers exercise
    - **for**<br>
```assembly 
    for (let i = 0; i <= 100; i++) {
    if(i % 2 == 0){
    console.log(i);
        }
    }
```

   - **while**<br>
```assembly    
    let i = 0;
    while (i <= 100) {
        if (i % 2 == 0) console.log(i);
        i++;
    }
```
   - **do while**<br>
```assembly
let i = 0;
do {
  if(i % 2 == 0)console.log(i);
  i++
} 
```
<br>

2. Bad Code exercise
    - Corrected code  

```javascript
    var cond = false;

    if (cond == true) {
    console.log('The cond variable is true');
    } else {
    console.log('The cond variable is false');
    }
```

3. Bad Code 2 exercise
    - Corrected code 

```javascript
    var n = 100;

    if (n == 100) {
    console.log('This is a special number!');
    } else if (n < 1000 && n % 10 == 0) {
    console.log('This number is almost special');
    } else {
    console.log('Just a regular number');
    }
```

4. Follow Git Course

- <h2>(Friday 22/07/2022)</h2>


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
bmo code 
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bmo App</title>
</head>
<body>
    <p><a name="startingpoint"></a></p> 
    
    <table>
        <form action="">
            <th>Information</th>
                <tr>
                    <td><label for="name"></label>Name</td>
                    <td><input type="checkbox" name="" id=""></td>
                </tr>
                <tr>
                    <td><label for="debitcard"></label>Debit card</td>
                    <td><input type="checkbox" name="" id=""></td>
                </tr>

            <th><a href="#Authentication">Authentication</a></th>
                <tr>
                    <td>
                        <label for="">VoiceID match</label>
                    </td>
                    <td>
                        <input type="checkbox" name="" id="">
                    </td>
                </tr>

                <tr>
                    <td>
                        <label for="">Voice Consent</label>
                    </td>
                    <td>
                        <input type="checkbox" name="" id="">
                    </td>
                </tr>

                <tr>
                    <td>
                        <label for="">OTP</label>
                    </td>
                    <td>
                        <input type="checkbox" name="" id="">
                    </td>
                </tr>
            
                <tr>
                    <td>
                        <label for="">FMA passed</label>
                    </td>
                    <td>
                        <input type="checkbox" name="" id="">
                    </td>
                </tr>
                <tr>
                    <td>
                        <label for="">2nd lvl match</label>
                    </td>
                    <td>
                        <input type="checkbox" name="" id="">
                    </td>
                </tr>
            
            <th><a href="#KYC">KYC</a></th>
                <tr>
                    <td><label for="name"></label>Needed</td>
                    <td><input type="checkbox" name="" id=""></td>
                </tr>
                <tr>
                    <td><label for="name">Given</label></td>
                    <td><input type="checkbox" name="" id=""></td>
                </tr>
                <tr>
                    <td><label for="name">Not needed</label></td>
                    <td><input type="checkbox" name="" id=""></td>
                </tr>

            <th><a href="#Ending">Ending</a></th>
                <tr>
                    <td><label for="name"></label>Needed</td>
                    <td><input type="checkbox" name="" id=""></td>
                </tr>
                <tr>
                    <td><label for="name">Not needed</label></td>
                    <td><input type="checkbox" name="" id=""></td>
                    <td><input type="reset"></td>
                </tr>

        </form>
    </table>

    <hr>

    <h3><a name="Authentication">- Authentication</a></h3>

    <p>
        <b><u>Voice id</u></b> <br>
        <font style="color: blue;">English</font> <br>
        Do you consent to the use of voice id to verify your identity? <br>
        <font style="color: red">Français</font> <br>
        Est-ce que j'ai votre consentement pour utiliser le système Empreint vocale pour vérifier votre identité? 
    </p>
    <button>
        <a href="#startingpoint">Up</a>
    </button>

    <hr>

    <h3><a name="KYC">- KYC</a></h3>

    <p>
        <font style="color: blue;">English</font> <br>
        Do you also have the opportunity to update some information with me, to ensure your profile is up to date<br>
        <font style="color: red">Français</font> <br>
        Avez-vous également la possibilité de mettre à jour certaines informations avec moi, pour assurer que votre profil est à jour?
    </p>
    <button>
        <a href="#startingpoint">Up</a>
    </button>

    <hr>

    <h3><a name="Ending">- Ending</a></h3>

    <p>
        <b><u>On the call</u></b> <br>
        <font style="color: blue;">English</font> <br>
        Would you like me to log this issue so that we have a record of it on your account?<br>
        <font style="color: red;">Français</font> <br>
        Souhaitez-vous que je note officiellement votre demande comme une plainte dans votre dossier afin d'en garder un registre? <br>
    </p>

    <p>
        <b><u>At the end of the call</u></b> <br>
        <font style="color: blue;">English</font> <br>
        Before you go, are you satisfied with the product or service we discussed on the call today?<br>
        <u>No: Is there a complaint that you would like me to log?</u> <br>
        <font style="color: red">Français</font> <br>
        Avant de raccrocher, êtes-vous satisfait avec le produit ou service dont nous avons discuté aujourd'hui? <br>
        <u>Non: Voulez-vous formuler une plainte?</u> <br>
    </p>

    <p>
        <b><u>Complaint documentation</u></b> <br>
        What happened? > when did it happened > how was the cx affected? > What is the cx expecting BMO to do as a resolution?
    </p>

    <button>
        <a href="#startingpoint">Up</a>
    </button>

    <hr>

</body>
</html>

```

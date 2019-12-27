# Test Taker's TI Trove
A collection of programs written for my students owning TI-84+ calculators. Check with me in class or [through email](mailto:ryan.villena@kaplan.com) if your calculator's compatible.

## General
On the SAT and ACT, there are some math problems which require more than a few seconds to solve. It is helpful on the _Calculator Permitted_ sections to outsource the "mechanical" work to a permitted calculator. When programmed correctly, the TI-84+ can save time on problems like [Systems of 2 Variables](https://github.com/RyanVillenaUCR/Test-Takers-TI-Trove/blob/bd715c6a50c9ac2ef77864290646df640d59d3cc/tests.txt#L43) and [Quadratic Roots](https://github.com/RyanVillenaUCR/Test-Takers-TI-Trove/blob/bd715c6a50c9ac2ef77864290646df640d59d3cc/tests.txt#L105), which can be the difference on the final SAT/ACT score.

Each program exists here as a `.8xp` file ([example](https://github.com/RyanVillenaUCR/Test-Takers-TI-Trove/blob/master/8xp/LINSYS3.8xp)) and as a `.txt` file ([example](https://github.com/RyanVillenaUCR/Test-Takers-TI-Trove/blob/master/src/LINSYS3.txt)). Computers/calculators read `.8xp` files, while humans read `.txt` files. You will install the `.8xp` files onto your calculator; I only provide the `.txt` files so you can actually read the code from your computer.

To install onto your calculator, you'll install [TI Connect](https://education.ti.com/en/products/computer-software/ti-connect-sw) onto your computer. You'll use TI Connect and a [USB A-Male to Mini-B cord](https://www.amazon.com/AmazonBasics-USB-2-0-Cable-Male/dp/B00NH11N5A) to copy the `.8xp` files to your calculator. Installation instructions [below](https://github.com/RyanVillenaUCR/Test-Takers-TI-Trove/blob/master/README.md#installation).

### Disclaimer
I should note that the use of these programs is **strictly unfair** to those without programmable calculators. Given the decision, I myself would prohibit the use of programmable calculators on these tests.

This said, my goal is to help my students succeed on their tests, and (un)fortunately, programmable calculators are **allowed** on these tests. I provide these programs in the interest of helping my students succeed on their tests _until such a time that programmed calculators are **explicitly** banned from these tests_.

To that last point, it might be surprising that at the time of this writing, the [SAT calculator policy](https://collegereadiness.collegeboard.org/sat/taking-the-test/calculator-policy) makes no mention of programs existing on calculators. The [ACT calculator policy](http://www.act.org/content/dam/act/unsecured/documents/ACT-calculator-policy.pdf) prevents requires that calculators lack "documents", but these semantics are ambiguous; one might be able to argue that because programs aren't documents, they are allowed on the ACT.

I thus recommend my students be equipped with these programs, but that they **comply with proctors** who request these programs be deleted on Test Day. These programs simply save time with manual calculations; **students who don't understand the material will not find these resources beneficial.**

### Programs

The following programs are currently available:

* **DISTANCE**
  * Finds the distance between two 2D points.
  * Stores the result in register D.
* **INTDIV** _(Integer division)_
  * Computes whole-number quotient and remainder when dividing two numbers.
  * Stores the quotient in register Q.
  * Stores the remainder in register R.
* **IPOW** _(Powers of i)_
  * Simplifies large whole-number powers of imaginary number i, like i^72.
* **LINSYS2** _(Linear Systems 2)_
  * Solves systems of two equations.
  * Will notify if infinite solutions or no solution.
  * Stores the results in registers X and Y.
* **LINSYS3** _(Linear Systems 3)_
  * Solves systems of 3 equations.
  * Will notify if infinite solutions or no solution.
  * Stores the results in registers X, Y, and Z.
* **PTS2LINE** _(Points to Line)_
  * Constructs y = mx + b equation for two points.
  * Stores the slope in register M.
  * Stores the y-intercept in register B.
* **PTSLPFRM** _(Point-Slope Form)_
  * Constructs y = mx + b equation for a slope and a point.
  * Stores the slope in register M.
  * Stores the y-intercept in register B.
* **QUADFORM** _(Quadratic Formula)_
  * Computes the roots of a quadratic equation.
  * Will notify if 0, 1, or 2 solutions.
  * Stores the greatest solution in register X.
* **SLOPE**
  * Computes the slope for two points.
  * Will notify if the slope is undefined.
  * Stores the slope in register M.

## Installation
### Download This Repo
* Click the green ![Clone or Download button](https://user-images.githubusercontent.com/32404733/71463821-846e6500-276c-11ea-873d-ccef3b1fb602.png) button at the top of this page
* Click ![Download ZIP](https://user-images.githubusercontent.com/32404733/71463897-acf65f00-276c-11ea-937f-7df5f158f7ca.png), then save the `.zip` file somewhere onto your computer
* Extract the files from that `.zip` file ([there are many ways to do this](https://lmgtfy.com/?q=extract+zip+file))

### Install TIConnect
* Download [TI Connect](https://education.ti.com/en/products/computer-software/ti-connect-sw) ([Windows version](https://education.ti.com/download/en/ed-tech/B59F6C83468C4574ABFEE93D2BC3F807/A885DD53BEC14496971FE5A42F1014CF/TI-Connect-4.0.0.218.exe)) ([Mac Version](https://education.ti.com/download/en/ed-tech/B59F6C83468C4574ABFEE93D2BC3F807/9BF7E4898EA043FB808873EE5D0267ED/TIConnect-4.1.15.dmg))
* Run the installer

### Transfer to Calculator
* Have a [cable](https://www.amazon.com/AmazonBasics-USB-2-0-Cable-Male/dp/B00NH11N5A) at the ready
* Open ![TI Connect icon](https://user-images.githubusercontent.com/32404733/71508870-1c884f00-283e-11ea-9b30-1b814cb5249b.png), and click ![Send to TI Device button](https://user-images.githubusercontent.com/32404733/71508935-535e6500-283e-11ea-9f27-0058517048ad.png)

* Connect your calculator to the computer using your cable
* Press `Select Device` at the top of this screen:

![Send to TI Device screen](https://user-images.githubusercontent.com/32404733/71508997-89034e00-283e-11ea-9fb4-6301824b6e0d.png)

* You should see the name of your calculator here, so hit `Select`. If you don't, try hitting `Refresh`.

![Select Device](https://user-images.githubusercontent.com/32404733/71509059-d1227080-283e-11ea-928b-c6f1ff72bb59.png)

* The top of your screen should now look something like this:

![Sending to TI-84 Plus Silver Edition](https://user-images.githubusercontent.com/32404733/71509137-1e064700-283f-11ea-9475-e6ece77d66e8.png)

* Find the `.8xp` files in that `.zip` file you extracted earlier.

![.8xp files](https://user-images.githubusercontent.com/32404733/71509298-b4d30380-283f-11ea-86e0-23140d6c3e3e.png)

* Press `Ctrl+A` to highlight all the `.8xp` files. Then, drag-and-drop to the TI Connect screen.

![Ready to export](https://user-images.githubusercontent.com/32404733/71509405-011e4380-2840-11ea-8c15-835267b9f4aa.png)

* Press `Send to Device` at the bottom of the screen. It'll take a minute to transfer.
* If all went well, check your TI to see that the programs went through. Press the `PRGM` button in the center of your TI:

![TI with programs](https://user-images.githubusercontent.com/32404733/71509634-de405f00-2840-11ea-9486-56ed80cd504e.png)

* You should see all the programs listed. Enjoy!

## Editing Programs

All programs are coded in the TI-Basic programming language. It is a scripting language, which means the calculator reads programs raw, line-by-line (as opposed to compiled languages like Java). In other words, if your program has a syntax error, it won't be caught until the calculator tries to execute that line of code. Please be careful and test your code frequently!

I strongly recommend that beginners learn to program on their calculators **before** moving on to desktop. On a physical calculator, it's easy to quickly test and fix your code when you're just starting out. Desktop programming should be reserved for more complicated programs.

### On the TI
Hit the `PRGM` button at the center of your calculator. You'll see all of the programs your calculator has. (This may be empty if you haven't yet installed any programs.)

![empty_prgm_menu](https://user-images.githubusercontent.com/32404733/71510456-dd5cfc80-2843-11ea-978a-f280d493c7d1.png)

We're in the `EXEC` submenu. We don't have any programs to execute yet, so let's make one. Use the right arrow key to highlight `NEW` instead. Our only option here is to `Create New`, so let's do just that by pressing `ENTER`.

![create new](https://user-images.githubusercontent.com/32404733/71510594-388eef00-2844-11ea-8fbc-ac7c882e527b.png)

We must define a name for our programs. Only uppercase letters and numbers are allowed, but the first character must be a letter. Also, only 8 characters are allowed. Let's title ours `FRSTPRGM` (first program) by using the green letters on our calculator, then hitting `ENTER`:

![empty FRSTPRGM](https://user-images.githubusercontent.com/32404733/71510774-dd113100-2844-11ea-93ef-d67bdfde7e2e.png)

On our calculator, each line of code starts with a `:` character. Let's make a program to display the number 69, and we'll do that 69 times. At the end, we'll display a message for our user. Sounds fun!

We'll first store the number 69 into register `X` so we can easily reference it. Store 69 into `X`, then insert a new line with `ENTER`:

![store 69 into X](https://user-images.githubusercontent.com/32404733/71511028-c0292d80-2845-11ea-9e09-b506a88e65d8.png)

(Use the STO button at the bottom-left of your calculator to type the arrow.)

We'll use the `Disp` command to display this number 69 times. You could manually type this 69 times, but there's a better way: TI-Basic supports [_for loops_](http://tibasicdev.wikidot.com/for). Let's follow the directions on that page, and type this line into our calculator:

![For(Y,1,69](https://user-images.githubusercontent.com/32404733/71511306-b8b65400-2846-11ea-9825-bfd15e11982b.png)

(To type the `For(` command, use `PRGM` → `For(` under the `CTL` submenu. `CTL` here stands for "flow of control", the keywords that dictate how your program runs. Use `ALPHA` → `1` to type `Y`, and there's a `,` button above the `7` button.)

Inside our _for_ loop, let's just do one thing: diplay the number 69. We stored it in `X` earlier, so let's just display `X`:

![Disp X](https://user-images.githubusercontent.com/32404733/71511417-26628000-2847-11ea-8f69-1183335fe197.png)

We now need to tell the calculator that we've finished writing the body of our _for_ loop. To do this, use the `End` keyword:

![End](https://user-images.githubusercontent.com/32404733/71511490-6de90c00-2847-11ea-9563-9609083b4adc.png)

(The `End` keyword is in `PRGM` → `End` under the `CTL` submenu.)

Alright, we've typed a program that displays 69, 69 times. Let's finish this off by printing "Nice" to the user, because of course we're going to do that. Display the string "NICE", making sure not to forget the left quotation mark:

![Disp "NICE](https://user-images.githubusercontent.com/32404733/71511777-5f4f2480-2848-11ea-8d5f-6756a5d6a3c9.png)

(Use `ALPHA` → `+` to type a quotation mark. In TI-Basic, you don't always need to use quotation marks on _both_ ends of a string; a quotation mark on the left is usually sufficient. This is considered good practice because it saves space on your TI.)

Awesome! Our program is finished. Let's exit out using `QUIT` (type in `2ND` → `MODE`), so we're on our main screen. Once there, let's now run our program using `PRGM` → `FRSTPRGM` → `ENTER` → `ENTER`:

![prgmNICE](https://user-images.githubusercontent.com/32404733/71511955-0fbd2880-2849-11ea-8d0b-07cfe15333ef.gif)

Wonderful. We've written our first program... but honestly, I can understand if you want to delete this. No worries, just do `MEM` by hitting `2ND` → `+`, then `Mem Mgmt/Del…` → `Prgm…` → `FRSTPRGM` → `DEL` → `Yes`:

![delete prgmFRSTPRGM](https://user-images.githubusercontent.com/32404733/71512165-dafda100-2849-11ea-869b-74b8372c9e08.gif)

Nicely done. Try writing your own programs on your TI now! If you need inspiration, you can always try looking at some [working examples](https://github.com/RyanVillenaUCR/Test-Takers-TI-Trove/tree/master/src). (Note that the // lines shouldn't be typed into your calculator.)

For me, `prgmSLOPE` was one of my first programs. I recommend you try writing your own version! [Mine](https://github.com/RyanVillenaUCR/Test-Takers-TI-Trove/blob/b5fb17f1bcf037788b5cc86b61ef4b15f49f0532/src/SLOPE.txt#L1) is always here for you to consult.

### On Windows

TODO - I'll finish this section later. For now, just use [TokenIDE](https://www.ticalc.org/archives/files/fileinfo/433/43315.html) to write programs on a Windows machine. You can emulate a TI on Windows or Android using [Wabbitemu](http://wabbitemu.org/). Save your program using `Ctrl+S`, build your program in TokenIDE using `F5`, then drag-and-drop the `.8xp` file to the Wabbitemu screen to export your program to the emulator.

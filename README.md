# MP1: Control flow

This MP consists of two parts involving numbers, strings, operators, and loops.
Forms of both problems are commonly used as "screening" questions in technical intervals.

## Gettysburg Address

The [Bliss autograph](https://en.wikipedia.org/wiki/Gettysburg_Address#Bliss_copy) of the Gettysburg Address is generally considered to be the most authoritative copy of Lincoln's famous speech.
It reads:

    Four score and seven years ago our fathers brought forth on this
    continent, a new nation, conceived in liberty, and dedicated to the
    proposition that all men are created equal. Now we are engaged in a
    great civil war, testing whether that nation, or any nation so conceived
    and so dedicated can long endure. We are met on a great battle-field of
    that war. We have come to dedicate a portion of that field, as a final
    resting place for those who here gave their lives that that nation might
    live. It is altogether fitting and proper that we should do this. But,
    in a larger sense, we can not dedicate---we can not consecrate---we can
    not hallow---this ground. The brave men, living and dead, who struggled
    here, have consecrated it, far above our poor power to add or detract.
    The world will little note, nor long remember what we say here, but it
    can never forget what they did here. It is for us the living, rather, to
    be dedicated here to the unfinished work which they who fought here have
    thus far so nobly advanced. It is rather for us to be here dedicated to
    the great task remaining before us---that from these honored dead we
    take increased devotion to that cause for which they gave the last full
    measure of devotion---that we here highly resolve that these dead shall
    not have died in vain---that this nation, under God, shall have a new
    birth of freedom---and that government of the people, by the people, for
    the people, shall not perish from the earth.

Your assignment is to count the vowels in the Gettsyburg Address.

### What to do

Write a snippet of Python code which counts all the vowels (defining these to be _a_, _e_, _i_, _o_, and _u_) in the above copy of the address, and then print out this count.

### Test support

There are 449 vowels in the Bliss autograph.

### Hints

* Use a `"""` string literal to assign the text of the address to a variable
* Use a `for`-loop to iterate over the characters in that variable
* Before starting the loop, create a counter integer variable

### Stretch goal

Research "case-folding" in Python.
Then, case-fold the address before performing the computation, so that you don't have to handle both uppercase and lowercase vowels separately.
Confirm that this does not change your result.

### What to turn in

* A code snippet that, when executed, counts the vowels and prints out the result (I should be able to copy and paste this into Python and obtain the answer)
* A brief (paragraph or so) description of your approach and any challenges you ran into

## FizzBuzz

FizzBuzz is a children's game. The first player says the number "1", the second player says the number "2", and so on. However:

* If the number is a multiple of 3, the player says "fizz" instead of the number
* If the number is a multiple of 5, the player says "buzz" instead of the number
* If the number is a multiple of both 3 and 5, the player says "fizzbuzz" instead of the number

### What to do

Write a series of Python expressions which prints out the FizzBuzz output from 1 to 100 (inclusive) using `print` and a `for`-loop.

### Test support

The first few lines of output should read:

	1
	2
	fizz
	4
	buzz
	fizz
	7
	8
	fizz
	buzz
	11
	fizz
	13
	14
	fizzbuzz
	16
	17
	fizz
	19
	buzz

## What to turn in

* A code snippet that, plays FizzBuzz for numbers 1-100 (inclusive) as described above
* A brief (paragraph or so) description of your approach and any challenges you ran into

### Hints

* Go back and read the description of the game one more time. Do not start coding until you understand it
* Use the modulus operator `%` for determining whether a number is divisible by 3 or 5
* Use `range` in the loop

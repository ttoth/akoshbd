# akoshbd
Ákos, here lies an indispensable message for you, but someone -feeling very funny- run it through ... a cipher, several times!
Your task is to quickly implement a decoder function, so you'd be able to read the original text.

## How It Works

Don't worry, we have intel on how this malicious man encoded the message. Let's see what piece of information we acquired!

> ### Algorithm
> Encoding and decoding are done by performing a series of character and substring rotations on a string input.
>
> Encoding: The number of rotations is determined by the value of n. The sequence of rotations is applied in the following order:
>  - Step 1: remove all spaces in the string (but remember their positions)
>  - Step 2: shift the order of characters in the new string to the right by n characters
>  - Step 3: put the spaces back in their original positions
>  - Step 4: shift the characters of each substring (separated by one or more consecutive spaces) to the right by n
>
> Repeat this process until it has been completed n times in total.
>
> The value n is then prepended to the resulting string with a space.
>
> **Decoding: Decoding simply reverses the encoding process.**
>
> ### Input
>
> The encode method will receive two arguments — a positive integer n and a string value.
>
> The decode method will receive one argument — a string value.
>
> ### Output
>
>Each method will return a string value.

See? Easy! You just have to write the decoder! To aid your effort there is a file containing some snippets and a file providing some basic test samples...if you really want to go hardcore on this one!

## The message
Oh, yeah, the message is:

``10 aspjki-zuááa l oomszlógzáá orKlpaotnnkT``



Good luck!

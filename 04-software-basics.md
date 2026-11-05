# Software Basics

**Module:** Operating Systems basics
**Completed:** Nov 2026

## Room: [Data Representation](https://tryhackme.com/room/datarepresentation)
Computers speak different languages: binary, hex, and 8 bits becomes color. This room teaches me how to convert between the three. Once I get the hang of it, a packet capture or a file header stops looking like noise and starts looking like a sentence.

## Room: [Data Encoding](https://tryhackme.com/room/dataencoding)
I learn how characters become numbers: ASCII, Unicode, and the different ways a computer maps "A" to a value. Also why our logs sometimes look like garbage and how bad guys use encoding mismatches to slip past filters.

## What Tripped Me Up
I got tripped up learning binary because TryHackMe made it sound more complicated than it is. All you do is look at which lights are on and add up their place values. 4 bits = 8, 4, 2, 1. If nothing's on, the answer is 0. The place values double going left because binary only has two digits. That's the whole thing. Why the heck did they make it so complicated.

## What I Learned
1. I learned that 8 bits is a byte and a tiny cute nibble is 4 bits.
2. Binary is just "which lights are on" and then you add up their values. That's the whole thing.
3. Hex is just binary with a shorter label. One hex digit = 4 bits. 1111 is too long to write every time, so we call it F.
4. I learned why people dislike hexadecimal... so much memorization. But I know the more I do this, it'll become automatic. Like how I don't "calculate" what the letter T looks like when I read a word. I just see it.
5. ASCII is just numbers → characters. 65 = A. That's the whole thing.
6. Encoding mismatches matter because attackers hide stuff in hex so a filter looking for "SELECT" just sees numbers and lets it through.

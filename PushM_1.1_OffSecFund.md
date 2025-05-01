# Offensive Security Fundamentals
## Cyber Security
### TL;DR
```txt
1. Read Push Method learning
2. Got a bit lost
3. Found some free and beginner-friendly CySec books
4. Attempted the CTF
5. Challenge Successful
```
## Table of Content
* [Introduction](/#Introduction)
* [Flags](/#Flags)

### Introduction
I followed the step-by-step instruction written by dibimbing.id. The goal was to get a hands-on offensive security practice/exercise. At first, I didn't know what to do in the practice/challenge/426 of picoCTF website. I mean, I know there is a webshell feature in picoCTF so that I can just use the linux-based environment in the browser, and I didn't need to install a VM. Moreover, luckily, the Unminify challenge does not really require webshell at all, I just clicked on the hyperlink provided in the instruction section of the challenge and then I could see the website. 

Before I actually working on the "Push Method" (a learning method implemented by dibimbing.id for this CySec bootcamp), I stumnbled upon some resources along the way, especially from the picoCTF website. I was intrigued by the way to solve this CTF stuff as I haven't get my hands on this kind of activity/exercise ever. Therefore, I looked at some document on Web Exploitation (~/learning_guides/Book-3-Web-Exploitation). Alas, the document explains in a very technical language that even I couldn't keep up. I was kind of stressed by the overload of specialized, subject-specific jargons the document told so I looked up for the external sources picoCTF offered. I ended up discovering some books about Cyber Security, some of which are easy to follow and beginner-friendly such as:
* [Gitbook from Trail of Bits](https://trailofbits.github.io/ctf/index.html) and
* [The CTF Primer](primer.picoctf.org)

I read the instruction while also looking at the website. I then navigate myself to the "hints" section to find some clues. Then I followed the hints and got myself the view-source view (kind of awkward writing "view" a couple of times). Once I got to see the source view, it was quite exhausting to scan the whole HTML code written horizontally. It was a pain in the eyes! Despite my eyes screaming when scanning the code, I kept looking for the flag.

A couple of minutes passed by and my eyes was tired. And then guess what, I saw an option to "Line wrap" in the left-top-corner of the view-source page. I was like, "What the shell?! I spent minutes of my time just to suffer from reading this diabolical HTML file of a website?!" (a reference to https://primer.picoctf.org/#_what_the_shell). I saved my eyes from getting murdered by the agony-inducing HTML that website has. Then, I looked for the flag. There are some HTML classes that specifies flags but they seemed not like one because they only have "picoctf()". What I was looking for was something that has the word "picoCTF" and "{" with some nonsense words and then closed with "}". Not long after carefully investigating the code line by line, I finally found the flag. It was just near the end of the code.


### Flags Captured
* Unminify (30/04/2025)
```txt
picoCTF{pr3tty_c0d3_d9c45a0b}
```
* Obedient Cat (30/04/2025)
```txt
  picoCTF{s4n1ty_v3r1f13d_4a2b35fd}
```
* Super SSH (30/04/2025)
```txt
picoCTF{s3cur3_c0nn3ct10n_65a7a106}
```
* what's a net cat? (30/04/2025)
```txt
picoCTF{nEtCat_Mast3ry_3214be47}
```
* Mod 26 (30/04/2025)
```txt
picoCTF{next_time_I'll_try_2_rounds_of_rot13_ZNMldSDw}
```
* Warmed Up (30/04/2025)
```txt
picoCTF{61}
```
* 2Warm (30/04/2025)
```txt
picoCTF{101010}
```
* Bases (30/04/2025)
```txt
picoCTF{l3arn_th3_r0p35}
```
* Wave a flag (01/05/2025)
```txt
picoCTF{b1scu1ts_4nd_gr4vy_d6969390}
```
* Table, Table, Attck (01/05/2025)
```txt
picoCTF{l3v3l_up!_t4k3_4_r35t!_f3553887}
```
* Insp3ct0r (01/05/2025)
```
picoCTF{tru3_d3t3ct1ve_0r_ju5t_lucky?f10be399}
```
* strings it (01/05/2025)
```txt
picoCTF{5tRIng5_1T_7f766a23}
```
* First Grep (01/05/2025)
```txt
picoCTF{grep_is_good_to_find_things_f77e0797}
```

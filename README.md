# PicoCTFLevels
Level description and solution for Pico CTF


## General Skills

### Level 1
Obedient Cat - 5 points

Download a file and read it in a text editor. Flag is in clear text.

> picoCTF{s4n1ty_v3r1f13d_2aa22101}

### Level 2
Python Wrangling - 10 points

Download 3 files:
- python script
- password
- flag

Run script in terminal:
> python ende.py -d flag.txt.en
  
Provide password:
> 67c6cc9667c6cc9667c6cc9667c6cc96

> picoCTF{4p0110_1n_7h3_h0us3_67c6cc96}

### Level 3
Wave a flag - 10 points

Download a file **warm**.
Change permissions to executable:
> sudo chmod 777 warm
Then run:
> ./warm -h
 
> picoCTF{b1scu1ts_4nd_gr4vy_30e77291}

### Level 4
Nice netcat... - 15 points

> nc mercury.picoctf.net 35652

It will return ascii list of numbers. Decode it.

> picoCTF{g00d_k1tty!_n1c3_k1tty!_9b3b7392}

### Level 5
Static ain't always noise - 20 points

Download two files, one of them is compiled.
Flag can be found by using *less* and reading it, or by using:
> bash ltdis.sh static
It will create decompiled files. Read them.

> picoCTF{d15a5m_t34s3r_f6c48608}

### Level 6
Tab, Tab, Attack - 20 points
Download, unzip, disassemble, read texts.

> picoCTF{l3v3l_up!_t4k3_4_r35t!_76266e38}

### Level 7
Magikarp Ground Mission - 30 points

SSH to an endpoint.
> ssh ctf-player@venus.picoctf.net -p 53520
> pass: b60940ca
Then find 3 files with parts of the flag.

> picoCTF{xxsh_0ut_0f_\/\/4t3r_c1754242}

### Level 8
Lets Warm Up - 50 points

Translate hexadecimal to ascii

> picoCTF{p}

### Level 9
Warmed Up - 50 points

Convert hex to dec.

> picoCTF{61}

### Level 10
2Warm - 50 points

Convert dec to bin

> picoCTF{101010}

### Level 11
what's a net cat? - 100 points

> nc jupiter.challenges.picoctf.org 64287

> picoCTF{nEtCat_Mast3ry_284be8f7}

### Level 12
strings it - 100 points

File can be decompiled and flag found in the strings.
Right way is to use 'strings' function.
> strings -n 7 static | grep pico

>picoCTF{5tRIng5_1T_827aee91}

### Level 13
Bases - 100 points

String encoded in base 64.

> picoCTF{l3arn_th3_r0p35}

### Level 14
First Grep - 100 points

> grep pico file

> picoCTF{grep_is_good_to_find_things_dba08a45}

### Level 15
Based - 200 points

First netcat:
> nc jupiter.challenges.picoctf.org 29221
Then decode words.
computer, street, lizard

> picoCTF{learning_about_converting_values_00a975ff}

### Level 16
plumbing - 200 points

> nc jupiter.challenges.picoctf.org 7480 | grep pico

> picoCTF{digital_plumb3r_06e9d954}

### Level 17
mus1c - 300 points

Decode song. No idea how.

### Level 18
flag_shop - 300 points

Use integer overflow to increase money in account, then buy flag.

> picoCTF{m0n3y_bag5_9c5fac9b}
> 
### Level 19
mus1c - 300 points

Decode song. No idea how.

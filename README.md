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
### Level 7
### Level 8
### Level 9
### Level 10

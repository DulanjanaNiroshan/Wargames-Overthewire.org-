# wargames_IT13082116

## Level0

######[DulanjanaNiroshan.Dulanjana-PC] ➤ ssh bandit0@bandit.labs.overthewire.org
######bandit0@bandit.labs.overthewire.org's password: bandit0

######bandit0@melinda:~$ ls
######readme
######bandit0@melinda:~$ cat readme
######boJ9jbbUNNfktd78OOpsqOltutMc3MY1
######bandit0@melinda:~$ logout

## level0->level1

############[DulanjanaNiroshan.Dulanjana-PC] ➤ ssh bandit1@bandit.labs.overthewire.org
######bandit1@bandit.labs.overthewire.org's password: boJ9jbbUNNfktd78OOpsqOltutMc3MY1

######bandit1@melinda:~$ ls
-
bandit1@melinda:~$ cat ./-
CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9
bandit1@melinda:~$
bandit1@melinda:~$ logout

## level1->level2

[DulanjanaNiroshan.Dulanjana-PC] ➤ ssh bandit2@bandit.labs.overthewire.org
bandit2@bandit.labs.overthewire.org's password: CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9

bandit2@melinda:~$ ls
spaces in this filename
bandit2@melinda:~$ cat "spaces in this filename"
UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK
bandit2@melinda:~$ logout

## level2->level3

[DulanjanaNiroshan.Dulanjana-PC] ➤ ssh bandit3@bandit.labs.overthewire.org
bandit3@bandit.labs.overthewire.org's password: UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK

bandit3@melinda:~$ ls
inhere
bandit3@melinda:~$ cd inhere
bandit3@melinda:~/inhere$ ls -la
total 12
drwxr-xr-x 2 root    root    4096 Nov 14  2014 .
drwxr-xr-x 3 root    root    4096 Nov 14  2014 ..
-rw-r----- 1 bandit4 bandit3   33 Nov 14  2014 .hidden
bandit3@melinda:~/inhere$ cat .hidden
pIwrPrtPN36QITSp3EQaw936yaFoFgAB
bandit3@melinda:~/inhere$ logout

## level4->level5

[DulanjanaNiroshan.Dulanjana-PC] ➤ ssh bandit4@bandit.labs.overthewire.org
bandit4@bandit.labs.overthewire.org's password: pIwrPrtPN36QITSp3EQaw936yaFoFgAB

bandit4@melinda:~$ ls
inhere
bandit4@melinda:~$ cd inhere
bandit4@melinda:~/inhere$ ls -la
total 48
-rw-r----- 1 bandit5 bandit4   33 Nov 14  2014 -file00
-rw-r----- 1 bandit5 bandit4   33 Nov 14  2014 -file01
-rw-r----- 1 bandit5 bandit4   33 Nov 14  2014 -file02
-rw-r----- 1 bandit5 bandit4   33 Nov 14  2014 -file03
-rw-r----- 1 bandit5 bandit4   33 Nov 14  2014 -file04
-rw-r----- 1 bandit5 bandit4   33 Nov 14  2014 -file05
-rw-r----- 1 bandit5 bandit4   33 Nov 14  2014 -file06
-rw-r----- 1 bandit5 bandit4   33 Nov 14  2014 -file07
-rw-r----- 1 bandit5 bandit4   33 Nov 14  2014 -file08
-rw-r----- 1 bandit5 bandit4   33 Nov 14  2014 -file09
drwxr-xr-x 2 root    root    4096 Nov 14  2014 .
drwxr-xr-x 3 root    root    4096 Nov 14  2014 ..
bandit4@melinda:~/inhere$ file ./-*
./-file00: data
./-file01: data
./-file02: data
./-file03: data
./-file04: data
./-file05: data
./-file06: data
./-file07: ASCII text
./-file08: data
./-file09: data
bandit4@melinda:~/inhere$ cat ./-file07
koReBOKuIDDepwhWk7jZC0RTdopnAYKh
bandit4@melinda:~/inhere$ logout

## level5->level6

[DulanjanaNiroshan.Dulanjana-PC] ➤ ssh bandit5@bandit.labs.overthewire.org 
bandit5@bandit.labs.overthewire.org's password: koReBOKuIDDepwhWk7jZC0RTdopnAYKh

bandit5@melinda:~$ ls
inhere
bandit5@melinda:~$ cd inhere
bandit5@melinda:~/inhere$ ls -la
total 88
drwxr-x--- 22 root bandit5 4096 Nov 14  2014 .
drwxr-xr-x  3 root root    4096 Nov 14  2014 ..
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere00
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere01
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere02
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere03
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere04
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere05
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere06
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere07
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere08
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere09
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere10
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere11
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere12
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere13
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere14
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere15
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere16
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere17
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere18
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere19
bandit5@melinda:~/inhere$ find ./ -size 1033c
./maybehere07/.file2
bandit5@melinda:~/inhere$ cat ./maybehere07/.file2
DXjZPULLxYr17uwoI01bNLQbtFemEgo7
bandit5@melinda:~/inhere$ logout

## level6->level7

[DulanjanaNiroshan.Dulanjana-PC] ➤ ssh bandit6@bandit.labs.overthewire.org 
bandit6@bandit.labs.overthewire.org's password: DXjZPULLxYr17uwoI01bNLQbtFemEgo7

bandit6@melinda:~$ find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
/var/lib/dpkg/info/bandit7.password
bandit6@melinda:~$ cat /var/lib/dpkg/info/bandit7.password
HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs
bandit6@melinda:~$ logout

## level7->level8

[DulanjanaNiroshan.Dulanjana-PC] ➤ ssh bandit7@bandit.labs.overthewire.org 
bandit7@bandit.labs.overthewire.org's password: HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs

bandit7@melinda:~$ ls -lh
total 4.0M
-rw-r----- 1 bandit8 bandit7 4.0M Nov 14  2014 data.txt
bandit7@melinda:~$ cat data.txt | grep millionth
millionth       cvX2JJa4CFALtqS87jk27qwqGhBM9plV
bandit7@melinda:~$ logout

## level8->level9

[DulanjanaNiroshan.Dulanjana-PC] ➤ ssh bandit8@bandit.labs.overthewire.org 
bandit8@bandit.labs.overthewire.org's password: cvX2JJa4CFALtqS87jk27qwqGhBM9plV

bandit8@melinda:~$ ls
data.txt
bandit8@melinda:~$ cat data.txt |sort |uniq -u
UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR
bandit8@melinda:~$ logout

## level9->level10

[DulanjanaNiroshan.Dulanjana-PC] ➤ ssh bandit8@bandit.labs.overthewire.org 
bandit9@bandit.labs.overthewire.org's password: UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR

bandit9@melinda:~$ ls
data.txt
bandit9@melinda:~$ strings data.txt | grep "=="
I========== the6
========== password
========== ism
========== truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk
bandit9@melinda:~$ logout

## level10->level11

[DulanjanaNiroshan.Dulanjana-PC] ➤ ssh bandit10@bandit.labs.overthewire.org 
bandit10@bandit.labs.overthewire.org's password: truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk  

bandit10@melinda:~$ ls
data.txt
bandit10@melinda:~$ cat data.txt
VGhlIHBhc3N3b3JkIGlzIElGdWt3S0dzRlc4TU9xM0lSRnFyeEUxaHhUTkViVVBSCg==
bandit10@melinda:~$ base64 -d data.txt
The password is IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR
bandit9@melinda:~$ logout

## level11->level12

[DulanjanaNiroshan.Dulanjana-PC] ➤ ssh bandit11@bandit.labs.overthewire.org 
bandit11@bandit.labs.overthewire.org's password: IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR

bandit11@melinda:~$ ls
data.txt
bandit11@melinda:~$ cat data.txt
Gur cnffjbeq vf 5Gr8L4qetPEsPk8htqjhRK8XSP6x2RHh
bandit11@melinda:~$ cat data.txt| tr 'A-Za-z' 'N-ZA-Mn-za-m'
The password is 5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu
bandit11@melinda:~$ logout

## level12->level13

[DulanjanaNiroshan.Dulanjana-PC] ➤ ssh bandit12@bandit.labs.overthewire.org 
bandit12@bandit.labs.overthewire.org's password: 5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu

bandit12@melinda:~$ ls
data.txt
bandit12@melinda:~$ mkdir /tmp/dulanjana123
bandit12@melinda:~$ cp ./data.txt /tmp/dulanjana123
bandit12@melinda:~$ cd /tmp/dulanjana123
bandit12@melinda:/tmp/dulanjana123$ file data.txt
data.txt: ASCII text
bandit12@melinda:/tmp/dulanjana123$ xxd -r data.txt data2
bandit12@melinda:/tmp/dulanjana123$ file data2
data2: gzip compressed data, was "data2.bin", from Unix, last modified: Fri Nov 14 10:32:20 2014, max compression

bandit12@melinda:/tmp/dulanjana123$ zcat -d data2 > data3
bandit12@melinda:/tmp/dulanjana123$ file data3
data3: bzip2 compressed data, block size = 900k
bandit12@melinda:/tmp/dulanjana123$ bzip2 -d data3
bzip2: Can't guess original name for data3 -- using data3.out
bandit12@melinda:/tmp/dulanjana123$ file data3.out
data3.out: gzip compressed data, was "data4.bin", from Unix, last modified: Fri Nov 14 10:32:20 2014, max compression

bandit12@melinda:/tmp/dulanjana123$ zcat -d data3.out > data4
bandit12@melinda:/tmp/dulanjana123$ file data4
data4: POSIX tar archive (GNU)

bandit12@melinda:/tmp/dulanjana123$ tar xvf data4
data5.bin
bandit12@melinda:/tmp/dulanjana123$ file data5.bin
data5.bin: POSIX tar archive (GNU)
bandit12@melinda:/tmp/dulanjana123$ tar -xvf data5.bin
data6.bin
bandit12@melinda:/tmp/dulanjana123$ file data6.bin
data6.bin: bzip2 compressed data, block size = 900k
bandit12@melinda:/tmp/dulanjana123$ bzip2 -d data6.bin
bzip2: Can't guess original name for data6.bin -- using data6.bin.out
bandit12@melinda:/tmp/dulanjana123$ file data6.bin.out
data6.bin.out: POSIX tar archive (GNU)
bandit12@melinda:/tmp/dulanjana123$ tar -xvf data6.bin.out
data8.bin
bandit12@melinda:/tmp/dulanjana123$ file data8.bin
data8.bin: gzip compressed data, was "data9.bin", from Unix, last modified: Fri Nov 14 10:32:20 2014, max compression
bandit12@melinda:/tmp/dulanjana123$ zcat -d data8.bin > data9.bin
bandit12@melinda:/tmp/dulanjana123$ file data9.bin
data9.bin: ASCII text
bandit12@melinda:/tmp/dulanjana123$ cat data9.bin
The password is 8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL
bandit12@melinda:/tmp/dulanjana123$ logout

## level13->level14

[DulanjanaNiroshan.Dulanjana-PC] ➤ ssh bandit13@bandit.labs.overthewire.org
bandit13@bandit.labs.overthewire.org's password: 8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL

bandit13@melinda:~$ ls
sshkey.private
bandit13@melinda:~$ ssh -i sshkey.private bandit14@localhost
Could not create directory '/home/bandit13/.ssh'.
The authenticity of host 'localhost (127.0.0.1)' can't be established.
ECDSA key fingerprint is 05:3a:1c:25:35:0a:ed:2f:cd:87:1c:f6:fe:69:e4:f6.
Are you sure you want to continue connecting (yes/no)? yes
bandit14@melinda:~$ cat /etc/bandit_pass/bandit14
4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e



## level14->level15

bandit14@melinda:~$ nc -vvn 127.0.0.1 30000
Connection to 127.0.0.1 30000 port [tcp/*] succeeded!
4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e
Correct!
BfMYroe26WYalil77FoDi9qh59eK5xNr

## level15->level16

bandit14@melinda:~$ openssl s_client -connect 127.0.0.1:30001
CONNECTED(00000003)
depth=0 CN = li190-250.members.linode.com
verify error:num=18:self signed certificate
verify return:1
depth=0 CN = li190-250.members.linode.com
verify return:1
---
Certificate chain
 0 s:/CN=li190-250.members.linode.com
   i:/CN=li190-250.members.linode.com
---
Server certificate
-----BEGIN CERTIFICATE-----
MIIC3jCCAcagAwIBAgIJAI5QiWZw4YHbMA0GCSqGSIb3DQEBCwUAMCcxJTAjBgNV
BAMTHGxpMTkwLTI1MC5tZW1iZXJzLmxpbm9kZS5jb20wHhcNMTQxMTE0MTAyODA0
WhcNMjQxMTExMTAyODA0WjAnMSUwIwYDVQQDExxsaTE5MC0yNTAubWVtYmVycy5s
aW5vZGUuY29tMIIBIjANBgkqhkiG9w0BAQEFAAOCAQ8AMIIBCgKCAQEAsKmy9o5z
WU+1EH7Z3bB5TGQA+16zXDcEJy6tZWZ8CDrRyQXiahendp45BWUc/ZuLDo0+B3Wt
ZXjofmLw/F4fmR+8X1s1fQZX2dFt920qEm7LxqzWd0c7FdHiBwwRrwhkk+3cQpOB
TTGdLWEgpdmwwNZDTUdsDLzjDczPnju6T6p6ArTECztPbmTjfY4QIRtC6capL1Z+
yPJSQVAuAMEX1wTDWTGdm0VV7oW4F5cGZutf6QAP51jdhSyZuGilIPHbnj0l6Qc7
a7+OtEsEGi31aJ8KpRf7LNZ7DXCuoB3Hf75Pd6VjDgoOIagcH0NYqa75gEjBkGzs
ktLWykT7ag7fKwIDAQABow0wCzAJBgNVHRMEAjAAMA0GCSqGSIb3DQEBCwUAA4IB
AQCaZdUNAj8WDEKWdoU3LNXUBJlTJwiWBrh550PbHSQORcCz2K0kiMei1A4ojK2N
dMHFGAqAeUEaxtz92p2BoFpZasAtdSa3u63tBckFhfUolIS1TC7Cj51y19ysTeep
fGPFpuPCVqVPsruei8Z/iqn3bFIhQQdmumeePZQdPMwZSWHNVYC5XODd7PvNDrDu
5MZJjkz4+6LbwwAvyew62meFN2QEsYbK2Brtbhze+IjE27FGWlSw4K3jlwa409MD
MTf4JU41ELaYY8G/LSNDJsBVhhkHzvXR9iCbXxNz3IL0dQDNj7h4LKhBy0q7hvqg
kDzwlmBO4WKSmCAuky44cXmd
-----END CERTIFICATE-----
subject=/CN=li190-250.members.linode.com
issuer=/CN=li190-250.members.linode.com
---
No client certificate CA names sent
---
SSL handshake has read 1714 bytes and written 637 bytes
---
New, TLSv1/SSLv3, Cipher is DHE-RSA-AES256-SHA
Server public key is 2048 bit
Secure Renegotiation IS supported
Compression: NONE
Expansion: NONE
SSL-Session:
    Protocol  : SSLv3
    Cipher    : DHE-RSA-AES256-SHA
    Session-ID: 8FCB87B54526E7989979B92EBDC5D8693C9324CB74B4BEBFDD114D2949CFC1BB
    Session-ID-ctx:
    Master-Key: 05EC46D30893A4E72459A321B9E5994CB5B325D6F4530DD0CF9AE01EAF95BE021CF5E65ACA272802E7DE072FFF8C3BC8
    Key-Arg   : None
    PSK identity: None
    PSK identity hint: None
    SRP username: None
    Start Time: 1439995804
    Timeout   : 300 (sec)
    Verify return code: 18 (self signed certificate)
---

Wrong! Please enter the correct current password
read:errno=0
bandit14@melinda:~$ openssl s_client -connect 127.0.0.1:30001
CONNECTED(00000003)
depth=0 CN = li190-250.members.linode.com
verify error:num=18:self signed certificate
verify return:1
depth=0 CN = li190-250.members.linode.com
verify return:1
---
Certificate chain
 0 s:/CN=li190-250.members.linode.com
   i:/CN=li190-250.members.linode.com
---
Server certificate
-----BEGIN CERTIFICATE-----
MIIC3jCCAcagAwIBAgIJAI5QiWZw4YHbMA0GCSqGSIb3DQEBCwUAMCcxJTAjBgNV
BAMTHGxpMTkwLTI1MC5tZW1iZXJzLmxpbm9kZS5jb20wHhcNMTQxMTE0MTAyODA0
WhcNMjQxMTExMTAyODA0WjAnMSUwIwYDVQQDExxsaTE5MC0yNTAubWVtYmVycy5s
aW5vZGUuY29tMIIBIjANBgkqhkiG9w0BAQEFAAOCAQ8AMIIBCgKCAQEAsKmy9o5z
WU+1EH7Z3bB5TGQA+16zXDcEJy6tZWZ8CDrRyQXiahendp45BWUc/ZuLDo0+B3Wt
ZXjofmLw/F4fmR+8X1s1fQZX2dFt920qEm7LxqzWd0c7FdHiBwwRrwhkk+3cQpOB
TTGdLWEgpdmwwNZDTUdsDLzjDczPnju6T6p6ArTECztPbmTjfY4QIRtC6capL1Z+
yPJSQVAuAMEX1wTDWTGdm0VV7oW4F5cGZutf6QAP51jdhSyZuGilIPHbnj0l6Qc7
a7+OtEsEGi31aJ8KpRf7LNZ7DXCuoB3Hf75Pd6VjDgoOIagcH0NYqa75gEjBkGzs
ktLWykT7ag7fKwIDAQABow0wCzAJBgNVHRMEAjAAMA0GCSqGSIb3DQEBCwUAA4IB
AQCaZdUNAj8WDEKWdoU3LNXUBJlTJwiWBrh550PbHSQORcCz2K0kiMei1A4ojK2N
dMHFGAqAeUEaxtz92p2BoFpZasAtdSa3u63tBckFhfUolIS1TC7Cj51y19ysTeep
fGPFpuPCVqVPsruei8Z/iqn3bFIhQQdmumeePZQdPMwZSWHNVYC5XODd7PvNDrDu
5MZJjkz4+6LbwwAvyew62meFN2QEsYbK2Brtbhze+IjE27FGWlSw4K3jlwa409MD
MTf4JU41ELaYY8G/LSNDJsBVhhkHzvXR9iCbXxNz3IL0dQDNj7h4LKhBy0q7hvqg
kDzwlmBO4WKSmCAuky44cXmd
-----END CERTIFICATE-----
subject=/CN=li190-250.members.linode.com
issuer=/CN=li190-250.members.linode.com
---
No client certificate CA names sent
---
SSL handshake has read 1714 bytes and written 637 bytes
---
New, TLSv1/SSLv3, Cipher is DHE-RSA-AES256-SHA
Server public key is 2048 bit
Secure Renegotiation IS supported
Compression: NONE
Expansion: NONE
SSL-Session:
    Protocol  : SSLv3
    Cipher    : DHE-RSA-AES256-SHA
    Session-ID: 0798D16B0A54D07BCA4C7FE24E32CAC5F76C7407BD96E30B3DD57C9513140B79
    Session-ID-ctx:
    Master-Key: B7A983FE5BEDB5D12F0DACE0E8623D9F8B11AF4F2743EF9C60B20B69E9846C5E336577E9D8D3387CD00D103DDAE778CF
    Key-Arg   : None
    PSK identity: None
    PSK identity hint: None
    SRP username: None
    Start Time: 1439995818
    Timeout   : 300 (sec)
    Verify return code: 18 (self signed certificate)
---
BfMYroe26WYalil77FoDi9qh59eK5xNr
HEARTBEATING
read R BLOCK
read:errno=0

bandit14@melinda:~$ bandit15@melinda:~$ openssl s_client -connect 127.0.0.1:30001 -quiet
-bash: bandit15@melinda:~$: command not found
bandit14@melinda:~$ openssl s_client -connect 127.0.0.1:30001 -quiet
depth=0 CN = li190-250.members.linode.com
verify error:num=18:self signed certificate
verify return:1
depth=0 CN = li190-250.members.linode.com
verify return:1
BfMYroe26WYalil77FoDi9qh59eK5xNr
Correct!
cluFn7wTiGryunymYOu4RcffSxQluehd

read:errno=0










 








   




   









#Wargames_IT13082116

##### Level0
```
[DulanjanaNiroshan.Dulanjana-PC] ➤ ssh bandit0@bandit.labs.overthewire.org
bandit0@bandit.labs.overthewire.org's password: bandit0
```
```
bandit0@melinda:~$ ls
readme
bandit0@melinda:~$ cat readme
boJ9jbbUNNfktd78OOpsqOltutMc3MY1
bandit0@melinda:~$ logout
```

##### level0->level1
```
[DulanjanaNiroshan.Dulanjana-PC] ➤ ssh bandit1@bandit.labs.overthewire.org
bandit1@bandit.labs.overthewire.org's password: boJ9jbbUNNfktd78OOpsqOltutMc3MY1
```
```
bandit1@melinda:~$ ls
-
bandit1@melinda:~$ cat ./-
CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9
bandit1@melinda:~$
bandit1@melinda:~$ logout
```

##### level1->level2
```
[DulanjanaNiroshan.Dulanjana-PC] ➤ ssh bandit2@bandit.labs.overthewire.org
bandit2@bandit.labs.overthewire.org's password: CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9
```
```
bandit2@melinda:~$ ls
spaces in this filename
bandit2@melinda:~$ cat "spaces in this filename"
UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK
bandit2@melinda:~$ logout
```

##### level2->level3
```
[DulanjanaNiroshan.Dulanjana-PC] ➤ ssh bandit3@bandit.labs.overthewire.org
bandit3@bandit.labs.overthewire.org's password: UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK
```
```
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
```

##### level4->level5
```
[DulanjanaNiroshan.Dulanjana-PC] ➤ ssh bandit4@bandit.labs.overthewire.org
bandit4@bandit.labs.overthewire.org's password: pIwrPrtPN36QITSp3EQaw936yaFoFgAB
```
```
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
```

##### level5->level6
```
[DulanjanaNiroshan.Dulanjana-PC] ➤ ssh bandit5@bandit.labs.overthewire.org 
bandit5@bandit.labs.overthewire.org's password: koReBOKuIDDepwhWk7jZC0RTdopnAYKh
```
```
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
```
##### level6->level7
```
[DulanjanaNiroshan.Dulanjana-PC] ➤ ssh bandit6@bandit.labs.overthewire.org 
bandit6@bandit.labs.overthewire.org's password: DXjZPULLxYr17uwoI01bNLQbtFemEgo7
```
```
bandit6@melinda:~$ find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
/var/lib/dpkg/info/bandit7.password
bandit6@melinda:~$ cat /var/lib/dpkg/info/bandit7.password
HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs
bandit6@melinda:~$ logout
```

##### level7->level8
```
[DulanjanaNiroshan.Dulanjana-PC] ➤ ssh bandit7@bandit.labs.overthewire.org 
bandit7@bandit.labs.overthewire.org's password: HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs
```
```
bandit7@melinda:~$ ls -lh
total 4.0M
-rw-r----- 1 bandit8 bandit7 4.0M Nov 14  2014 data.txt
bandit7@melinda:~$ cat data.txt | grep millionth
millionth       cvX2JJa4CFALtqS87jk27qwqGhBM9plV
bandit7@melinda:~$ logout
```
##### level8->level9
```
[DulanjanaNiroshan.Dulanjana-PC] ➤ ssh bandit8@bandit.labs.overthewire.org 
bandit8@bandit.labs.overthewire.org's password: cvX2JJa4CFALtqS87jk27qwqGhBM9plV
```
```
bandit8@melinda:~$ ls
data.txt
bandit8@melinda:~$ cat data.txt |sort |uniq -u
UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR
bandit8@melinda:~$ logout
```

##### level9->level10
```
[DulanjanaNiroshan.Dulanjana-PC] ➤ ssh bandit8@bandit.labs.overthewire.org 
bandit9@bandit.labs.overthewire.org's password: UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR
```
```
bandit9@melinda:~$ ls
data.txt
bandit9@melinda:~$ strings data.txt | grep "=="
I========== the6
========== password
========== ism
========== truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk
bandit9@melinda:~$ logout
```

##### level10->level11
```
[DulanjanaNiroshan.Dulanjana-PC] ➤ ssh bandit10@bandit.labs.overthewire.org 
bandit10@bandit.labs.overthewire.org's password: truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk  
```
```
bandit10@melinda:~$ ls
data.txt
bandit10@melinda:~$ cat data.txt
VGhlIHBhc3N3b3JkIGlzIElGdWt3S0dzRlc4TU9xM0lSRnFyeEUxaHhUTkViVVBSCg==
bandit10@melinda:~$ base64 -d data.txt
The password is IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR
bandit9@melinda:~$ logout
```

#####level11->level12
```
[DulanjanaNiroshan.Dulanjana-PC] ➤ ssh bandit11@bandit.labs.overthewire.org 
bandit11@bandit.labs.overthewire.org's password: IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR
```
```
bandit11@melinda:~$ ls
data.txt
bandit11@melinda:~$ cat data.txt
Gur cnffjbeq vf 5Gr8L4qetPEsPk8htqjhRK8XSP6x2RHh
bandit11@melinda:~$ cat data.txt| tr 'A-Za-z' 'N-ZA-Mn-za-m'
The password is 5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu
bandit11@melinda:~$ logout
```

#####level12->level13
```
[DulanjanaNiroshan.Dulanjana-PC] ➤ ssh bandit12@bandit.labs.overthewire.org 
bandit12@bandit.labs.overthewire.org's password: 5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu
```
```
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
```
```
bandit12@melinda:/tmp/dulanjana123$ zcat -d data2 > data3
bandit12@melinda:/tmp/dulanjana123$ file data3
data3: bzip2 compressed data, block size = 900k
bandit12@melinda:/tmp/dulanjana123$ bzip2 -d data3
bzip2: Can't guess original name for data3 -- using data3.out
bandit12@melinda:/tmp/dulanjana123$ file data3.out
data3.out: gzip compressed data, was "data4.bin", from Unix, last modified: Fri Nov 14 10:32:20 2014, max compression
```
```
bandit12@melinda:/tmp/dulanjana123$ zcat -d data3.out > data4
bandit12@melinda:/tmp/dulanjana123$ file data4
data4: POSIX tar archive (GNU)
```
```
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
```
##### level13->level14
```
[DulanjanaNiroshan.Dulanjana-PC] ➤ ssh bandit13@bandit.labs.overthewire.org
bandit13@bandit.labs.overthewire.org's password: 8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL
```
```

bandit13@melinda:~$ ls
sshkey.private
bandit13@melinda:~$ ssh -i sshkey.private bandit14@localhost
Could not create directory '/home/bandit13/.ssh'.
The authenticity of host 'localhost (127.0.0.1)' can't be established.
ECDSA key fingerprint is 05:3a:1c:25:35:0a:ed:2f:cd:87:1c:f6:fe:69:e4:f6.
Are you sure you want to continue connecting (yes/no)? yes
bandit14@melinda:~$ cat /etc/bandit_pass/bandit14
4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e
```

##### level14->level15
```
bandit14@melissa:~$ telnet localhost 30000
Trying 127.0.0.1...
Connected to localhost.
Escape character is '^]'.
4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e
Correct!
BfMYroe26WYalil77FoDi9qh59eK5xNr
 
Connection closed by foreign h
```
##### level15->level16
```
bandit15@melissa:~$ openssl s_client -connect localhost:30001
CONNECTED(00000003)
depth=0 /CN=melissa.labs.overthewire.org
verify error:num=18:self signed certificate
verify return:1
depth=0 /CN=melissa.labs.overthewire.org
verify return:1
---
Certificate chain
0 s:/CN=melissa.labs.overthewire.org
i:/CN=melissa.labs.overthewire.org
---
Server certificate
-----BEGIN CERTIFICATE-----
MIICyjCCAbICCQDE6DxysXt56TANBgkqhkiG9w0BAQUFADAnMSUwIwYDVQQDExxt
ZWxpc3NhLmxhYnMub3ZlcnRoZXdpcmUub3JnMB4XDTEyMDUxMDIxMzYzOVoXDTIy
MDUwODIxMzYzOVowJzElMCMGA1UEAxMcbWVsaXNzYS5sYWJzLm92ZXJ0aGV3aXJl
Lm9yZzCCASIwDQYJKoZIhvcNAQEBBQADggEPADCCAQoCggEBAL85VFz7tV/45RID
5x804dSKyvmZH62lOjAg0NhW7Kbc9L6mmq3EVd4As/kupXYs0d7hCiMjJri0X2e8
GTM+nysxZLTR1qa2j/KOzQ7FgQ4vp4R4JQZP6ofhNPvBybh6BwYE5hFzRARK9Y3x
+dr3ZefeAE7Ea1k6NzH7p6HAtpkG36SD6GbhLV9HFhwOCwBWGPnXPfXA/2XBdZzY
/h6FWrxZPqdALjy8dCeRlNPqG7dD8CIWK4dpBGudxfyXiki5YfwOirotEWjI1E/C
JK2/jWT7tYLIrVKzOF0dwDWYxNMRnwn5+S2F2/AERSRBlwrtMb6jJf+g2pU27eAe
3xvtJs8CAwEAATANBgkqhkiG9w0BAQUFAAOCAQEAtDKEX9gWmEyKqkhPN1L+wjEi
M2HH/XMgDxHrqWgy0Xl9gznuvM0pkOEXUOKWkfKDQfskk8cbgqn0hEvaX7AKrNL4
Nbm1JD+hUSSFtW3sxmv+aHkdEz6H70oUp712wP2Hu3DF7paVSPC5yB1vqoNYmHX/
J9CwqptVj+dLaDeY+ayzEwOuaEcd+cpP4OTbMLy0SuKLONr1+NaA5IPaVE/XOmlE
wW7zNRcJ3kxnvsHrqF4ZeYPBLNmhDT3ZD4qso+JiL9lme5YbP7+dCQo5Oa1AT7Dz
UmKZhWQTLsnI6Eyl8NwLnxiSkIOUigN6WF8bnd1F9FVKfmjQDSjBJHGqTE4Trg==
-----END CERTIFICATE-----
subject=/CN=melissa.labs.overthewire.org
issuer=/CN=melissa.labs.overthewire.org
---
No client certificate CA names sent
---
SSL handshake has read 1436 bytes and written 229 bytes
---
New, TLSv1/SSLv3, Cipher is DHE-RSA-AES256-SHA
Server public key is 2048 bit
Secure Renegotiation IS supported
Compression: zlib compression
Expansion: zlib compression
SSL-Session:
Protocol  : TLSv1
Cipher    : DHE-RSA-AES256-SHA
Session-ID: 5AED820CF694E077E4F590C9089FC77A050DC3A3BBCE7F383B811CBD4937DAC9
Session-ID-ctx:
Master-Key: 201FB305DD48B3D4746DA988FD88B0EF939A766A393DFED1D9184DA6BD41B28F4ABDF06AE23DA7B0DEFF0329C69499E8
Key-Arg   : None
TLS session ticket:
0000 - b4 b5 f0 bf 88 14 bc 85-59 9b e6 22 ea f3 7f a1   ........Y.."....
0010 - 61 8a 25 48 a4 08 cb 5c-f0 2d 8a 97 b1 78 c3 eb   a.%H...\.-...x..
0020 - 14 6b 41 99 71 5e 62 6b-bf 6a 17 18 82 cc 69 1a   .kA.q^bk.j....i.
0030 - d5 a3 fd 08 97 8c b8 3a-d7 52 7c 01 31 eb c8 be   .......:.R|.1...
0040 - 09 a0 fd 58 cc aa d9 98-51 53 71 98 7d 8f 92 78   ...X....QSq.}..x
0050 - 00 8c d3 1d b0 57 df 70-0a af 92 44 6c b8 5e 85   .....W.p...Dl.^.
0060 - 1f e1 87 fd c6 da db bd-35 da 89 a0 b9 da fe 37   ........5......7
0070 - 0f 5b 4e d9 96 16 3b 7e-6b fb 0f 42 51 67 5f d9   .[N...;~k..BQg_.
0080 - 11 9a 8d a3 95 2a 9b d1-f6 9b ce 2c 55 62 92 4b   .....*.....,Ub.K
0090 - a8 89 b1 9f 8a b8 f7 6b-b7 65 2d e4 7e 52 6b 6c   .......k.e-.~Rkl
 
Compression: 1 (zlib compression)
Start Time: 1363810708
Timeout   : 300 (sec)
Verify return code: 18 (self signed certificate)
---
BfMYroe26WYalil77FoDi9qh59eK5xNr
Correct!
cluFn7wTiGryunymYOu4RcffSxQluehd
 
read:errno=0
```

##### level16->level17
```
bandit16@melissa:~$ nmap -p 31000-32000 localhost
 
Starting Nmap 5.21 ( http://nmap.org ) at 2013-03-20 21:24 CET
Nmap scan report for localhost (127.0.0.1)
Host is up (0.0033s latency).
Not shown: 996 closed ports
PORT      STATE SERVICE
31046/tcp open  unknown
31518/tcp open  unknown
31691/tcp open  unknown
31790/tcp open  unknown
31960/tcp open  unknown
 
Nmap done: 1 IP address (1 host up) scanned in 0.19 seconds
 
#We can see we have 5 ports open. Nmap does have a script scan to verify SSL, but it does not seem to work on this server.
#Thus it's quicker to manually check each port. To speed this up, I will tell you I verified it on port 31790.
 
bandit16@melissa:~$ openssl s_client -connect localhost:31790
CONNECTED(00000003)
depth=0 /CN=melissa.labs.overthewire.org
verify error:num=18:self signed certificate
verify return:1
depth=0 /CN=melissa.labs.overthewire.org
verify return:1
---
Certificate chain
0 s:/CN=melissa.labs.overthewire.org
i:/CN=melissa.labs.overthewire.org
---
Server certificate
-----BEGIN CERTIFICATE-----
MIICyjCCAbICCQDE6DxysXt56TANBgkqhkiG9w0BAQUFADAnMSUwIwYDVQQDExxt
ZWxpc3NhLmxhYnMub3ZlcnRoZXdpcmUub3JnMB4XDTEyMDUxMDIxMzYzOVoXDTIy
MDUwODIxMzYzOVowJzElMCMGA1UEAxMcbWVsaXNzYS5sYWJzLm92ZXJ0aGV3aXJl
Lm9yZzCCASIwDQYJKoZIhvcNAQEBBQADggEPADCCAQoCggEBAL85VFz7tV/45RID
5x804dSKyvmZH62lOjAg0NhW7Kbc9L6mmq3EVd4As/kupXYs0d7hCiMjJri0X2e8
GTM+nysxZLTR1qa2j/KOzQ7FgQ4vp4R4JQZP6ofhNPvBybh6BwYE5hFzRARK9Y3x
+dr3ZefeAE7Ea1k6NzH7p6HAtpkG36SD6GbhLV9HFhwOCwBWGPnXPfXA/2XBdZzY
/h6FWrxZPqdALjy8dCeRlNPqG7dD8CIWK4dpBGudxfyXiki5YfwOirotEWjI1E/C
JK2/jWT7tYLIrVKzOF0dwDWYxNMRnwn5+S2F2/AERSRBlwrtMb6jJf+g2pU27eAe
3xvtJs8CAwEAATANBgkqhkiG9w0BAQUFAAOCAQEAtDKEX9gWmEyKqkhPN1L+wjEi
M2HH/XMgDxHrqWgy0Xl9gznuvM0pkOEXUOKWkfKDQfskk8cbgqn0hEvaX7AKrNL4
Nbm1JD+hUSSFtW3sxmv+aHkdEz6H70oUp712wP2Hu3DF7paVSPC5yB1vqoNYmHX/
J9CwqptVj+dLaDeY+ayzEwOuaEcd+cpP4OTbMLy0SuKLONr1+NaA5IPaVE/XOmlE
wW7zNRcJ3kxnvsHrqF4ZeYPBLNmhDT3ZD4qso+JiL9lme5YbP7+dCQo5Oa1AT7Dz
UmKZhWQTLsnI6Eyl8NwLnxiSkIOUigN6WF8bnd1F9FVKfmjQDSjBJHGqTE4Trg==
-----END CERTIFICATE-----
subject=/CN=melissa.labs.overthewire.org
issuer=/CN=melissa.labs.overthewire.org
---
No client certificate CA names sent
---
SSL handshake has read 1436 bytes and written 229 bytes
---
New, TLSv1/SSLv3, Cipher is DHE-RSA-AES256-SHA
Server public key is 2048 bit
Secure Renegotiation IS supported
Compression: zlib compression
Expansion: zlib compression
SSL-Session:
Protocol  : TLSv1
Cipher    : DHE-RSA-AES256-SHA
Session-ID: 913086AEE63018EFB254F2105A4597FC5CB419BFFBCE5B1FAF10EC7967668530
Session-ID-ctx:
Master-Key: 155AF180C1B8BB81BDE85105A05F1C6D5E7B8511B6C9E83B257EC2012B102170522C965E114B233D108A838C7520DED6
Key-Arg   : None
TLS session ticket:
0000 - 95 66 61 4b c2 a6 3c 36-50 d2 8d fd 58 fb 03 30   .faK..<6P...X..0
0010 - 2c 38 20 12 84 02 08 68-d0 f3 5d 47 1a 8a 86 b2   ,8 ....h..]G....
0020 - 01 19 4f cb 46 85 e8 a2-36 e2 ac fd 9f 2e 66 1e   ..O.F...6.....f.
0030 - ab 99 67 49 93 f0 82 0e-56 60 0f 4b c2 28 b6 7b   ..gI....V`.K.(.{
0040 - 7f 55 f9 cf 9d d9 07 0a-4f 40 a6 7d cc 89 4b b4   .U......O@.}..K.
0050 - f3 2a 0e b8 35 ac e9 e3-04 b7 3b e8 b5 32 8b 7a   .*..5.....;..2.z
0060 - a8 05 c9 e9 89 74 c4 fc-40 8d 3b 49 2e de 63 be   .....t..@.;I..c.
0070 - 25 b5 f5 05 85 17 82 92-8b 95 5c 8b e6 e9 f3 e7   %.........\.....
0080 - 21 49 9b a6 b8 82 fc d8-6e 67 54 31 ad a3 75 ee   !I......ngT1..u.
0090 - 43 07 47 54 bb fa d9 9a-2a ef 20 85 28 2d 2b 63   C.GT....*. .(-+c
 
Compression: 1 (zlib compression)
Start Time: 1363811727
Timeout   : 300 (sec)
Verify return code: 18 (self signed certificate)
---
cluFn7wTiGryunymYOu4RcffSxQluehd
Correct!
-----BEGIN RSA PRIVATE KEY-----
MIIEogIBAAKCAQEAvmOkuifmMg6HL2YPIOjon6iWfbp7c3jx34YkYWqUH57SUdyJ
imZzeyGC0gtZPGujUSxiJSWI/oTqexh+cAMTSMlOJf7+BrJObArnxd9Y7YT2bRPQ
Ja6Lzb558YW3FZl87ORiO+rW4LCDCNd2lUvLE/GL2GWyuKN0K5iCd5TbtJzEkQTu
DSt2mcNn4rhAL+JFr56o4T6z8WWAW18BR6yGrMq7Q/kALHYW3OekePQAzL0VUYbW
JGTi65CxbCnzc/w4+mqQyvmzpWtMAzJTzAzQxNbkR2MBGySxDLrjg0LWN6sK7wNX
x0YVztz/zbIkPjfkU1jHS+9EbVNj+D1XFOJuaQIDAQABAoIBABagpxpM1aoLWfvD
KHcj10nqcoBc4oE11aFYQwik7xfW+24pRNuDE6SFthOar69jp5RlLwD1NhPx3iBl
J9nOM8OJ0VToum43UOS8YxF8WwhXriYGnc1sskbwpXOUDc9uX4+UESzH22P29ovd
d8WErY0gPxun8pbJLmxkAtWNhpMvfe0050vk9TL5wqbu9AlbssgTcCXkMQnPw9nC
YNN6DDP2lbcBrvgT9YCNL6C+ZKufD52yOQ9qOkwFTEQpjtF4uNtJom+asvlpmS8A
vLY9r60wYSvmZhNqBUrj7lyCtXMIu1kkd4w7F77k+DjHoAXyxcUp1DGL51sOmama
+TOWWgECgYEA8JtPxP0GRJ+IQkX262jM3dEIkza8ky5moIwUqYdsx0NxHgRRhORT
8c8hAuRBb2G82so8vUHk/fur85OEfc9TncnCY2crpoqsghifKLxrLgtT+qDpfZnx
SatLdt8GfQ85yA7hnWWJ2MxF3NaeSDm75Lsm+tBbAiyc9P2jGRNtMSkCgYEAypHd
HCctNi/FwjulhttFx/rHYKhLidZDFYeiE/v45bN4yFm8x7R/b0iE7KaszX+Exdvt
SghaTdcG0Knyw1bpJVyusavPzpaJMjdJ6tcFhVAbAjm7enCIvGCSx+X3l5SiWg0A
R57hJglezIiVjv3aGwHwvlZvtszK6zV6oXFAu0ECgYAbjo46T4hyP5tJi93V5HDi
Ttiek7xRVxUl+iU7rWkGAXFpMLFteQEsRr7PJ/lemmEY5eTDAFMLy9FL2m9oQWCg
R8VdwSk8r9FGLS+9aKcV5PI/WEKlwgXinB3OhYimtiG2Cg5JCqIZFHxD6MjEGOiu
L8ktHMPvodBwNsSBULpG0QKBgBAplTfC1HOnWiMGOU3KPwYWt0O6CdTkmJOmL8Ni
blh9elyZ9FsGxsgtRBXRsqXuz7wtsQAgLHxbdLq/ZJQ7YfzOKU4ZxEnabvXnvWkU
YOdjHdSOoKvDQNWu6ucyLRAWFuISeXw9a/9p7ftpxm0TSgyvmfLF2MIAEwyzRqaM
77pBAoGAMmjmIJdjp+Ez8duyn3ieo36yrttF5NSsJLAbxFpdlc1gvtGCWW+9Cq0b
dxviW8+TFVEBl1O4f7HVm6EpTscdDxU+bCXWkfjuRb7Dy9GOtt9JPsX8MBTakzh3
vBgsyi/sN3RqRBcGU40fOoZyfAMT8s1m/uYv52O6IgeuZ/ujbjY=
-----END RSA PRIVATE KEY-----
 
read:errno=0
 
#Now we have an ssh key we can use. We need to copy it into a file to it.
 
bandit16@melissa:~$ mkdir /tmp/ssss
bandit16@melissa:~$ cd /tmp/ssss
bandit16@melissa:/tmp/ssss$ touch sshkey.private
bandit16@melissa:/tmp/ssss$ vi sshkey.private
bandit16@melissa:/tmp/ssss$ chmod 600 sshkey.private
bandit16@melissa:/tmp/ssss$ ssh -i sshkey.private bandit17@localhost
Could not create directory '/home/bandit16/.ssh'.
The authenticity of host 'localhost (127.0.0.1)' can't be established.
RSA key fingerprint is 9d:09:d9:46:84:df:f9:dd:cc:7c:dc:49:a0:95:b2:10.
Are you sure you want to continue connecting (yes/no)? yes
Failed to add the host to the list of known hosts (/home/bandit16/.ssh/known_hosts).
bandit17@melissa:~$
```

###### level17->level18
```
bandit17@melissa:~$ ls
passwords.new  passwords.old
bandit17@melissa:~$ diff passwords.new  passwords.old
42c42
< kfBf3eYk5BPBRzwjqutbbfE887SVc5Yd
---
> bECYSoXjOeGseirUCztuCBDF3xXqE7By
```

###### level18->level19
```
Byebye !
Connection to bandit.labs.overthewire.org closed.
 
ssh bandit18@bandit.labs.overthewire.org cat readme
bandit18@bandit.labs.overthewire.org's password:
IueksS7Ubh8G3DCwVzrTd8rAVOwq3M5x
```

###### level19->level20
```
bandit19@melissa:~$ ls
bandit20-do
bandit19@melissa:~$ ./bandit20-do
Run a command as another user.
Example: ./bandit20-do id
bandit19@melissa:~$ ./bandit20-do id
uid=11019(bandit19) gid=11019(bandit19) euid=11020(bandit20) groups=11020(bandit20),11019(bandit19)
bandit19@melissa:~$ ./bandit20-do whoami
bandit20
bandit19@melissa:~$ ./bandit20-do cat /etc/bandit_pass/bandit20
GbKksEFF4yrVs6il55v6gwY5aVje5f0j
```








 








   




   









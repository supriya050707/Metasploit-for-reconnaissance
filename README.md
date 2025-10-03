# Metasploit-for-reconnaissance
# Metasploit
Metasploit for reconnaissance in pentesting

# AIM:

To get introduced to Metasploit Framework and to  perform reconnaissance  in pentesting .

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:

Find out the ip address of the attackers system

## output

<img width="1920" height="463" alt="exp 5" src="https://github.com/user-attachments/assets/a94278d2-d311-4ee0-a1aa-2c7d7e0ae86b" />



Invoke msfconsole:


## OUTPUT:

<img width="955" height="416" alt="exp5(1)" src="https://github.com/user-attachments/assets/7604a70a-42c2-4aaa-a837-223405298844" />


Port Scanning:

## OUTPUT:

<img width="1920" height="165" alt="exp 5 3" src="https://github.com/user-attachments/assets/fde54641-aef2-4142-86cc-2fec2570adbf" />

kali > ls -l

## output

<img width="1920" height="334" alt="exp5 4" src="https://github.com/user-attachments/assets/6cd47e13-9c27-4d0f-8c61-508b844ba254" />

msf >search name:Microsoft type:exploit

## output

<img width="955" height="1045" alt="exp 5 5" src="https://github.com/user-attachments/assets/41e2aea4-8f01-4d9e-aba3-39e35553ad3a" />

## MYSQL ENUMERATION

## output

<img width="1920" height="674" alt="exp 5 6" src="https://github.com/user-attachments/assets/e2e82f89-fc0e-4d6c-a9aa-f5e430767791" />

use auxiliary/scanner/mysql/mysql_version

## output

<img width="1920" height="453" alt="exp5 8" src="https://github.com/user-attachments/assets/21e097a5-eb59-4b02-8800-bb3b19ea6f3d" />

Use the set rhosts command to set the parameter and run the module, as follows:

## output

<img width="1920" height="298" alt="exp 5 9" src="https://github.com/user-attachments/assets/5afdeb82-71a8-4916-b4c0-6d50d32cb0cb" />

After scanning, you can also brute force MySQL root account via Metasploit's auxiliary(scanner/mysql/mysql_login) module.

## output

<img width="1920" height="577" alt="exp 5 10" src="https://github.com/user-attachments/assets/f4180649-1f9f-41d3-ad1f-c13ac794b5ec" />


<img width="1920" height="319" alt="exp 5 11" src="https://github.com/user-attachments/assets/6808d32c-316c-49bb-8973-a4c737b45477" />


## RESULT:
The Metasploit framework for reconnaissance is  examined successfully





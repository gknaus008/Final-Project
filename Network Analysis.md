 Network Forensic Analysis Report


```bash

  ## Time Thieves ##
  You must inspect your traffic capture to answer the following questions:

   1. What is the domain name of the users custom site?
      -frank-n-ted.com

   2. What is the IP address of the Domain Controller (DC) of the AD network?
      -10.6.12.12

  Both of these answers can be found here:
```
 ![fnt](images/fnt.PNG)
 
```bash
   3. What is the name of the malware downloaded to the 10.6.12.203 machine?
      -June11.dll
```
 ![june11](images/june11.PNG)
 
 ```bash
   
   5. What kind of malware is this classified as?
   -Trojan
```
 ![malware1](images/malware1.PNG)

 Vulnerable Windows Machine

```bash
   1. Find the following information about the infected Windows machine:
      - Host name: ROTTERDAM-PC
      - IP address: 172.16.4.205
      - MAC address: 00:59:07:b0:63:a4
```
 ![ROTT](images/rotterdam.PNG)
    
```bash   
   2. What is the username of the Windows user whose computer is infected?
      -mattijs.dervies
```
 ![CNAME](images/RotterdamUsername.JPG)
 
 ```bash
   3. What are the IP addresses used in the actual infection traffic?
      -185.243.115.84
 ```
  ![Infect](images/InfConvo2.png)

---

## Illegal Downloads
```bash

   1. Find the following information about the machine with IP address `10.0.0.201`:
      - MAC address: 00:16:17:18:66:c8
 ```
  ![SRC](images/torrent.PNG)
  
```bash
      - Windows username: elmer.blanco
```
 ![TCNAME](images/elmerblanco.JPG)
 
```bash 
   2. Which torrent file did the user download?
      - Betty_Boop_Rhythm_on_the_Reservation.avi.torrent
```
 ![TName](images/elmerblanco.JPG)

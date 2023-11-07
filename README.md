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

## OUTPUT:
![image](https://github.com/Priya-Loganathan/Metasploit-for-reconnaissance/assets/121166075/ad5d2d07-fdb3-4f51-80e9-67c44a829283)

### Invoke msfconsole

## OUTPUT:
![image](https://github.com/Priya-Loganathan/Metasploit-for-reconnaissance/assets/121166075/1ae27d8a-8f1c-44f6-97f4-d2dae3c2c542)

Type help or a question mark "?" to see the list of all available commands you can use inside msfconsole.

![image](https://github.com/Priya-Loganathan/Metasploit-for-reconnaissance/assets/121166075/08435bf9-6158-43ab-99ba-fc12c35598ae)

### Port scanning:
#### msf > nmap -sT 192.168.1810/24-p1-1000  
![image](https://github.com/Priya-Loganathan/Metasploit-for-reconnaissance/assets/121166075/64fc050b-1d90-4717-a4ae-b4ff7928f78c)

#### msf > db_nmap 192.168.181.0/24
![image](https://github.com/Priya-Loganathan/Metasploit-for-reconnaissance/assets/121166075/04d309f5-750c-4e61-a107-3ed9925d018c)

#### kali > ls-l
![image](https://github.com/Priya-Loganathan/Metasploit-for-reconnaissance/assets/121166075/3e49fd88-d760-41fc-9b6a-4d1f8bac2c7d)

#### search
![image](https://github.com/Priya-Loganathan/Metasploit-for-reconnaissance/assets/121166075/7117b7be-161d-439c-b00f-5ca7a359b738)

#### info
![image](https://github.com/Priya-Loganathan/Metasploit-for-reconnaissance/assets/121166075/c3ba8ca1-2312-4b2d-91a0-d323d25f7f29)

### MYSQL ENUMERATION
#### db_nmap -sV -sC -p 3306 <metasploitable_ip_address>
![image](https://github.com/Priya-Loganathan/Metasploit-for-reconnaissance/assets/121166075/1f824fcd-14af-4457-b815-1d803380288b)

#### search
![image](https://github.com/Priya-Loganathan/Metasploit-for-reconnaissance/assets/121166075/9c46d9bd-8ba6-4f8c-b2f2-f853b76f85bd)

#### use 11 Or: use auxiliary/scanner/mysql/mysql_version
![image](https://github.com/Priya-Loganathan/Metasploit-for-reconnaissance/assets/121166075/3e7ae3d4-ca83-418d-9743-c076e6709c15)

#### Use the set rhosts command to set the parameter and run the module, as follows:
![image](https://github.com/Priya-Loganathan/Metasploit-for-reconnaissance/assets/121166075/15546f24-b6db-44a1-825f-02d2705228fc)

#### After scanning, you can also brute force MySQL root account via Metasploit's auxiliary(scanner/mysql/mysql_login) module
![image](https://github.com/Priya-Loganathan/Metasploit-for-reconnaissance/assets/121166075/d268c4c3-484d-46bf-9438-b4e03c2291c8)

#### /usr/share/wordlists: set PASS_FILE /usr/share/wordlistss/rockyou.txt
![image](https://github.com/Priya-Loganathan/Metasploit-for-reconnaissance/assets/121166075/32c482b0-6178-41de-b5b6-34229bf33e63)
![image](https://github.com/Priya-Loganathan/Metasploit-for-reconnaissance/assets/121166075/e4ab6d37-02f3-4c57-b411-72cdc59cbb6e)

## RESULT:
The Metasploit framework for reconnaissance is  examined successfully.

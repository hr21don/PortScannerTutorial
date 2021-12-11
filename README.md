# PortScannerTutorial
How to build a simple Port Scanner? Lets get started! 

## What is a Port Scanner?
A port scanner is the process of running through a list of ports to see if they are open or not. 

## How can we do this?
Using, sockets to provide the basic functionality of a port scanner. 
This is a form of "reconnaissance" for hackers and penetration testers.

## How to run? || Download the zip file to your downloads directory and extract it.
* Open up the file & change to the directory with Simpleportscanner.py in it
* Run Simpleportscanner.py locally and notice the list of ports that are open.

## How to find Ports in use?

## Method 1: Use Command Prompt 

1. Run CMD as administrator.

<img width="340" alt="Capture" src="https://user-images.githubusercontent.com/91548582/145676935-8de44def-5007-4ed1-9aa8-037b47ff4fe2.PNG">

2. Once in the command prompt window, execute the command below.

```
netstat -ab

```

3.  After, you run the command you will see the port number right next to the ip address for e.g. 192.168.1.198:50412. 

![check-ports-in-use-windows-10-01 (1)](https://user-images.githubusercontent.com/91548582/145677026-165bd7dd-e1de-4b02-8bad-d78726f158be.png)


## Method 2: Currports Utility

Nirsoft Utilities has a pretty neat and lightweight tool called CurrPorts which lists all the ports that are in use by Windows and other programs. In case you don’t, Nirsoft has a lot of small and portable apps that are quite useful in day to day life. If you’ve never used Nirsoft Utilities, go browse the developer site and you will find interesting little tools.

1. First, download CurrPorts from the official website. Being a portable application, you don’t have to install it. After downloading, extract the exe file from the zip file and double-click on it to open.

2. As soon as you open the window, the application will list all the connections and their ports. You can find the port number under the Local Port section.

![check-ports-in-use-windows-10-04](https://user-images.githubusercontent.com/91548582/145677068-9cf5893f-ad9e-40dd-896b-c5a8522b73b4.png)


## Resources To Try for youself

  TCPview(2021). https://docs.microsoft.com/en-us/sysinternals/downloads/tcpview . Date Accessed: 11/12/21
  Currports(2021). https://www.nirsoft.net/utils/cports.html#DownloadLinks . Date Accessed: 11/12/21
  
  

## Output || Testing the Reconnaissance Tool

In this example output, the ports that are open are 'portnumbers: 135' and '149' for the given REMOTE host x.x.x.x.  

<img width="463" alt="Capture" src="https://user-images.githubusercontent.com/91548582/145676822-ef6d7b44-bf19-4c01-a812-14fd174dd4d2.PNG">



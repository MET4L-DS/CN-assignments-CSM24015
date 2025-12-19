# CN-assignments-CSM24015
---
Name: **Ayanshu Dev Sikdar**

Roll no: **CSM24015**

Programme: **MCA (3rd Semester)**

Subject: **Computer Networks Lab (CS520)**

---
## Assignment 1

### **Objective:** To gain first hands on experience of basic Socket Programming.

### **Exercise:** Write a program to run TCP client and server socket programs where client first says “Hi” and in response server says “Hello”.

### **Output:**

<img width="982" height="364" alt="Pasted image 20251218232352" src="https://github.com/user-attachments/assets/50166472-77a3-4fac-bd06-58da0a248c18" />


---

## Assignment 2

### **Objective:** To gain experience of TCP Socket Programming for simple applications.

### **Exercise:** Write a program using TCP socket to implement the following: 
1. Server maintains records of fruits in the format: fruit-name, quantity Last-sold, (server timestamp), 
2. Multiple client purchase the fruits one at a time, 
3. The fruit quantity is updated each time any fruit is sold, 
4. Send regret message to a client if therequested quantityof the fruit is not available. 
5. Display the customer ids <IP, port> who has done transactions already. This list should be updated in the server every time a transaction occurs. 
6. The total number of unique customers who did some transaction will be displayed to the customer every time.

### **Output:**

![[Pasted image 20251219000024.png](assignment2/Pasted image 20251219000024.png)]

---

## Assignment 3

### **Objective:** To gain experience of UDP Socket Programming for simple applications.

### **Exercise:** Redo assignment 2 using UDP socket.

### **Output:**

![[Pasted image 20251219000839.png]]

---

## Assignment 4

### **Objective:** To gain knowledge of packet capturing tools and understand header structures.

### **Exercise:** Install wireshark in a VM (Virtual Machine) environment. 
Draw a time diagram to show the steps in the protocols recorded in the captured file (saved in the `.pcap` file of wireshark) during a PING operation. List the L2, L3, L4 header fields that can be extracted from the `.pcap` file.

### **Output:**

![[Pasted image 20251219002227.png]]

![[Pasted image 20251219002337.png]]

![[Pasted image 20251219002259.png]]

---

## Assignment 5

### **Objective:** To gain knowledge of more packet capturing tools.

### **Exercise:** Learn and use maximum number of packet generation tools

### **Output:**

![[Pasted image 20251219005042.png]]

![[Pasted image 20251219005155.png]]

![[Pasted image 20251219005316.png]]

![[Pasted image 20251219010921.png]]

---

## Assignment 6

### **Objective:** To gain knowledge of more TCP/IP C libraries.

### **Exercise:** Develop a simple C based network simulator to analyze TCP traffic.

### **Output:**

![[Pasted image 20251219012616.png]]

---

## Assignment 7

### **Objective:** Client server communication with UDP packets

### **Exercise:** Write UDP client server socket program 
where client sends one/two number(s) (integer or floating point) to server and a scientific calculator operation (like sin,cos,\*,/, inv etc.) and server responds with the result after evaluating the value of operation as sent by the client. Server will maintain a scientific calculator. Detect in the mininet hosts with wireshark if there is any packet loss? Show it to the TA.

### **Output:**

![[Pasted image 20251219013908.png]]

---

## Assignment 8

### **Objective:** Using Thread library and TCP sockets.

### **Exercise:** Write a program in C using thread library and TCP sockets to build a chat server which enable clients communicating to each other through the chat server. 
Message logs must be maintained in the server in a text file. Each client will see the conversations in real time. Clients must handled by a server thread. (Keep it like a group chatbox)

### **Output:**

![[Pasted image 20251219015038.png]]

---

## Assignment 9

### **Objective:** File upload and download using TCP.

### **Exercise:** Write a client server socket program in TCP for uploading and downloading files between two different hosts. Also calculate the transfer time in both the cases.

### **Output:**

![[Pasted image 20251219020536.png]]

![[Pasted image 20251219021350.png]]

---

## Assignment 10

### **Objective:** Using RAW sockets to generate packets.

### **Exercise:** Write two C programs using raw socket to send 
1. TCP packet where TCP payload will contain your roll number. 
2. ICMP time stamp messages towards a target IP.

### **Output:**

![[Pasted image 20251219023641.png]]

![[Pasted image 20251219023702.png]]

![[Pasted image 20251219023855.png]]

![[Pasted image 20251219024038.png]]

---

## Assignment 11

### **Objective:** Using RAW sockets to generate TCP flooding attack.

### **Exercise:** Write a RAW socket program to generate TCP SYN flood based DDoS attack towards an IP address. Take four mininet hosts as agent devices.

### **Output:**

![[Pasted image 20251219030401.png]]

![[Pasted image 20251219030114.png]]

---

## Assignment 12

### **Objective:** Using RAW sockets to generate ICMP flooding attack.

### **Exercise:** Do the same attack as given in assignment no. 11 with ICMP packets using RAW socket.

### **Output:**

![[Pasted image 20251219031313.png]]

![[Pasted image 20251219031133.png]]

![[Pasted image 20251219031215.png]]

---

## Assignment 13

### **Objective:** To learn packet capturing and analysis.

### **Exercise:** Create a binary tree topology with 7 switches in mininet. Capture packets at the root switch.
Write a C program to extract the headers and draw a time diagram to show the protocols displayed in the captured file (save the `.pcap`/`.pcapng` file of wireshark/tshark) during a PING operation. List the L2, L3, L4 protocols that can be extracted from the `.pcap`/`.pcapng` file.

### **Output:**

![[Pasted image 20251219034621.png]]

![[Pasted image 20251219034416.png]]

![[Pasted image 20251219034444.png]]

![[Pasted image 20251219034055.png]]

![[Pasted image 20251219034229.png]]

![[Pasted image 20251219034931.png]]

---

## Assignment 14

### **Objective:** Creating customized topologies in mininet.

### **Exercise:** Create a custom leaf-spine topology in mininet using python which can be scaled with increasing switch radix.

### **Output:**

![[Pasted image 20251219035405.png]]

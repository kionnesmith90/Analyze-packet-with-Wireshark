
# Analyze packets using Wireshark

## Objective

Analyzing packets for malicious activity using Wireshark  

### Skills Learned

- Filter by specific parameters to find packets that match what you are looking for. 


### Tools Used

- Wireshark

## Steps

1. Applying a basic Wireshark filter (searching for IP address matches)
 
![image](https://github.com/user-attachments/assets/e715e6d7-51a1-434a-95bd-f7a1c464af54)

2. Searched for the first packet that lists TCP as a protocol (double clicked)

![image](https://github.com/user-attachments/assets/b8618bae-41e7-4f0a-9826-7c765c0ede07)

3. First objective was to find the destination port within the Transmission control protocol subtree

![image](https://github.com/user-attachments/assets/526b7df4-7239-40cd-b914-24525f12b22e)

Contains the initial web request to an HTTP website which is TCP port 80 <--- destination port

4. Performing a filter search to look up all packets where TCP = 80 (default port for web traffic)

![image](https://github.com/user-attachments/assets/e422af29-444c-4497-82c5-263b5a6829fb)
 
5. Then I was asked to click on the first packet and find the Time of Live value within the IP protocol verseion 4 subtree

![image](https://github.com/user-attachments/assets/941de1ac-01d5-4b8c-bb14-5442a82e053c)



 

# Capture your first packet
 
## Introduction
In this lab activity, you'll capture and analyze live network traffic using tcpdump. You'll use Linux commands in the Bash shell to complete these steps.

What you’ll do

You have multiple tasks in this lab:
1. Identify available network interfaces
2. Use tcpdump to capture live network traffic
3. Save network traffic to a packet capture file
4. Filter the packet capture data

## Activity overview
As a security analyst, it’s important to know how to capture and filter network traffic in a Linux environment. You’ll also need to know the basic concepts associated with network interfaces.

In this lab activity, you’ll perform tasks associated with using tcpdump to capture network traffic. You’ll capture the data in a packet capture (p-cap) file and then examine the contents of the captured packet data to focus on specific types of traffic.

Let’s capture network traffic!

## Scenario
You’re a network analyst who needs to use tcpdump to capture and analyze live network traffic from a Linux virtual machine.

The lab starts with your user account, called analyst, already logged in to a Linux terminal.

Your Linux user's home directory contains a sample packet capture file that you will use at the end of the lab to answer a few questions about the network traffic that it contains.

Here’s how you’ll do this: 

1. First, you’ll identify network interfaces to capture network packet data.
2. Second, you’ll use tcpdump to filter live network traffic.
3. Third, you’ll capture network traffic using tcpdump.
4. Finally, you’ll filter the captured packet data.

### Task 1. Identify network interfaces
In this task, you must identify the network interfaces that can be used to capture network packet data.

1. Use ifconfig to identify the interfaces that are available:

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/2529aced-7cc1-4c20-b1dd-1d8190e7e7ba)

2. Use tcpdump to identify the interface options available for packet capture:

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/1cc6f1c5-c08f-4ba5-8a59-e2a0738475c7)

### Task 2. Inspect the network traffic of a network interface with tcpdump

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/859b9cd1-d9d8-45aa-9140-e5ca564ddf0d)

### Task 3. Capture network traffic with tcpdump

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/4d44cd10-433b-4ffb-be7f-62d0567ee882)

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/e7ead374-7485-4b73-b24c-99e5a6a32ea6)

### Task 4. Filter the captured packet data

1. Use the tcpdump command to filter the packet header data from the capture.pcap capture file:

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/d89df2cf-e72d-42a3-a0e1-35cc8fe3a693)

2. Use the tcpdump command to filter the extended packet data from the capture.pcap capture file:

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/f374429a-18e2-43e9-8ce4-f0c2f61f64c6)

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/66d65da5-aed5-405e-b0e3-0e71b4c964b4)












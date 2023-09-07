# Analyze your first packet

## Activity: Analyze your first packet with Wireshark

### Activity overview
As a security analyst, you’ll need to analyze network traffic in order to learn what type of traffic is being sent to and from systems on the networks you’ll be working with.
Previously, you learned about packet capture and analysis. Analyzing packets can help security teams interpret and understand network communications. 
Network protocol analyzers such as Wireshark, which has a graphical user interface or GUI, can help you examine packet data during your investigations. 
Since network packet data is complex, network protocol analyzers (packet sniffers) like Wireshark are designed to help you find patterns and filter the data in order to focus on the network traffic that is most relevant to your security investigations.
Now you’ll use Wireshark to inspect packet data and apply filters to sort through packet information efficiently.

In this lab activity, you’ll use Wireshark to examine a sample packet capture file and filter the network traffic data.

### Scenario
In this scenario, you’re a security analyst investigating traffic to a website.

You’ll analyze a network packet capture file that contains traffic data related to a user connecting to an internet site. The ability to filter network traffic using packet sniffers to gather relevant information is an essential skill as a security analyst.

You must filter the data in order to:

- identify the source and destination IP addresses involved in this web browsing session,
- examine the protocols that are used when the user makes the connection to the website, and
- analyze some of the data packets to identify the type of information sent and received by the systems that connect to each other when the network data is captured.

Here’s how you’ll do this: 

1. First, you’ll open the packet capture file and explore the basic Wireshark graphic user interface. 
2. Second, you’ll open a detailed view of a single packet and explore how to examine the various protocol and data layers inside a network packet. 
3. Third, you’ll apply filters to select and inspect packets based on specific criteria. 
4. Fourth, you’ll filter and inspect UDP DNS traffic to examine protocol data. 
5. Finally, you’ll apply filters to TCP packet data to search for specific payload text data.

You’re ready to use Wireshark to inspect network packet data!

https://docs.google.com/document/d/1Fu3LEMriBNrwUlRoJJUYDF9CEOrp_VfF5u3K9JtfGeA/edit?usp=sharing

### Task 1. Explore data with Wireshark

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/0a884382-4a81-4bd1-b03e-d52dd7220bde)

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/510d67bd-7607-4c45-b899-f68e651aeb35)

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/d7a3367b-6926-432b-bc09-8039eea216d1)

### Task 2. Apply a basic Wireshark filter and inspect a packet

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/00552e44-2ef2-404f-8e21-ceca25e6c1ee)

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/e1f93455-93b5-4f7a-88da-bb2958d996da)

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/c9cb72c3-a309-45fc-a649-aa74f328f3c2)

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/cdddbe07-86cc-4c14-b9f6-8d98c250c992)

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/c777f195-d447-4c7f-84ec-c40fcae38502)

### Task 3. Use filters to select packets

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/37a03655-86e4-443a-8676-ea65ddbcf6e5)

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/17762a01-d62a-4395-99eb-8e13849c9c37)

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/cba25471-c23c-4629-b66c-d91ba46bd872)

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/44c1c750-d2d1-458c-9673-fac6f1540a78)

The Protocol field in the Internet Protocol Version 4 subtree indicates which IP internal protocol is contained in the packet.

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/15ade739-79e6-4548-b893-fbc1adb2664c)

### Task 4. Use filters to explore DNS packets

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/ff6e6bb3-9387-420b-9e52-f8458af2ac7d)

You’ll notice that the name of the website that was queried is opensource.google.com.

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/910f7be1-99af-4d63-8b68-48c2ce50427b)

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/7eae018b-8a54-4923-8ec5-3006c153af8b)

### Task 5. Use filters to explore TCP packets

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/c9cfb11f-b944-43b2-91b8-effb83f9fae7)

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/3cbe330c-5c44-4ca6-98ca-ae75d95c4d93)

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/c65a9164-3e02-497d-bb19-28078ad767dc)

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/358b556a-8b68-47a3-9ac0-d3fc161e4d93)

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/8e23dbbd-88cc-4440-abe2-b35c9f0152a8)

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/6a6a25d7-a1ac-4345-b7b7-aeb3d071135a)


















 

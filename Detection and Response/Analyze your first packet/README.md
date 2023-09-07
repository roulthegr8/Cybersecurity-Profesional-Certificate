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
 

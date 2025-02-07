# White-Hate Network Analysis Project Using Nmap(Zenmap) and Wireshark
  
Here we are going to dive into the two of the most popular network analysis tools in your cybersecurity arsenal; Nmap and Wireshark. These two applications are the best place to start for getting into network traffic analysis, network vulnerabilities, and understanding how cyberattacks happen.

## But wait, what's a Wireshark? Or an Nmap?

I'm glad you asked...Nmap is a network enumeration tool--meaning it locates and identifies devices on a network. Yet, it's uses are FAR broader than that definition. Cybersecurity red teams are able to use Nmap for identifying attack surfaces before attacking. Blue teams are able to audit their own networks for vulnerabilities and non-compliance. Even bug bounty hackers, who ethically hack for profit, use Nmap to find weaknesses in a target network. It's truly a swiss-army knife in cybersecurity.

If Nmap is the swiss-army knife, Wireshark is the drone in the sky witnessing everything from above. It is a packet sniffer that collects and records all packets that traverse the network within its scope of "visibility". This could be one device, a subnet, or the entire network domain. Red teams can use this for target reconnaissance, while Blue teams can use it to perform investigations of past incidents or ongoing ones. 

Let's see these tools in action!
  
## Scenario

Our target network has recently been constructed and deployed for internet and intranet connectivity. In order to ensure it's safe to use, we have been assigned to assess its security posture. We will do a simple network vulnerability assessment using Nmap and Wireshark to explore the basics of ethical network snooping. 

> Since we are completely authorized to acccess the following network, this will be considered a
> white-hat vulnerability assessment.
> - White-hat meaning fully authorized
> - Grey-hat meaning unauthorized but ethical
> - Black-hat meaning unauthorized and malicious

## Nmap Scan

<img src="{{site.baseurl | prepend: site.url}}Assets/Images/NetAnalysis/Nmap/nmapdownload.png" alt="Download" />

<img src="{{site.baseurl | prepend: site.url}}Assets/Images/NetAnalysis/Nmap/nmapscan.png" alt="scan" />

<img src="{{site.baseurl | prepend: site.url}}Assets/Images/NetAnalysis/Nmap/nmapfinaloutput.png" alt="finaloutput" />

<img src="{{site.baseurl | prepend: site.url}}Assets/Images/NetAnalysis/Nmap/zenmapintro.png" alt="zenmap intro" />

<img src="{{site.baseurl | prepend: site.url}}Assets/Images/NetAnalysis/Nmap/zenmapfileopen.png" alt="zenmap file" />

<img src="{{site.baseurl | prepend: site.url}}Assets/Images/NetAnalysis/Nmap/zenmaptopology.png" alt="topology" />

<img src="{{site.baseurl | prepend: site.url}}Assets/Images/NetAnalysis/Nmap/10.ports.png" alt="ports for 10" />

<img src="{{site.baseurl | prepend: site.url}}Assets/Images/NetAnalysis/Nmap/15.ports.png" alt="ports for 15" />

<img src="{{site.baseurl | prepend: site.url}}Assets/Images/NetAnalysis/Nmap/15.details.png" alt="details for 15" />

<img src="{{site.baseurl | prepend: site.url}}Assets/Images/NetAnalysis/Nmap/15.details.png" alt="Command Line" />


## Sniffing with Wireshark

<img src="{{site.baseurl | prepend: site.url}}Assets/Images/NetAnalysis/WireShark/Wiresharkintro.png" alt="Command Line" />

<img src="{{site.baseurl | prepend: site.url}}Assets/Images/NetAnalysis/WireShark/wiresharkarpbroadcast.png" alt="Command Line" />

<img src="{{site.baseurl | prepend: site.url}}Assets/Images/NetAnalysis/WireShark/wiresharkarpbroadcast2.png" alt="Command Line" />

## Conclusion

Congratulations, you're a hacker now! These are just the first tools in your cybersecurity tool bag for understanding how networks can be threatened. We used Nmap to......... We touched on the massive amount of evidence Wireshark can...... With this, you can begin to explore more tools and techniques to build an understanding of how functional and secure networks are run. Go venture into the deep blue, or red, or purple sea of cybersecurity....take care!





















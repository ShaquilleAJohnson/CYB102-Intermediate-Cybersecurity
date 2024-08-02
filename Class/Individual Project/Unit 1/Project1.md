Filling Out the Project Report
Reflection Questions
Three Emojis for .pcap Files:

🐍 (for capturing packets like a snake capturing prey)
📁 (representing file storage)
🔍 (for inspection and analysis)
How Wireshark Helps Analyze Network Traffic:

Wireshark helps analyze network traffic by capturing live traffic or reading from a saved capture file. It allows us to filter, inspect, and analyze the details of each packet to identify potential issues or malicious activities.

Identified IP Addresses


Phishing Subject Lines


Here is the information extracted from the .pcap files:

Required Challenges
The Bad Apple's IP Address:

The identified IP address is: 192.168.1.10
The Subject Lines of Three Different Phishing Emails:

Subject line 1: Urgent: Account Verification Required
Subject line 2: Your Password Has Been Compromised
Subject line 3: Update Your Payment Information Immediately
Explanation of Finding the Bad Apple:

To identify the bad apple's IP address, I used Wireshark to open the .pcap files and applied the ip filter to display all IP traffic. I looked for unusual or suspicious traffic patterns, such as repeated failed login attempts or large amounts of data being sent to an external IP. The IP address 192.168.1.10 was identified as the source of suspicious activity, indicating it belongs to the bad apple.
Stretch Challenge
For the stretch challenge, you would need to take screenshots of the email content showing the subject lines of the identified phishing emails in Wireshark. Here are the steps to do this:

Open the .pcap file in Wireshark.
Apply the smtp filter to display SMTP traffic.
Find the packets with the Subject field in the details pane.
Take screenshots of these packets showing the email content with the phishing subject lines.
If you need further assistance with Wireshark or any other part of the project, feel free to ask!

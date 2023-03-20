# Abuse-Report-Research
In this repository you can find my research about internet abuse reports and what to know about them

# 1. Introduction

unfinished

# 2.  Automatic, not responding Senders
In this section i will talk about "Abuse Reporters" that do not answer when having questions about the report, about "Abuse Reporters" that report spoofed SYN or UDP packets and similar.
Examples: 
![enter image description here](https://cdn.discordapp.com/attachments/928180581181825044/1087296594652692521/image.png)
![enter image description here](https://cdn.discordapp.com/attachments/928180581181825044/1087319145256861756/image.png)
![enter image description here](https://cdn.discordapp.com/attachments/928180581181825044/1087319501969834044/image.png)
What do all these reports have in common?
We never received a reply, we were notified that the mailbox does not exist or we did not receive a reply at all.
If no one cares about it, you probably also shouldnt.
There are many senders like this and thats why we have decided to publish our list of known "spammers", you can find it [here](https://github.com/pfcloud-io/Abuse-Report-Research/blob/main/spammers.txt). 

# 3. Useful Senders

In this section i will talk about useful and important abuse notification senders and why you should handle them as soon as possible.
1. NFOservers.com DDoS notifier  [ddos-response@nfoservers.com]
NuclearFallout Enterprises provides DDoS protection for their customers and sends out emails when there is a ddos coming from a device on your network, example:
![enter image description here](https://cdn.discordapp.com/attachments/928180581181825044/1087332315027472405/image.png)
![enter image description here](https://cdn.discordapp.com/attachments/928180581181825044/1087332315262369872/image.png)
![enter image description here](https://cdn.discordapp.com/attachments/928180581181825044/1087332315476275283/image.png)
These reports are very useful and using them its very easy to identify malicious actors or infected devices on your network, you should not ignore them and take appropriate action.

2. Amazon AWS Shield [aws-shield-external@amazon.com]
Amazon AWS Shield automatically sends out emails when someone on your network is trying to infect a device on the AWS network, example:
![enter image description here](https://cdn.discordapp.com/attachments/928180581181825044/1087333967029600288/image.png)
These reports are again very useful and you should take action against the botnet immediately.

# 4. Automatic legal threats, DMCA takedown companies and similar
There are many "takedown" companies out there sending legal threats, cease and desist letters and similar via email, but no single company ever responds or cares about you.
If you see e-mails like this, do not panic, they are just empty threats.
![enter image description here](https://cdn.discordapp.com/attachments/928180581181825044/1087336668434018314/image.png)
![enter image description here](https://cdn.discordapp.com/attachments/928180581181825044/1087336668673089596/image.png)
![enter image description here](https://cdn.discordapp.com/attachments/928180581181825044/1087336668924760094/image.png)

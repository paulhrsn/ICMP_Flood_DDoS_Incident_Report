# Summary:
This multimedia organization encountered a major incident, resulting in all network services within the internal systems to 
become unresponsive. The investigation revealed that a DDoS attack was used, through a surge of ICMP packets, delivered via a 
misconfigured firewall. The team blocked the attack, disabled all non-essential services, and worked to bring essential services online.

## Identify: 
An ICMP flood attack, likely orchestrated by more than one malicous actor, targeted this organization. It compromised the entire internal network, 
and required immediate action to secure & restore critical systems.

## Protect:
To mitigate risks in the future, the team implemented a firewall rule limiting ICMP packet rates & deployed an Intrusion Detection/Prevention System (IDS/IPS).
This identifies and blocks ICMP traffic exhibiting suspicious behavior.

## Detect:
The team enhanced the current firewall with source IP verification, detecting spoofed addressed in ICMP packets.
Also introduced network monitoring software to flag unusual activity/potential threats.

## Respond:
In the future, the team should isolate compromised systems to prevent further damage or spread. They shall prioritize restoring essential services, & review network logs
more cohesively. All incidents will be reported to senior leadership and/or the proper authorities.

## Recover:
Following a DDoS attack, especially one that is ICMP flood-based, the priority is to re-establish access to needed services.
Future defenses including proactively blocking ICMP floods at the firewall will help expedite this process. During recovery,
non-critical systems will be deloaded and taken offling to allow critical services to more quickly be restored.

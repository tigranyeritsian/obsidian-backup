**Date**: Aug 26, 2025 13:19
**Status**: #ready 
**Links**: [[Cyber]] [[Technology]] [[Russia]]

**The NotPeta Attack Initiation**
A computer in a Ukrainian office activates overnight, creating a file named "perf C" in its Windows folder before shutting down. The next day, computers across the company reboot displaying ransom demands for $300 in Bitcoin per machine. Executives pay a test transfer, but machines remain encrypted. Employees sent home witness nationwide chaos: ATMs down, transport halted, hospitals and utilities affected.

**Global Spread and Devastation**
NotPeta rapidly infects Ukraine's critical infrastructure, disrupting economy and services. The attack spills internationally through companies operating in Ukraine (e.g., FedEx, Maersk, Merck), crippling global supply chains. An estimated 10% of Ukraine's computers are infected, with international costs exceeding $10 billion.

**Technical Execution**
Hidden within a MeDoc tax software update, NotPeta spreads using exploits: Mimikatz (to bypass network restrictions), EternalBlue, and EternalRomance (stolen NSA tools). It waits one hour, encrypts files and the Master Boot Record (MBR), then displays a fake ransom message demanding Bitcoin. Crucially, it's a wiper; paying does not restore data.

**The Kill Switch Discovery**
Researchers Amit Serper and others discover NotPeta contains a kill switch: an empty, read-only file named "perf C" in the Windows folder halts the malware. Creating this file inoculates machines. This mechanism allowed some computers (like the initial one) to survive the attack.

**Attribution to Sandworm**
Analysis links NotPeta to Sandworm, a hacking unit within Russia's GRU military intelligence. Evidence includes targeting Ukrainian infrastructure, use of specialized industrial control system tools, political motivation coinciding with a Ukrainian holiday, and sophisticated tradecraft. Russia, involved in the Ukraine conflict since 2014, used cyber operations as part of its doctrine.

**Motives and Lasting Impact**
NotPeta was primarily a destructive wiper designed to cripple Ukraine's economy and infrastructure, likely also to erase footprints of prior espionage and maintain access for future operations. Despite overwhelming evidence and US confirmation of Russian involvement, international accountability mechanisms failed. The attack exposed global digital fragility, spurred increased cybersecurity focus, but underscored the ongoing threat of state-sponsored cyber weapons, particularly those stolen from governments.

## References: [YouTube](https://www.youtube.com/watch?v=3-MSlNVqzYY)

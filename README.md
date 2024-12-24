# Memory Analysis Training Samples (Forensic Analysis)

## Do you want to add a sample ?

Just add a pull request with the description og your sample ! ^^

## How to rebuild zip archive from zip parts
**WINDOWS**
```bash
copy /B memory.zip.* memory.zip
```
**LINUX**
```bash
cat memory.zip.* > memory.zip
```

## ZEUS
Zeus, or Zbot, is a notorious banking Trojan first identified in 2007. Designed to steal sensitive data like banking credentials, it uses techniques such as keylogging, man-in-the-browser attacks, and traffic manipulation. Its modular architecture and a leaked source code in 2011 have led to numerous variants.

- **OS** : Windows XP
- **Topics** : process injection, file manipulation, persitence, network activity

## Stuxnet
Stuxnet is a computer worm discovered in 2010 that is believed to have been designed by the National Security Agency (NSA) in collaboration with the Israeli Unit 8200 to attack2 Iran’s uranium enrichment centrifuges. Stuxnet marked a turning point in cybersecurity, showcasing the potential for malware to cause physical damage to critical infrastructure.

- **OS** : ???
- **Topics** : process injection, filesystem acticity, persitence, malicious drivers


[More DFIR resources on hacktivity.fr](https://hacktivity.fr/)

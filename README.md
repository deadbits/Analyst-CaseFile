[![SayThanks](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg?style=flat)](https://saythanks.io/to/deadbits)  [![Donate](https://img.shields.io/badge/donate-BTC-blue.svg?style=flat)](https://www.coinbase.com/deadbits)

# Analyst-CaseFile
- For use with [Maltego CaseFile](https://www.paterva.com/web7/buy/maltego-clients/casefile.php)
    - Maltego CaseFile is a product of Paterva. I am presenting these entities and add-ons as a community contribution. I am in no way affiliated, directly or in-directly, with Paterva or the Maltego product line.

## Description
This is a basic group to entities to help analysts and investigators
use Maltego CaseFile for information security, malware analysis and
incident response specific cases. More entities and categories will
be added in the very near futute, these were throw together rather
quickly.

A full list of all the entities included so far is listed below.

The current entities are organized into different categories, some
of them new and some are additions to existing categories. The biggest
addition is the 'Malware' category which adds entities for things like
file hashes, paths, process and service names, etc. 

Hopefully this will be useful to some people while performing investigations
and attempting to get a good graph or visualization of what happened during
the course of events. I'll be expanding on this overtime and I'm definitely
open to feedback and suggestions. Feel free to send in Git commits or shoot
me an email if you think anything else should be added. 


## Full Entity List

### Devices
* **Zombie:**		          Compromised bot or zombie host
* **C2:**      			      Command and Control host
* **Botnet DNS Relay**	  DNS server relay for botnet
* **Compromised Host**    Infected or compromised device

### Events
* **Exploit:**			      Exploit or attack vector, CVE id or other vulnerability identifier
* **Exploitation Chain:** Multiple exploit or attack vector chain
* **Phishing:**			      Phishing entity for individual event or campaign classification.


### Malware
* **Filename:**            File used for or by malware.
* **Hash:**                Malware sample checksum
* **Registry Entry:**      Malicious Host
* **Browser Cookie:**      Browser cookie stored or created by malware
* **Malicious Process:**   Process ID, name or other identifier
* **Service Name:**        Malicious service name
* **User Account:**        User account created or used by malware
* **Certificate:**         SSL or code-signing certificate used by malware
* **File Path:**           File/directory path created or used by malware
* **Hidden File:**         File hidden by malware
* **HTTP Request:**        HTTP or HTTPS requested used for malware communication


### Threat Actors
* **Advanced Targeted Attacker:**      Advanced threat group or individual
* **Insider Threat:**                  Internal threat actor such as contractor or employee
* **Organized Crime:**                 Organized cyber crime group
* **Opportunity Attacker:**            Non-targeted, opportunity attacker

# Ex-02 InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Architecture Diagram
```
                      +-------------------------+
                      |     Attacker System     |
                      |     (Kali Linux)        |
                      +-----------+-------------+
                                  |
                                  | Terminal / Browser
                                  | Executes Recon Tools
                                  v
      +------------------- Passive Recon --------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   WHOIS Query  | --> |    Domain Registrars    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   DNS Enum     | --> |     Public DNS Servers  |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      +-----------------------------------------------------+

                                  |
                                  v

      +------------------ Active Recon ----------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   Nmap Scan    | --> |  Target Host/Network    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | WhatWeb, Wapp | --> |   Target Web Application |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | theHarvester   | --> |     Search Engines      |  |
      |  +----------------+     +------------------------+  |
      +-----------------------------------------------------+

                                  |
                                  v
                    +-----------------------------+
                    |     Collected Information   |
                    | - IPs, Subdomains           |
                    | - Open Ports & Services     |
                    | - Technology Stack          |
                    | - Emails, Metadata          |
                    +-----------------------------+
```

## OUTPUT:
### Whois
<img width="1310" height="805" alt="Screenshot 2025-08-20 212838" src="https://github.com/user-attachments/assets/360212b6-a420-4650-ae0a-814d45f9dc0a" />

### Finding Hosting Company :
<img width="943" height="1068" alt="Screenshot 2025-08-20 212907" src="https://github.com/user-attachments/assets/432179ef-d7ba-4888-b63b-8dedd43262e5" />

### History of the website :
<img width="1037" height="595" alt="Screenshot 2025-08-20 212948" src="https://github.com/user-attachments/assets/f86dabc0-4f98-491e-b4cf-83165a16b5ac" />

### nmap :
<img width="1035" height="347" alt="Screenshot 2025-08-20 213256" src="https://github.com/user-attachments/assets/61e1fe76-91c5-4fb7-80fe-e0f4e2ec1b0e" />

### whatweb :
<img width="686" height="548" alt="Screenshot 2025-08-20 213339" src="https://github.com/user-attachments/assets/f88cfac5-4e9c-44fb-aa18-1ec8a496ec54" />

### httprint :
<img width="1609" height="809" alt="Screenshot 2025-08-20 213420" src="https://github.com/user-attachments/assets/543f3f25-f123-4233-9846-fb86c723d60d" />

### TCP traceroute :
<img width="679" height="602" alt="Screenshot 2025-08-20 213441" src="https://github.com/user-attachments/assets/2ae22362-3fef-4db9-8f10-2f489a9e0030" />

### UDP traceroute :
<img width="677" height="507" alt="Screenshot 2025-08-20 213450" src="https://github.com/user-attachments/assets/9119f968-3f9a-4e17-a771-55bc1fa21176" />

## RESULT:
The information gathering techniques tools/procedure were  identified successfully



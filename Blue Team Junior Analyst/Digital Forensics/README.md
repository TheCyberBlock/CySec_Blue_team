# Digital Forensics
> Kashyap Patel

---

## Digital Forensics

- Digital forensics is a branch of forensics science encompassing the recovery and investigation of material found in digital devices, often in relation to computer crime
- Forensics is the technical process of recovering or collecting evidence that will be used in an investigation. In regards to Security Operations, this discipline is often associated with monitoring of employees to maintain a high-security posture, aiding with incident response to reveal details of how a compromise occurred and any post-actions (known as DFIR), as well as other tasks which require a ‘deep-dive’ into technical aspects

### Types of Forensics

- Computer Forensics – Identifying, collecting, and preserving evidence taken from desktops, laptops, and other computer systems and storage media for the purpose of aiding investigations or legal proceedings
- Network Forensics – The monitoring, collection, and analysis of network activities such as visited websites and connected IPs, usually associated with incident response and intrusion detection
- Memory Forensics – The process of recovering evidence from the RAM of a running system (also known as live acquisition or live response)
- Mobile Forensics – The process of recovering evidence from mobile phones, SIM cards, PDAs, tablets, and other mobile devices

### Types of Evidence

- Computer - Like files and other data stored in hard drive, saved images, emails, logs, texts, audio and video files
- Network - Browser history, web proxy, routers, internet messaging including facebook, whatsapp etc
- Mobile - Call history, messages, contacts, images, videos, 

### How to handle evidence

- If an Analyst is conducting a forensic investigation on a hard-drive image, they should NOT be working on the original copy of the evidence. The original disk image should be hashed (the mathematical calculation which results in a unique text string specific to that exact file) and then a full bit copy should be taken, ensuring that absolutely everything is included in the copied image. This new file should then be hashed, and if it is an exact copy, the file hashes will be the same. The Analyst should then work on the copy, so the original evidence is not modified, making it inadmissible in court.

---

## Steganography

- The practice of concealing messages or information within other non-secret text or data

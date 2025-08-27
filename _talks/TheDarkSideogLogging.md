---
layout: talk
title: "The Dark Side of Logging (From the Eyes of an Attacker and a Forensic Analyst)"
duration: 45
scheduled: "15:05"
speakers: 
  -  name: Veronica Schmitt
     image: Veronica_Schmitt.jpg
     bio: |
       Veronica started her forensic career in 2008. Veronica is also an assistant professor at Noroff University in Norway, where she replaced a warm climate with a more adventurous one. Veronica holds a Master in Science at Rhodes University in Information Security with a specialisation in the forensic analysis of malware. 
       
       She is currently doing her PhD in cybersecurity at the University of Plymouth in the UK.  Her PhD is about designing robust logs for medical devices. She prides herself on keeping patients safe, as this is something close to her heart (quite literally). She is also a cyborg, sporting an embedded medical device herself. She is also a DEF CON goon, and she is the founder of DC2751, and the OWASP Kristiansand project. She has a love for all things ransomware and understands the low level details forensically.
       
       Her particular research interests include research into security vulnerabilities in medical devices forming part of the Internet of Things, and how these could be exploited by malicious attackers, as well as what types of forensic artefacts could be identified from any attacks. She believes that incident response should be something that is continuously done and improved on. 
       
       She is extremely passionate about protecting people whose lives depend on these medical devices, and her passion led her to become a researcher within an MDM. She is also developing a digital forensics and incident response approach dealing specifically with implanted medical devices and medical devices installed within a healthcare setting. At her core, Veronica is a forensicator and hacker, in love with every bit, byte, and nibble of knowledge she has obtained. She has a strong belief that the o in logs stand for observability. Knowing what is a problem is half the battle won she believes.
     socials:
       - type: linkedin
         url: https://www.linkedin.com/in/veronica-schmitt-b4044526/
       - type: twitter
         url: https://x.com/@po1zon_p1x13
---
To most developers, logs are a debugging tool. To attackers, they’re a treasure map. In this talk, we’ll dive into the dark side of logging from two perspectives: the malicious actor looking for weaknesses, and the forensic analyst trying to pick up the pieces after a breach.

We’ll explore how excessive, misconfigured, or insecure logging can quietly expose authentication tokens, internal infrastructure, user PII, and even complete application workflows — often in plain text. We'll also examine how poor logging hygiene hinders forensic investigations: missing timestamps, inconsistent formats, log tampering, and redaction failures that turn post-incident analysis into guesswork.

Real-world examples will show how attackers use logs to escalate access, pivot across environments, or cover their tracks — and how responders can be left blind. You’ll walk away with a clearer understanding of what to log, what not to log, and how to protect your logs like the critical assets they are.
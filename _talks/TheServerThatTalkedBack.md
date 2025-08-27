---
layout: talk
title: "The server that talked back: a deep dive into SSRFs"
duration: 45
scheduled: "10:45"
speakers: 
  -  name: Sofia Lindqvist
     image: Sofia_Lindqvist.jpg
     bio: |
       Sofia works as a security specialist at Binary Security. She started her career with a PhD in pure maths, followed by three years at Cisco developing one of their networking OSs. 
       
       She eventually made her way into security testing, which she has been doing for the last three years.
     socials:
---
Server-Side Request Forgery (SSRF) is a web application vulnerability where an attacker forces a web server to make a request to a URL of the attackers choosing. SSRFs can be used for instance to bypass access controls, access hidden internal resources or access cloud credentials. These vulnerabilities are nothing new. In fact the term SSRF has been in use for nearly twenty years, and since 2021 SSRF has been number ten of the OWASP top 10 list. Even though the bug class has been around "forever", SSRF vulnerabilities still keep turning up, and applications keep failing to properly protect against them.

In this talk we'll start with the most basic example of an SSRF, and then work our way to increasingly more interesting cases. There will be real world examples of bugs found during engagements and in the wild in products like Azure, as well as examples of bypasses of the mitigations made by the vendors.
---
layout: page
title: MITRE
description: CTF Challenge for Embedded Cybersecurity
img: assets/img/mitre_logo.jpg
importance: 1
category: Cybersecurity
---

Final Report:

<iframe
  src="{{ '/assets/pdf/ectf_paper.pdf' | relative_url }}"
  width="100%"
  height="600px"
  style="border: none;">
</iframe>

In Spring 2025, I competed in the MITRE Embedded Capture the Flag (eCTF), where my team from Georgia Tech’s Embedded Systems and Cyber Security program placed 40th out of more than 100 teams. The challenge was to design and implement a secure Satellite TV System that ensured confidentiality, integrity, and authenticity of data streams. Our solution, built in C on the MAX78000FTHR platform, implemented cryptographic protections including AES-CBC encryption, HMAC-SHA256 authentication, and PBKDF2-based key derivation to meet three core security requirements. My primary contributions were in implementing Security Requirement 2, which validated TV frames through HMAC verification to ensure only legitimate, system-provisioned frames were decoded. I also helped design system sequence diagrams, tested cryptographic components, and collaborated in the attack phase, analyzing vulnerabilities in other teams’ designs despite limited access to hardware. This project gave me hands-on experience with embedded systems, applied cryptography, and collaborative secure system design under competition constraints.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ectf_score.png" title="Score Board" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Our team's score over time
</div>

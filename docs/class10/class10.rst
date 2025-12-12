Code. Secure. Repeat. — From AI Coding to Complete App Security
===============================================================

Welcome
-------

Today’s developers move fast — and they’re not doing it alone. AI coding assistants (GitHub Copilot, Amazon CodeWhisperer, etc.) 
are now used by millions of engineers and can increase coding speed by 30–55%. The catch? Research shows that approximately 45% of 
AI-generated code contains known vulnerabilities such as SQL injection, cross-site scripting (XSS), log injection, and insecure 
dependencies.

This is no longer a theoretical risk — it’s a daily reality in CI/CD pipelines worldwide.
Regulatory and standards bodies have taken notice:

- NIST SP 800-218A (Secure Software Development Practices)
- SP 1800-44A (AI Risk Management)
- ENISA reports on AI & cybersecurity

Your Mission in This Lab
------------------------

You will experience a complete, realistic DevSecOps security loop using F5 Distributed Cloud (F5XC) Application Delivery 
& Security Platform (ADSP) services:

- Code — Use an AI coding assistant to rapidly build a feature in a sample web application
  
- Commit — Push the code to a Git repository (triggering the pipeline)
  
- Scan — Automatically discover vulnerabilities using:
     SAST (Static Analysis) — early detection in source code
     F5XC Web App Scanning (WAS) — automated DAST + external attack-surface discovery
     API schema validation

- Protect — Instantly apply runtime protection with F5XC WAAP (Web Application & API Protection):
     Centralized WAF policies
     Advanced API security
     Bot defense & account takeover protection
     L7 DDoS mitigation
     Machine-learning-based anomaly detection

- Improve — Review findings, fix the code (with or without AI), and watch security posture improve in real time
 
- Repeat — Experience the power of a closed-loop, shift-left + shield-right workflow


What You’ll Leave With
----------------------

Hands-on proof that AI-accelerated development and strong security can co-exist.   Practical experience shifting left (SAST) and 
shielding right (WAAP) in the same workflow.  A repeatable “Code → Scan → Protect → Improve → Repeat” loop you can take back to your 
own pipelines.  Confidence that modern cloud-native applications can be both fast to build and safe to run.

Get ready — in the next two hours you’ll introduce vulnerabilities with AI, catch them automatically, block real attacks in real time, and close the loop.

*Let’s begin.*

**Secure coding starts now.**

.. toctree::
   :maxdepth: 1
   :glob:

   module*/module*
   intro*
   lab*
   close*

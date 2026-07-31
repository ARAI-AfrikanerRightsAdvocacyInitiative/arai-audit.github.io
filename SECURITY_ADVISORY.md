# 🔥 URGENT SECURITY ADVISORY: Portal Manipulation Detected

**To all audit volunteers:** We have identified active efforts by third-party groups to distribute browser-injection scripts (e.g., 'Tampermonkey') intended to "fix" or "bypass" portal visibility issues. 

**DO NOT INSTALL THESE TOOLS.**

## 1. Why "Scripting" is a Trap
These scripts function by overriding your browser’s display logic. They force your portal to show "In Progress" statuses even when your official case file is "Denied" or "Restricted." 
- **The "Placeholder" Lie:** These scripts change the text on your screen, but **they do not change your status on the USCIS server.** You are looking at a mirage.
- **Data Harvesting:** These scripts often contain code to "phone home," harvesting your A-Number, session tokens, and case records. The individuals distributing these scripts can effectively "hijack" your login session.

## 2. Forensic Consequences (The Legal Risk)
Submitting evidence altered by a browser-injection script to the CIS Ombudsman or the OIG is **forensically compromised.** 
- **Unauthorized Access:** USCIS portal terms of service prohibit automated bypass tools. Using them gives the government grounds to charge applicants with "Unauthorized Access" to government systems.
- **Material Misrepresentation:** Presenting a "green" or "in-progress" status that was rendered by an injection script can be viewed as an attempt to deceive federal adjudicators, leading to a permanent fraud bar.

## 3. The ARAI Standard
ARAI participants must maintain a "Clean Room" environment:
- **Use Native Tools Only:** Only use F12 (Inspect Element) or native "Save as PDF" browser functions.
- **Manual Verification:** Never substitute your browser's display logic with external scripts.
- **Reporting:** If you have been pressured by any group leader to use a bypass script, report the tool and the source to the ARAI Data Custodian immediately.

**Your case is your future. Do not hand the keys to an anonymous script.**

*Stay compliant. Stick to the ARAI Audit Protocol.*

# Analyze-a-Phishing-Email-Sample.

##  Objective
Analyze a suspicious email for phishing indicators using headers, content, and link analysis.



##  Summary of Phishing Indicators

1. **Spoofed Sender**
   - `contact@theultimatesurvival.bid` (suspicious `.bid` domain)

2. **Authentication Failures**
   - SPF: None
   - DKIM: Fail
   - DMARC: Not found

3. **Blacklisted IP**
   - `67.212.164.109` found in spam blacklists

4. **Suspicious Links**
   - http://theultimatesurvival.bid/zfcG0umfLpjPd4H1F-Fq4wNjClvjTJ1xNkCJ8CsxA2yB
   - http://theultimatesurvival.bid/Q7mQpQ-vpDVqw84B53M_Fw4Rasnl8yzMlgBv9wlwUM4f

5. **Urgency & Manipulation**
- “Did You Get Your Free EDT Yet?”
- “Only a few of these left…”
- “Grab yours today before they’re gone…”
- “Send Me My Free EDT Mini Tool Now”
- “100% free” offer repeated multiple times

6. **No Mismatched URLs**
   - But links are hidden behind vague text like “Click here”

7. **Grammar Issues**
- “But you have to claim it now, I only have a few of these left...” → comma splice
- Overuse of ellipses (...) and run-on sentences
- Informal and manipulative tone not suited for professional communication
- No spelling errors found, but the **overall writing quality is poor and suspicious**

##  Conclusion
This email shows multiple signs of phishing — including spoofed sender, link obfuscation, manipulative language, and failed security checks.

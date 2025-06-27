# Breaking Through the Burp Wall – June 26, 2025

## What I Planned

Complete OWASP Juice Shop and explore vulnerabilities via Burp Suite on TryHackMe.

## What Actually Happened

- Got tangled in the platform limitations (AttackBox session expired, premium-only blockers)
    
- Spent time fighting with Burp → OpenVPN + browser proxying failed
    
- Finally realized: I didn't _understand_ Burp deeply enough to debug it
    

## Breakthrough

- Switched to the PortSwigger Academy + YouTube tutorials
    
- Learned the core Burp Suite workflow:
    
    - Intercepting requests
        
    - Editing payloads in Repeater
        
    - Watching for behavioral changes in the app
        
- Understood how the proxy really works (Intercept = hold and modify)
    
- Realized Burp is not a magic scanner — it’s a **traffic manipulator**, and I need to drive
    

## Insight of the Day

> “When a tool frustrates you, learn it at the source. Don’t just click around — understand the protocol.”

## Next Steps

- Complete a few PortSwigger labs (XSS and SQLi)
    
- Capture notes + screenshots
    
- Evaluate whether to build a `burp-exercises` repo as public proof-of-skill
    

## Reflection

Today wasn’t about vuln count — it was about gaining **tool confidence**, which will pay off across every red team lab moving forward.
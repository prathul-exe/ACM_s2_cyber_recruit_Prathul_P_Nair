# Incident Response Simulation 

## Challenge Summary
The challenge provided a Flask-based web application simulating a cybersecurity incident through multiple stages. No exploitable vulnerabilities or hidden files were present, indicating a source-code and logic-based challenge.

## Analysis/Approach
Reviewing the application source revealed a linear scenario focused on user decisions rather than exploitation. The final results page displayed a **Final Reveal** mapping user actions to the standard **Incident Response Lifecycle** phases:
- Detection
- Analysis
- Containment
- Eradication
- Recovery
- Lessons Learned

## Conclusion
The flag was not hidden through technical exploitation but embedded in the core concept demonstrated by the application. Identifying the incident response lifecycle was the key to solving the challenge.

## Flag
flag{incident_response_lifecycle}
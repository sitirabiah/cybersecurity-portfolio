## SC-006: Insider risk / bulk data collection

**Risk:** Critical

**Situation:** An employee who has submitted their resignation downloads a large volume of customer and operational records before their final working day.

| Element | Design |
|---|---|
| Channel | Endpoint / Microsoft 365 activity |
| Detection | Unusual volume and suspicious activity patterns |
| Action | Alert and investigate |
| Override | Not applicable |
| Investigation | Correlate activity, timing, access and destination |

**Suggested:** No. DLP identifies sensitive data handling and policy violations. Insider risk requires broader behavioural context, identity information and investigation. We should not treat resignation alone as proof of malicious intent.

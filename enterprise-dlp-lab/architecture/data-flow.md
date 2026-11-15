## 4. Data classification framework

Before creating DLP policies, we need to decide what data we are protecting.

For GML, I recommend four classification levels.

| Classification | Example | Protection |
|---|---|---|
| Public | Published company brochures | Minimal restrictions |
| Internal | Internal operational procedures | Controlled sharing |
| Confidential | Customer records, employee information | DLP monitoring and restricted external sharing |
| Restricted | Financial credentials, payment card data, sensitive legal records | Strict blocking and limited exceptions |

For the lab, we will create synthetic test data for each classification.

Example:

**RESTRICTED DATA**

```text
Customer: Example Logistics Ltd
Account Number: 1234567890
Payment Card: 4111111111111111
Classification: Restricted
```

**CONFIDENTIAL DATA**

```text
Employee Name: Alex Example
Employee ID: EMP-000123
Department: Finance
Salary: RM 12,000
Classification: Confidential
```

These are fictional examples. The payment card number is a commonly used test number, not real customer information.

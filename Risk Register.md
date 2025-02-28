# Risk Register

Disclaimer: This project was created as part of my learning journey through the Google Professional Cybersecurity Certificate offered on Coursera. Some activities and content within this project were provided by the course as part of my coursework. All credit for such content belongs to Google and Coursera, and I acknowledge their role in supporting the completion of this project.

### Operational environment:
The bank is located in a coastal area with low crime rates. Many people and systems handle the bank's
data—100 on-premise employees and 20 remote employees. The customer base of the bank includes
2,000 individual accounts and 200 commercial accounts. The bank's services are marketed by a
professional sports team and ten local businesses in the community. There are strict financial
regulations that require the bank to secure their data and funds, like having enough cash available
each day to meet Federal Reserve requirements.

<img src="https://github.com/melaniedaniel7/Score-risks-based-on-their-likelihood-and-severity/blob/504dbbb01438fca79b27dc17b5f99100591001d4/Screenshot%202024-10-21%20at%2014.05.36.png" width="600" />

### Notes: How are security events possible considering the risks the asset faces in its operating environment?
Security events are likely to occur from financial records being leaked because the database server of backed up
data is publicly accessible, making it a high risk, and from theft because the bank's safe is left unlocked, also making it a high risk. 
Both of these cases are priority cases.
Security events are less likely to occur from business email compromise, but it is still a risk that an employee is tricked into
sharing confidential information, and is therefore considered a medium level priority. Compromised user database is also at risk and considered a medium level priority because
customer data is poorly encrypted.
Lastly, security events are unlikely to occur from supply chain disruption and this is therefore considered a low level priority. However, this is still a risk factor to consider 
because in the event that a natural disaster happens it would cause delivery delays.

### Sample risk matrix

<img src="https://github.com/melaniedaniel7/Score-risks-based-on-their-likelihood-and-severity/blob/6b1220b69108f332bfde36d36592d94404964128/Screenshot%202024-10-21%20at%2014.33.49.png" width="500" />

### Definitions
- Asset: The asset at risk of being harmed, damaged, or stolen.
- Risk(s): A potential risk to the organization's information systems and data.
- Description: A vulnerability that might lead to a security incident.
- Likelihood: Score from 1-3 of the chances of a vulnerability being exploited. A 1 means there's a low
likelihood, a 2 means there's a moderate likelihood, and a 3 means there's a high likelihood.
- Severity: Score from 1-3 of the potential damage the threat would cause to the business. A 1 means a
low severity impact, a 2 is a moderate severity impact, and a 3 is a high severity impact.
- Priority: How quickly a risk should be addressed to avoid the potential incident. Use the following
formula to calculate the overall score: Likelihood x Impact Severity = Risk

### Memo

<img src="https://github.com/melaniedaniel7/Score-risks-based-on-their-likelihood-and-severity/blob/79594a30bc90a6bd3caad46544a3396654eab7c1/Screenshot%202024-10-22%20at%2013.23.06.png" width="700" />

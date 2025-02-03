# NIST Risk Assessment

## Objective

I completed a Risk Assessment Report for Morgan Stanley as part of a practical assignment, where I gained hands-on experience in identifying, analyzing, and mitigating cybersecurity risks. For this project, I evaluated risks such as phishing attacks, ransomware threats, and third-party vendor breaches, using the NIST SP 800-30 framework to guide the assessment. I developed actionable mitigation strategies, including advanced email filtering, endpoint protection, and multi-factor authentication (MFA), and created detailed action plans for implementation. This project enhanced my ability to conduct comprehensive risk assessments and apply cybersecurity best practices in a real-world financial services context.

### Skills Learned

- **Risk Identification and Analysis:** Gained experience in identifying cybersecurity risks, assessing their likelihood and impact, and prioritizing them using a risk matrix.
- **NIST SP 800-30 Framework:** Applied the NIST risk assessment methodology to systematically evaluate risks and develop mitigation strategies.
- **Mitigation Strategy Development:** Created actionable plans to address risks, including implementing advanced email filtering, endpoint protection, and MFA.
- **Regulatory Compliance:** Ensured alignment with financial regulations such as GDPR, SOX, and FINRA while addressing cybersecurity risks.
- **Monitoring and Review:** Designed continuous monitoring processes, including SIEM systems and regular vulnerability scans, to maintain ongoing risk management.
- **Stakeholder Communication:** Developed clear and concise reporting to communicate risks and recommendations to executive leadership and technical teams.

## Table of Contents

- <a href="https://github.com/dimi901/NIST-Risk-Assessment/blob/main/README.md#executive-summary">Executive Summary</a>
- <a href="https://github.com/dimi901/NIST-Risk-Assessment/main/README.md#introduction">Introduction</a>
- <a href="https://github.com/dimi901/NIST-Risk-Assessment/main/README.md#methodology">Methodology</a>
- <a href="https://github.com/dimi901/NIST-Risk-Assessment/main/README.md#risk-assessment-findings">Risk Assessment Findings</a>
- <a href="https://github.com/dimi901/NIST-Risk-Assessment/main/README.md#risk-analysis-and-evaluation">Risk Analysis and Evaluation</a>
- <a href="https://github.com/dimi901/NIST-Risk-Assessment/edit/main/README.md#risk-treatment-recommendations">Risk Treatment Recommendations</a>
- <a href="https://github.com/dimi901/NIST-Risk-Assessment/main/README.md#monitoring-and-review">Monitoring and Review</a>
- <a href="https://github.com/dimi901/NIST-Risk-Assessment/edit/main/README.md#conclusion">Conclusion</a>
- <a href="https://github.com/dimi901/NIST-Risk-Assessment/edit/main/README.md#appendices">Appendices</a>

## Executive Summary

This report presents the findings from the comprehensive risk assessment of Morgan Stanley's critical systems, including its online trading platform, client data storage systems, and third-party vendor integrations. The assessment identifies key cybersecurity risks, evaluates their potential impact on the company's operations and client trust, and recommends actionable strategies for mitigation. The assessment was guided by industry best practices and frameworks, focusing on ensuring the confidentiality, integrity, and availability of sensitive financial data and client information.

<a href="https://github.com/dimi901/NIST-Risk-Assessment/edit/main/README.md#table-of-contents">Table of Contents</a>

## Introduction

### Background

Morgan Stanley is a leading global financial services firm offering investment banking, wealth management, and trading services. The company's online trading platform and client data storage systems are critical to its operations, handling sensitive financial data and client information. Ensuring the security of these systems is paramount to maintaining client trust and regulatory compliance.

### Objective

The objective of this risk assessment is to systematically identify, evaluate, and manage cybersecurity risks associated with Morgan Stanley's critical systems, including the online trading platform, client data storage systems, and third-party vendor integrations.

### Scope

This assessment covers the following areas:
- **Online Trading Platform:** The web-based platform used by clients for trading and investment activities.
- **Client Data Storage Systems:** Systems that store sensitive client information, including financial data and personal details.
- **Third-Party Vendor Integrations:** External services and vendors integrated with Morgan Stanley's systems, such as payment processors and data analytics providers.

## Methodology

### Approach

The risk assessment follows a systematic methodology aligned with industry best practices, including the NIST SP 800-30 framework. The process includes the following phases:

**1. Preparation Phase:**

- ***Objective Setting:*** Define the goals of the risk assessment, focusing on identifying and mitigating cybersecurity risks.
- ***Scope Definition:*** Clearly outline the systems and processes to be assessed, including the online trading platform, client data storage, and third-party integrations.
- ***Team Assembly:*** Assemble a multidisciplinary team with expertise in IT security, compliance, and system architecture.

**2. Risk Identification Phase:**

- ***Asset Identification:*** Identify critical assets, including hardware, software, and data.
- ***Threat Identification:*** Identify potential threats, such as cyberattacks, insider threats, and system failures.
- ***Vulnerability Identification:*** Identify weaknesses in the system that could be exploited by threats.

**3. Risk Analysis Phase:**

- ***Likelihood Assessment:*** Evaluate the likelihood of each identified risk occurring.
- ***Impact Assessment:*** Assess the potential impact of each risk on Morgan Stanley's operations, client trust, and regulatory compliance.

**4. Risk Treatment Phase:**

- ***Mitigation Strategies:*** Develop strategies to mitigate high-priority risks.
- ***Action Plans:*** Create detailed action plans for implementing mitigation strategies, including timelines and responsibilities.

**5. Monitoring and Review Phase:**

- ***Continuous Monitoring:*** Implement ongoing monitoring to detect new risks and assess the effectiveness of controls.
- ***Regular Review:*** Schedule periodic reviews of the risk assessment to ensure it remains up-to-date.

### Team Composition

- **Chief Information Security Officer (CISO):** Oversees the risk assessment process and communicates findings to the executive board.
- **IT Manager:** Leads the technical analysis of systems, identifies vulnerabilities, and assesses the effectiveness of current controls.
- **Compliance Officer:** Ensures the assessment aligns with financial regulations such as GDPR, SOX, and FINRA.
- **Application Development Manager:** Provides insights into the architecture of the online trading platform and potential security flaws.
- **Third-Party Vendor Manager:** Evaluates risks associated with third-party integrations and vendor management.

This team composition ensures a comprehensive, multidisciplinary approach to the assessment. The CISO provides executive oversight, the IT Manager offers technical expertise, and the Compliance Officer ensures regulatory adherence. The Application Development Manager identifies code-level vulnerabilities, while the Third-Party Vendor Manager assesses risks from external integrations. This diverse team combines technical, operational, and regulatory perspectives for a thorough and actionable risk evaluation.

## Risk Assessment Findings

**1. Vulnerability to Phishing Attacks**

- ***Finding:*** A significant number of employees have not undergone recent cybersecurity awareness training, increasing the risk of successful phishing attacks. This vulnerability is exacerbated by the absence of advanced email filtering solutions.
- ***Impact:*** Successful phishing attacks could lead to unauthorized access to Morgan Stanley's systems, compromising client data and damaging the company's reputation.
- ***Current Controls:*** Basic email filtering is in place, but it lacks the sophistication to detect advanced phishing attempts. Annual security awareness training is conducted but is not sufficiently frequent or comprehensive.

**2. Ransomware Attacks**

- ***Finding:*** The client data storage systems are vulnerable to ransomware attacks due to insufficient endpoint protection and lack of robust backup procedures.
- ***Impact:*** A successful ransomware attack could lead to data encryption, operational downtime, and significant financial losses.
- ***Current Controls:*** Basic endpoint protection is in place, but it lacks advanced anti-malware capabilities. Data backups are performed regularly, but recovery procedures are not thoroughly tested.

**3. Third-Party Vendor Breaches**

- ***Finding:*** Third-party vendors integrated with Morgan Stanley's systems have weak access controls and insufficient data encryption, increasing the risk of data breaches.
- ***Impact:*** A breach through a third-party vendor could lead to unauthorized access to client data, resulting in regulatory penalties and loss of client trust.
- ***Current Controls:*** Basic access controls are in place, but multi-factor authentication (MFA) is not consistently enforced. Data encryption standards for third-party integrations are outdated.

## Risk Analysis and Evaluation

| Risk | Likelihood | Impact | Risk Score | Priority |
|----------|----------|----------|----------|----------|
| Phishing Attacks    | High     | High     | 9     | High     |
| Ransomware Attacks    | Likely     | High     | 8     | High     |
| Third-Party Vendor Breaches    | Moderate     | High     | 7     | Medium-High     |

***Risk scores are calculated on a scale of 1-10, with 10 being the most severe.***

## Risk Treatment Recommendations

**1. Phishing Attacks**

***Mitigation Strategy:*** 

- Implement advanced email filtering solutions and enhance security awareness training.

***Action Plan:***
1.	Deploy an advanced email security solution with phishing detection capabilities within 30 days.
2.	Initiate quarterly security awareness training for all employees, focusing on recognizing and responding to phishing attempts.
3.	Conduct simulated phishing exercises bi-annually to assess employee awareness.

**2. Ransomware Attacks**

***Mitigation Strategy:*** 

- Implement robust endpoint protection and backup procedures.

***Action Plan:***
1.	Deploy advanced endpoint protection solutions within 45 days.
2.	Implement daily backups and test recovery procedures within 60 days.
3.	Conduct regular disaster recovery drills to ensure readiness.

**3. Third-Party Vendor Breaches**

***Mitigation Strategy:*** 

- Strengthen access controls and data encryption for third-party integrations.

***Action Plan:***
1.	Enforce multi-factor authentication (MFA) for all third-party vendor access within 30 days.
2.	Conduct security audits of all third-party vendors within 90 days.
3.	Upgrade data encryption standards for third-party integrations within 60 days.

These recommendations enhance Morgan Stanley's security by reducing phishing risks through advanced email filtering and training, mitigating ransomware threats with robust endpoint protection and backups, and securing third-party integrations with MFA and encryption. These measures protect client data, ensure operational continuity, and maintain regulatory compliance, strengthening the company's overall cybersecurity posture.

## Monitoring and Review

### Continuous Monitoring

- Implement a Security Information and Event Management (SIEM) system to continuously monitor and analyze security events in real-time.
- Conduct monthly vulnerability scans and semi-annual penetration testing to identify new risks.

### Regular Review

- Perform a comprehensive risk assessment review annually or after significant changes to the systems or business operations.
- Assign responsibility for monitoring and review to the IT Manager and CISO, with quarterly updates to the executive board.

The monitoring and review processes ensure that Morgan Stanley maintains a proactive approach to cybersecurity by continuously identifying new risks and assessing the effectiveness of implemented controls. Through tools like Security Information and Event Management (SIEM) systems, regular vulnerability scans, and annual disaster recovery testing, the company can adapt to evolving threats and maintain system resilience. This ongoing process helps safeguard client data, ensure regulatory compliance, and minimize potential disruptions, ultimately supporting long-term operational stability and trust.

## Conclusion

This risk assessment highlights critical cybersecurity risks facing Morgan Stanley, including phishing attacks, ransomware, and third-party vendor breaches. By implementing the recommended mitigation strategies, Morgan Stanley can enhance its security posture, protect client data, and ensure operational continuity. Continuous monitoring and regular reviews will be essential to adapt to evolving threats and maintain compliance with regulatory requirements.

## Appendices

**Appendix A: Glossary of Terms**

- ***Phishing:*** A cyberattack where attackers impersonate legitimate entities to steal sensitive information.
- ***Ransomware:*** Malicious software that encrypts data, demanding payment for its release.
- ***Multi-Factor Authentication (MFA):*** A security process that requires users to provide two or more verification factors to access a system.

**Appendix B: Risk Assessment Methodology**

- The methodology follows **NIST SP 800-30** guidelines, ensuring a systematic approach to identifying, analyzing, and mitigating risks.

**Appendix C: Supporting Documentation**

- Vulnerability scan reports.
- Security policies and procedures.
- Disaster recovery and business continuity plans.

**Distribution List:** The report will be distributed to the executive board, IT department, compliance team, and risk management team. Further distribution requires CISO approval.

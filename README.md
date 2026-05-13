# Phishing Security Awareness Training

## Simulation Report

### Cybersecurity Audit Project – Employee Vigilance Assessment

**Organization:** EmiratesGas.ai *(dummy organization for awareness training)*

---

# 1️ Overview

A phishing simulation was conducted across the **Production (30 employees)**, **IT (40 employees)**, and **HR (35 employees)** departments to evaluate the effectiveness of previous phishing awareness training initiatives.

The exercise simulated a **Microsoft 365 email verification campaign** using a replicated Microsoft login portal hosted within a controlled cybersecurity lab environment.

The assessment demonstrated encouraging progress in employee awareness and vigilance:

* Click rates remained relatively low *(7.5% – 17%)*
* Credential submissions were minimal *(0 – 4 total)*
* Reporting rates improved significantly, particularly within IT and HR departments

These findings indicate measurable improvement in organizational security culture, with fewer risky behaviors and stronger phishing-reporting habits.

---

# 2️ Objectives

* Reduce phishing link click-through rates among employees
* Increase phishing incident reports submitted to the security team
* Minimize credential submission attempts on phishing landing pages
* Evaluate employee response to Microsoft 365-themed phishing attempts

---

# 3️ Compliance Drivers

## ISO 27001 A.7.2.2 — Awareness, Education & Training

This phishing simulation provides evidence of employee awareness testing and supports continuous security improvement initiatives.

## Internal Risk Register

Addresses phishing and credential-harvesting threats identified as high-risk attack vectors.

---

# 4️ Tooling

| Tool                        | Purpose                                                              |
| --------------------------- | -------------------------------------------------------------------- |
| ZPhisher                    | Generated phishing simulation pages and captured interaction metrics |
| Localhost / Local Tunneling | Provided controlled internal access during testing                   |
| Kali Linux                  | Hosted the testing environment                                       |
| Google Sheets               | Stored KPIs and simulation metrics                                   |

<p align="center">
  <img src="screenshot/01 Kali ZPhisher.png" width="800">
</p>
<p align="center">
  <img src="screenshot/02 Git ZPhisher.png" width="800">
</p>
<p align="center">
  <img src="screenshot/03 Kali ZPhisher.png" width="800">
</p>
<p align="center">
  <img src="screenshot/04 ZPhisher Microsoft Login Page.png" width="800">
</p>
<p align="center">
  <img src="screenshot/05 Kali ZPhisher Localhost and Submission.png" width="800">
</p>

---

# 5️ Simulation Scenario

## Microsoft 365 Email Verification Campaign

Employees received a simulated Microsoft 365 security notification requesting them to verify or update their corporate Microsoft email account to avoid temporary service disruption.

The email contained a link directing users to a cloned Microsoft login page hosted within an isolated awareness-training environment using ZPhisher.

The objective was to measure:

* Link-click behavior
* Credential submission attempts
* Employee phishing-reporting rates

---

# 5.1️ Phishing Email Template

<p align="center">
  <img src="screenshot/06 Phishing Email Template.png" width="800">
</p>
<p align="center">
  <img src="screenshot/07 Phishing Email Link.png" width="800">
</p>

---

# 6️ Metrics

## Before Awareness Training

| Department | Employees Tested | Clicked Link | Submitted Credentials | Reported | Click Rate (%) | Submission Rate (%) | Report Rate (%) |
| ---------- | ---------------- | ------------ | --------------------- | -------- | -------------- | ------------------- | --------------- |
| Production | 30               | 30           | 27                    | 3        | 100%           | 90%                 | 10%             |
| IT         | 40               | 25           | 2                     | 38       | 62.5%          | 5%                  | 95%             |
| HR         | 35               | 35           | 30                    | 5        | 100%           | 86%                 | 14%             |

---

## Post-Awareness Training Results

The post-training simulation demonstrated significant improvement across all departments:

* Click rates decreased from **62.5% – 100%** to **7.5% – 17%**
* Credential submissions dropped from **90%** to near **0%**
* Reporting rates increased from **10% – 14%** to **88.6% – 100%**

| Department | Employees Tested | Clicked Link | Submitted Credentials | Reported | Click Rate (%) | Submission Rate (%) | Report Rate (%) |
| ---------- | ---------------- | ------------ | --------------------- | -------- | -------------- | ------------------- | --------------- |
| Production | 30               | 5            | 2                     | 28       | 16.7%          | 6.7%                | 93.3%           |
| IT         | 40               | 3            | 0                     | 40       | 7.5%           | 0%                  | 100%            |
| HR         | 35               | 6            | 4                     | 31       | 17%            | 11.4%               | 88.6%           |

---

# 7️ Analysis

## Production Department

Moderate click rate *(16.7%)* with limited credential submissions. Additional phishing awareness reinforcement is recommended for identifying fake Microsoft login portals.

## IT Department

Lowest click rate *(7.5%)* with a perfect reporting rate *(100%)*, demonstrating strong awareness and phishing detection capability.

## HR Department

Slightly higher click and submission rates compared to IT. However, reporting behavior improved significantly after awareness training.

---

# 8️ Recommendations

* Conduct targeted refresher training focused on Microsoft 365 phishing indicators
* Reinforce suspicious-email reporting procedures organization-wide
* Perform quarterly phishing simulations to measure long-term awareness effectiveness
* Introduce gamified awareness initiatives such as leaderboards and recognition programs
* Include Microsoft cloud-service phishing scenarios in onboarding exercises

---

# 9️ Conclusion

The phishing simulation demonstrates that cybersecurity awareness training is producing measurable improvements across the organization.

Reduced credential submissions and significantly increased reporting rates indicate meaningful progress toward a stronger security culture. Continued awareness reinforcement and regular phishing simulations will help EmiratesGas.ai further reduce phishing-related risks while supporting ISO 27001 compliance objectives.

---

### Prepared by
**Ahmed Olatunji** - Cybersecurity Analyst

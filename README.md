# Defender_For_Cloud

**Overview:** Repository for demonstrating security posture management with Microsoft Defender for Cloud

**Prerequisites:**
✅ Active Azure subscription 
✅ Microsoft Defender for Cloud Plan
✅ Virtual Machines
✅ Security Admin or Owner Permission

**High-Level Steps with Explanations:**

 **1. Configure Microsoft Defender for Cloud:** I began by enabling Microsoft Defender for Cloud on my Azure subscription. This involved setting up the necessary permissions and configuring the tool to monitor my resources for security vulnerabilities and threats. Activating Defender for Cloud ensured I could access advanced security features, including threat alerts, compliance management, and proactive recommendations.

 **2. Review the Microsoft Defender for Cloud Recommendations:** After enabling Defender for Cloud, I navigated to the Security Recommendations section to review identified vulnerabilities and configuration issues in my environment. I prioritized the most critical recommendations, such as missing security configurations, and prepared to implement fixes to enhance my security score.

 **3. Implement the Microsoft Defender for Cloud Recommendation to Enable Just-in-Time VM Access:** To reduce the exposure of management ports on my virtual machines, I implemented the Just-In-Time VM Access recommendation. This involved configuring JIT policies to restrict access to VM management ports, allowing connections only when explicitly requested and approved.

**Reference Link(s):**
[* https://microsoftlearning.github.io/AZ-104-MicrosoftAzureAdministrator/Instructions/Labs/LAB_02b-Manage_Governance_via_Azure_Policy.html](https://microsoftlearning.github.io/AZ500-AzureSecurityTechnologies/Instructions/Labs/LAB_09_Microsoft%20Defender%20for%20Cloud.html)

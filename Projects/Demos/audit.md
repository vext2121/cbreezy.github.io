# Performing an External IT Audit

In this project, we will explore the general process of externally auditing a company's IT department for compliance with common regulations, guidelines, and best practices. This exercise will explore some, but not all, IT regulations enforced primarily within the United States. This exercise will illustrate the preparation, analysis, and reporting that goes into a proper IT compliance audit, to guide your studies of legal implications in Information Technology. 
> Disclaimer: The names, characters, businesses, places, events, and incidents portrayed in this work are purely fictitious. Any resemblance to actual persons, living or deceased, or to real events is entirely coincidental. This work is intended for fictional purposes only, and no factual accuracy should be inferred.

## Scenario

This audit exercise will be performed on a simulated company named Nexora Solutions Inc. Specifically, Nexora's Market Intelligence(MI) Unit and its Emerging Technologies Division. As we will see, this company has a bit of work to do to achieve satisfactory compliance with industry regulations. Though, if they were perfect, we'd have no work to do, right? Our audit team will perform an in-depth pre-investigation report to identify abnormal practices and procedures. Our job will be to take this report and analyze it for specific legal infractions and form suggestions for how Nexora can improve its industry compliance. You can view the report [here](/Assets/Images/Audit/NexoraCaseStudy.md), or simply observe our findings below. 

## Goals
- Determine Scope and Audit Nexora's MI Unit for Negligence, Noncompliance or Malicious Activity
- Identify Explicit Legal Infractions, Noncompliance, or Criminal Actions
- Identify Possible Improvements or Risks of Litigation
- Compile the Audit into an Executive Summary for C-Level Executives and other Higher-Ups

## Determining Scope and Performing the Audit
  
As shown in the audit report [here](/Assets/Images/Audit/NexoraCaseStudy.md), our audit team has already identified the scope of the Audit. That being to investigate the IT and business practices of the Emerging Technologies Division of Nexora Solutions. While this has saved us a bit of time for the sake of this exercise, the establishment of scope must not be overlooked. This would have been laid out in a debrief meeting upon being requested to perform the audit, long before it was performed. This is necessary to avoid over-provisioning resources for this task and maintain compliance with audit guidelines and regulations, as well. Human and physical resources are dedicated to a specific task and achieving specific goals efficiently.

Though for the sake of this step, we're done! We assume management has determined the scope of this audit, sent investigators to collect information, and given us the report. On to the next step, which is our job of identifying the exact laws, regulations, and guidelines that Nexora Solution's Emerging Technologies Division violated.

## Identifying Specific Legal and Regulatory Violations

Our final report requires that we identify explicit legal and regulatory violations of on the part of Nexora Solutions' Emerging Technologies Division. This allows us to illustrate technical information to non-technical staff within our executive report. We will identify each violation and why it was violated. Remember, legal violations may result in litigation, while regulatory violations are industry standards that may have a company or individual banned from conducting business.

### Legal Violations

#### Computer Fraud and Abuse Act(CFAA)
IT Security Analyst Hannah Collins failed to enforce user account controls, leaving all workstations with admin rights and unauthorized access to other departments' systems, violating the CFAA.

#### Electronic Communications Privacy Act(ECPA)
Michael Carter reports that the MI Unit used dummy accounts to access unprotected Nexora systems without proper authorization and to discuss illegal “dumpster diving” and “trash surveillance” against non-clients. These actions violate the Electronic Communications Privacy Act (ECPA). Additionally, the accounts belong to former employees, facilitating unauthenticated communications, further breaching the ECPA.

#### Sarbanes-Oxley Act(SOX)
The SOX Act mandates financial report audits to ensure ethical practices. Nexora never fully audited its client financial databases, and when it did, unethical activities were uncovered, violating SOX and exploiting investors.

#### GDPR (If the company does business in the EU)
There was no mention of a suitable Acceptable Use Policy(AUP), which could have prevented numerous malicious actions by members of the Emerging Technologies Division.

### Regulatory Violations

#### NIST 800-53
- Control PL-4: Failing to enforce suitable Acceptable Use Policies(AUPs)
- Control CA-7: Failing to assess proper authorization and properly monitoring for acceptable network activity
- Control AT-2, 3, & 4: Failing to exercise adequate Security Awareness, Training, and Education(SATE) programs.

#### NIST 800-207
- This guideline illustrates how to construct and maintain a Zero-Trust IT infrastructure.

#### ISO 27001/27002
- Annex A.5: Failing to enforce  and document suitable Acceptable Use Policies(AUPs)
- Annex A.12: Failing to monitor and detect security events
- Annex A.7: Requires SATE programs to maintain company-wide best practices with IT security 

#### CIS
- Controls 6-8: Inadequate network traffic and security event monitoring
- Control 14: Failing to enforce adequate SATE training, which includes communicating AUPs

Already! We have formed a hefty list of legal and regulatory issues within Nexora's Emerging Technologies Division--and these are only a few(see if you can find more!) It's worth noting that Nexora's compliance issues align across multiple industry guidelines. Despite the overlap, each industry framework offers unique approaches that complement one another in conjunction. Most IT departments follow multiple up-to-date frameworks to ensure best practices and protect employees and clients in a rapidly evolving IT landscape.

## Identify Improvement Paths and Possible Litigation Risks
  
We are tasked with identifying every possible shortcoming of Nexora's IT procedures and its legal violations. However, we are not responsible for pursuing litigation against them. We are here to advise on possible improvements and acknowledge that they can be litigated for negligent or malicious activity. With that said, here is a list of those recommendations:

### Implementation of a Suitable AUP and Application White-Listing

- Creating a thorough AUP would provide grounds for management to discipline or terminate employees who don't conform to company and industry regulations, laid out in the AUP. This may be a result of negligent or malicious management on the part of the division head, Ryan Caldwell, illustrating how important leadership is for secure company culture.

- Implementing application white-lists would prevent users from downloading applications that the company does not approve. To clarify, a white list assumes no applications are authorized for downloading(black) unless explicitly authorized in a list of authorized applications(white). This would have prevented users from downloading malicious software like Metasploit and intruding on non-client networks.

### Implementation of a more Thorough and more Frequent SATE Program

- Security Awareness, Training, and Education(SATE) programs are necessary for ensuring non-technical and technical users handle technology and information appropriately. It is the responsibility of management and GRC personnel to conduct these trainings. They must also document each training session and who recieved the training for the sake of accounting and complete employee participation.

- This would have allowed ignorant employees and managers the ability to identify negligent and malicious use of company technology. Not only reporting on other's poor habits but improving their own as well. 

### Implementing Stronger Network Monitoring Infrastructure

- It is hard to identify what they lack in particular. What we can say is that most IT departments design network architecture with a foundation of security in mind. This includes considerations for firewalls, intrusion detection/prevention systems, and extensive logging of endpoints and data traveling between them. Nexora must upgrade its infrastructure to capture all of this data and educate its team on how to monitor it all for non-compliance, malicious activity, or general maintenance situations.

- Without this foundational focus on network surveillance, Nexora was unable to perform due care(preventing problems) or due diligence(investigating current problems). Implementing the proper security infrastructure and acting on it would have prevented data loss/extraction from various departments, criminal intrusion on non-client networks, and misuse of company hardware.

### Enforcing the Principle of Least Privilege

- This falls on the division head, Ryan Caldwell, and the IT security team as a whole. Users in the Emerging Technologies Division were given excessive privileges, allowing them unauthorized access to unnecessary company resources. Enforcing proper group policies, access controls, and proper employee onboarding procedures would have saved Nexora a multitude of problems.   

### Possible Risks of Litigation

Remember, there is a difference between regulatory violations and legal violations. Legal violations may result in litigation:

- CFAA
  - Civil: Lawsuit from each exploited user
  - Criminal: up to 5 years in prison

- ECPA
  - Civil: Lawsuit for $100 per day per violation that occurred, or a minimum of $10,000
  - Criminal: up to 5 years in prison and $500,000 in fines
- SOX
  - Civil: Depending on the extent of financial tampering, possible class-action
    lawsuits, and millions in fines or       
  - Criminal: Similar fines and up to 25 years in prison
- GDPR
  - Millions in applicable currency and litigation from the EU Data Protection Authority

Yikes! Not only could Nexora face regulatory bans but possibly millions of dollars in civil and criminal litigation. Fortunately, we're just here to deliver the message. On to the executive summary!

## Conclusion: Create an Executive Summary

Now all the hard work has been done. The executive summary will take whatever form you see fit. This could be a formal report, as our coworkers did for us after the investigation. It could be compiled into a PowerPoint presentation to supplement an in-depth meeting with the relevant parties. You have everything that is required of a formal executive report for this external audit, that is:

- Primary investigation of Nexora's current practices and procedures
- All legal and regulatory implications
- Suggestions for improvement compliance or planning litigation possibilities

And that's it! This is where you go forward with your most vital soft skill, communication. Organize this information into a comprehensive story for your company and Nexora. Ensure that all parties feel that the audit was thorough and that all strategic avenues are available for the audited party.

Whew! If you made it this far, congratulations, you have witnessed how feasible an audit process can be. All it takes is a team executing proper planning, understanding the industry regulations that apply to the target companies, and communicating how said companies can strategize for the future. While legal implications seem daunting, it's possible for any tech professional to grasp and its important to maintain integrity within industry...we would be no better than animals without rules!

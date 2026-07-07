# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
* Northstar Medical Group is a fast-growing healthcare organization that outsourced its Identity Lifecycle Management to a third-party MSP. This arrangement worked well in the early stages, but cracks began to appear as the company scaled. No RBAC framework existed to govern user access based on defined roles. Permissions were granted on an ad-hoc basis, with no standardized or auditable process. Combined with the lack of audit trails, this left the organization exposed to significant HIPAA compliance risk.

## Solution Overview
* To address these gaps, I built out a basic employee onboarding pipeline in Active Directory. I designed and implemented an RBAC matrix to ensure users were granted access strictly according to their assigned role, eliminating ad-hoc provisioning. I also simulated a mock support ticket where a user had been provisioned with an incorrect access level, in order to test and validate the review process for catching and correcting such errors.

## Video Walkthrough
[Add your video walkthrough link placeholder here. You will record this tomorrow and update this link so visitors can see a live demonstration of your lab environment.]

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* Solved a mock ticket where a user was given the incorrect access!
* I fully documented my steps end-to-end



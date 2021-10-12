---
description: An e-adjudication case study
---

# Effective Communication with UI Claimants Through a Standalone Case Management System

**Note on U.S. Digital Response Independence**

U.S. Digital Response’s (USDR) unemployment insurance (UI) team has partnered with more than ten workforce development agencies to troubleshoot challenges, expand capacity, and improve the user experience. With our partners, we quickly evaluate, plan, and/or implement more effective and impactful solutions. Through one of these partnerships, we learned about their newly digitized fact-finding system. USDR was not involved in any way in the project described in this case study. We wrote this case study because it is a great example for other agencies of a UI modernization project that uses incremental, continuous delivery, and modular development while keeping the mission in-house.

**Impact Summary**

Previously, the State UI System was not meeting US Department Of Labor (DOL) requirements for quick resolution of claimant issues because they were fully reliant on fact-finding via phone calls scheduled weeks into the future. The State implemented a new system, switching to an online fact-finding interview , resulting in a response from claimants within one day for 50% of issues, instead of weeks for each individual concern. Additionally, examiners nearly doubled the number of cases they were able to process in a day.

**Problem Statement**

Previously, the State UI System was far from meeting the US DOL target of 87% of issues resolved within 3 weeks, and were put on a corrective action plan. At that time, to resolve issues the State DOL was fully reliant on scheduling phone calls with claimants, creating a backlog so large that calls needed to be scheduled weeks into the future. To become compliant with the U.S. DOL’s standards, the State would need to drastically change their fact-finding process. ![](https://lh4.googleusercontent.com/UHOKOJUtNUXrqKPc8\_r5BvdNyMnl00oamkLtk85XDRUoHyabLOTt7f92niBwkfeUhrXvg38Qs-hOWLXQsSiLBFa_CGVR1BQOP1Tv3qdjPJyA3xgSjwP3fJLz-YoOziB13zQCthew=s0)

**Solution**

We incorporated USDR’s fundamental principles in the following ways:

**Modular development:** the State DOL built the system “on top” of the existing infrastructure, to replace the existing manual phone-based adjudication system. They do have API-based integration from the mainframe to initiate the new adjudication system, but they still have examiners input determinations directly into the old system rather than requiring that the new system connect directly back. 

**Incremental, continuous delivery:** The State DOL did not transition all issues to the new system at once; they started with issues connected to initial claims, then progressed to web certifications/weekly claims, reopened claims, and monetary issues. This iterative process provided time for staff to get used to the new system and to improve the process for some issues while the system was being built out for others. They didn’t have to wait for everything to be done to start seeing benefit to both staff and claimants. In addition to not waiting for the system to cover all issues before going live, the State DOL kept several features out of scope and can consider adding them in the future, e.g.: employer fact-finding, carefully automated determinations, API connection back to mainframe from the CMS. 

**In-house ownership:** Their vendor showed the State DOL how to create and edit questionnaires, notifications, and reports, so, once the system was initially set up, they could easily make their own changes or additions. The State DOL is able to use the reports to understand what claimants might be having difficulty with in the user experience and make copy and question changes accordingly.



**Architecture**

The State DOL stood up a cloud-based case management system (CMS) to get more information from claimants when issues are detected. This new CMS is nearly independent of the State’s mainframe: a query is run nightly in the mainframe to get a list of claims with particular issues, and that data is sent via API to the CMS to send questionnaires to claimants. On the other end, examiners view responses in the CMS and do double manual data entry into both the CMS and mainframe.           ![](https://lh6.googleusercontent.com/GY0huInaJ0zrE7vGuqRo1o0cpELZrP3UeqcK9zLGEhTVjpQF\_6XMZvKhkVMgyYN13PcVvNFfcweJUbmtaViOfLDsGS57ycunlRk_qBIkUX\_6bQ5elefe94bQbhO0\__iPdL5i05ht=s0)

**User Experience**

Once the CMS knows which claimants have what issues that need resolving, it sends email notifications to claimants with unique links. The content at this link is specific to the individual, and can gather information about both monetary and non-monetary issues.

The CMS can be set up to send reminder notifications for people who haven’t responded in the given timeframe; the State chose to leverage both email and SMS capabilities for reminders. The reminders can be tailored to different populations, e.g., those who haven’t started the questionnaire, who started and abandoned the questionnaire, or who submitted the questionnaire with incomplete responses.

When the claimant fills out the questionnaire, their case is put in a queue for examiners to look at. The CMS enables load balancing cases for the examiners (and can account for differing skill levels/proficiencies), and provides reporting on productivity and outcomes for individual examiners. An examiner can see data about all the claimant’s issues in one place, and then when a determination is made, they enter that information both into the CMS and manually back into the mainframe.

### Bringing this live

The State planned for a 6-week period where phone interviews were still happening, but new ones weren’t being scheduled. During the transition period, examiners needed to handle both the scheduled phone calls and the new digital workload. It was not as bad as everyone thought it would be given the efficiency and ease of the new system. They went live based on when they knew they would have lowest volume, and they were prepared to turn the new system off and keep scheduling phone appointments while troubleshooting before doing a small live test again.

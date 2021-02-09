# Solution space

### Overview

Here’s how the state agency describes their high-level needs, and USDR’s notes about that requirement after looking at the first dozen vendors or so. To see the evaluation matrix along these and other dimensions, download this spreadsheet:

{% file src="../../../.gitbook/assets/usdr\_appointment\_scheduling\_vendor\_comparison\_sheet\_2020-12-04\_update.xlsx" caption="Appt Scheduling Vendor Comparison Matrix" %}

* SaaS-based scheduling tool.
* Ability to define \# of appointments available based on \# of agents.
  * As we look at the different tools, it doesn’t appear on the surface that any offer this particular functionality. However, 1\) calls with sales reps could verify this, or 2\) we can think about this a different way. E.g., you may have to figure out how many appointments you can manage per slot, and the question becomes: how easy is it for you to set and update that “schedule”?
* Ability for customers to self-schedule their own appointments.
  * Almost all the evaluated providers have the ability for you to “embed” the tool within your own webpage; some additionally have the option for you to create your own experience and use their API, or for you to use a landing page that they provide for you.
* Ability to prevent duplicate appointments being set by same individuals.
  * No tool mentioned this as a feature, but we can ask about it in sales calls.
  * **Note:** if the system does a good enough job sending a confirmation email/SMS right after the person books the appointment, we might not see as many duplicate bookings.
  * **Alternative:** We might also be able to think through a solution to put “on top” of the vendor’s implementation. The following is an example of a solution that could work depending on the UI system’s technical limitations:
    * Scheduling appointments would be available only after logging in. If the tool has webhook/API support, whenever someone schedules an appointment, it would let the state's UI system know that it had happened, and then remove the option for that person to schedule another appointment, showing instead “Appointment already scheduled” or something to that effect.
    * You could take this a step further and have the tool send you back information about when the person’s appointment actually is to display that and give them a clear way to cancel or reschedule.
* Confirmation emails/reminders to customers:
  * Almost all tools have both confirmations and reminders. The biggest question is email vs. SMS. SMS costs more from many of the vendors but may be more effective at reducing no-shows.
* Ability to customize forms for collecting information
  * The tools labeled as “candidates” in the spreadsheet all have this ability; however, some only have this ability in different pricing tiers. We’d want to clarify what kind of intake data you want and run that past the sales folks to understand the feasibility of your specific need.
* Ability to see all callbacks scheduled and make agent notes and set indicators for those we were unable to reach:
  * All the vendors marked as “candidates” have some level of reporting, though it can vary by pricing tier. 
  * It was not apparent with most of the vendors how you might annotate individuals as un-reached; that might be something that you integrate with your CRM or have an agent manually look up and note in another tool at their disposal. Vcita has this capability in its higher-cost tiers, as does Nemo-Q \(both vendors used by state DMVs\).
* Form localization support, including callbacks in the chosen language:
  * I need to go back and look for localization support of the intake form and calendar interface.
  * Re: callbacks in the chosen language: this could be figured out by collecting that information as data in the intake form.
* Ability set workgroups so callbacks can be schedule by certain teams:
  * This gets to the ideas of “users” and “access”, which are ill-defined in many descriptions of the tools’ features. This will likely become clearer when we’re able to talk to salespeople and describe our scenario to get feedback.
* Various reporting capabilities for metrics/quality control:
  * Again, we’d want to know more about what specifically the agency is looking for to evaluate this furhter.

**Additional desirable features:**

* Some form of integration capabilities with CRM:
  * Many of the candidates do have this via Zapier, which is another app that helps provide the connection between different systems.
* Ability to standup multiple instances to take advantage of different divisions’ needs:
  * Most of the tools offer this in some manner, though some might be sleeker than others.
* Dashboard view of callback status for staff performance/monitoring:
  * This seems beyond the scope of many of the tools, but it is something that we could ask about in a sales call. Likely the first sticking point would be the fact that people wanting a call back aren’t scheduling an appointment with a specific individual.

### **Vendors**

* **Evaluated:**

  * Acuity Scheduling
  * Appointy
  * Calendly
  * DocPace
  * FlexBooker
  * Juvonno
  * LumaHealth
  * Microsoft Bookings
  * MS Dynamics
  * QLess
  * Schedulicity
  * Setmore
  * Solv
  * Square Appointments
  * Vagaro
  * vcita
  * You Can Book Me

  **Not evaluated:**

  * ﻿Appointlet
  * AppointmentPlus
  * EZnet Scheduler
  * Genbook
  * Marketing360
  * Qmatic
  * SimplyBook.me
  * TimeTap


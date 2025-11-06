---
name: User stories template
about: Template for creating user stories
title: ''
labels: ''
assignees: ''

---

**As a** nature enthusiast visiting the wildlife resort.
 **I need** to easily browse and book safari tours online from web portal.
 **So that** I can plan my visit conveniently.
   
 ### Details and Assumptions
Users have access to the internet and a device to browse the website.
Safari tours have real-time availability data in the system.
Payment gateways are integrated and functional for online bookings.
User will receive confirmation mail in register email id after successful payment
Users understand basic English (or the language of the platform).
The resort staff will update tour schedules regularly.
   
 ### Acceptance Criteria  
   
 ```gherkin
Given the user is on the wildlife resort website
When the user views the safari tours page
Then the user should see a list of available tours with dates and prices

 Given the user has selected a tour 
 When the user proceeds to booking
 Then the system should allow the user to complete the booking in a single flow

Given the booking is successfully completed
When the booking is confirmed
Then the user should receive an email with the itinerary and payment confirmation

Given the user has a confirmed booking
When the user chooses to cancel or reschedule
Then the system should allow cancellation or rescheduling according to resort policies
 ```

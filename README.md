# EventForce Management System

A Salesforce CRM application for an event planning company. It manages clients, events, venues, vendors and feedback in one org, and automates bookings, reminders and cancellations.

**Program:** Salesforce Developer (Naan Mudhalvan)
**College:** Arasu Engineering College
**Team Leader:** Kiruthika Kannan
**Registered Mail ID:** kiruthikakannan061@gmail.com
**Team ID:** SWTID-2026-4043

## Demo Video
[Watch the Demo Video](https://drive.google.com/file/d/17hnJxd90RoEzYicuJ-ifI9Z1rySiJ2px/view?usp=drivesdk)

## Features
- Six custom objects: Event, Client, Vendor, Venue, Feedback, Event Vendor
- Email validation rule on Client
- Event Budget formula field based on event type
- Lookup filter on Feedback
- Approval process for event cancellation (Event_Cancellation_Process)
- Record-triggered Flow (Event_Reminder_Flow) with a 3-days-before reminder email
- Apex trigger to prevent double booking of a venue (PreventDoubleBooking)
- Apex trigger and helper to update venue availability (EventTrigger13, VenueStatusHelper)
- Batch and Schedulable Apex to mark past events as Completed every night (BatchCompleteEvents, ScheduleCompleteEvents)
- Lightning App (Event Planner), report (Upcoming Events by Month) and dashboard (EventForce Operations Dashboard)
- Roles, profiles, permission set (Feedback Manager), organization-wide defaults and an Event sharing rule

## Repository Contents
- `efmsd.pdf` and `efmsd.docx` : project documentation
- `EventForce-Management-System/Code/` : Apex classes, triggers, formula and validation rule
- `README.md` : this file

## Platform
Salesforce Developer Edition, Lightning Experience.

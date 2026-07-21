---
title: "Video Demo"
date: 2026-06-28
weight: 8
chapter: false
pre: " <b> 8. </b> "
---

# 📋 System Functionality List

Summary of key user (User) and administrator (Admin) features on the AWS Serverless Event Management Portal system.

<iframe src="https://drive.google.com/file/d/1o7jYsZKDzKYaxqa19NlDwcz02fIEcPjM/preview" width="100%" height="450" allow="autoplay"></iframe>

## 👥 1. User Features (User / Visitor)

*   **View & Search Events:** Browse active events, search by keywords, or filter by category (Technology, Music, Sports...).
*   **View Event Details:** View descriptions, location, time, remaining seat count, previous reviews, and related event recommendations.
*   **Sign Up & Sign In:** Create a new account or securely log into the system via Cognito.
*   **Book Tickets:** Reserve tickets for available events, receive digital tickets and QR codes for check-in.
*   **Join Waitlist:** Submit registration to the waiting list when an event is sold out.
*   **Manage Personal Profile:** View ticket booking history, change password, and option to delete account.
*   **Review Events:** Rate with stars and leave feedback for events actually attended (checked-in).
*   **Export Personal Calendar:** Download `.ics` calendar files or add events directly to Google Calendar.

---

## 👑 2. Administrator Features (Admin)

*   **Manage Events (CRUD):** Add new events, update details, or remove events from the system.
*   **Manage Attendees List:** View detailed list of registered participants for each event (Email, Ticket ID, Booking Date, Ticket Status).
*   **QR Code Check-in:** Scan QR codes on attendee tickets (or manually enter ticket codes) to confirm attendance and prevent duplicate ticket usage.
*   **Access Control:** Manage dedicated Admin Dashboard interface and automatically restrict standard user accounts from accessing.

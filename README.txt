JOIN MY SALES TEAM — WEBSITE

This is a custom recruiting funnel inspired by the structure of colechristoffersen.com,
using original copy and branding.

Included:
- High-impact recruiting hero
- Video placeholder
- Multi-step qualification application
- Daily time commitment question
- Sales experience question
- Calendar unlocks immediately after the final application question
- Time slot booking
- "What You Get" section
- Process / blueprint section
- FAQ
- Income disclaimer
- Fully responsive mobile layout

IMPORTANT:
This version stores applications and bookings only in the visitor's browser using localStorage.
For real public applications across devices, connect the form to a backend/database
and optionally Google Calendar, email, SMS, or a CRM.

OWNER / CALL NUMBER (kept available for future integration):
781-718-7998


HOW TO RECEIVE APPLICATIONS

The website now has an APPLICATION_ENDPOINT setting inside index.html.

1. Create a form endpoint using Formspree, Make.com, Zapier, a Google Apps Script,
   Supabase, or your own backend.
2. Copy the endpoint URL.
3. Open index.html and find:
   const APPLICATION_ENDPOINT = "";
4. Paste your URL between the quotation marks.
5. Deploy the site.

The site sends:
- Age
- Location
- Daily hours commitment
- Sales experience
- Why they are a good fit
- Phone number
- Email
- Submission date/time

After they book, it also sends:
- Selected calendar date
- Selected call time
- Their full application data

Without an endpoint, the site still keeps a local browser backup, but you will NOT
receive submissions from other visitors.


CONNECTED FORMSPREE ENDPOINT:
https://formspree.io/f/mdekpvaw


FINAL SUBMISSION FLOW
- The application step does NOT send anything to Formspree.
- The applicant completes the questions, enters phone/email, and opens the calendar.
- Only after they choose a date/time and click Confirm Call is ONE Formspree submission sent.
- That single submission contains all application answers + phone + email + booked date + booked time.


ONE-SUBMISSION FLOW:
The site now sends exactly one Formspree submission.
Nothing is sent to Formspree when the applicant first opens the calendar.
When they click Confirm Call, one submission is sent containing:
- Age
- Location
- Hours per day
- Sales experience
- Why they are a good fit
- Phone number
- Email
- Booked date
- Booked time


POST-BOOKING LOCK:
After a successful Formspree submission, the application and calendar are hidden and
the visitor only sees a "Thank you for booking" confirmation screen. The completed
booking is saved in localStorage, so refreshing or reopening the site in the same
browser keeps them on the confirmation screen instead of letting them choose again.


BOOKED-TIME BLOCKING
Confirmed time slots are stored in localStorage and shown as "Booked" / disabled
for that browser.

IMPORTANT: Formspree is submission-only. To prevent double-booking globally across
different visitors/devices, connect the site to a shared database or calendar backend
such as Supabase, Firebase, or Google Calendar.


THEME: Red
FORMSPREE ENDPOINT: https://formspree.io/f/mdekpvaw

BRANDING: Levels Financial
FOOTER: © 2026 Levels Financial

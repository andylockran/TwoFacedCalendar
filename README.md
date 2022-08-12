# TwoFacedCalendar

This is a proof-of-concept Office365 Extension for Free-Busy sync with other calendars.

I am the same person across both my professional and personal calendars, but have to manage my free-busy separately.

This plugin is an attempt to see whether I can get Office365 to sync my Free/Busy information from my personal calendar into my work calendar so that
I'm not double booked for appointments.

A stretch goal would be to do the reverse (i.e. show my work appointments in my Gmail Calendar as events that simply demonstrate I'm working.

The information published in each calendar should not contain any additional metadata about the meeting, except that I'm busy.

It definitely should not share meeting titles, locations or attendees.

It _may_ look at the type of booking (Out of Office, Free, Busy .etc) so that 'Free' meetings don't show up as 'Busy' - but that's hopefully the extent.

Whilst it would be better for this to execute server-side, I also think it could work if only executed on the Outlook client.

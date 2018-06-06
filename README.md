# Markmandsgade Infrastructure

Under development, not ready yet...

This repository will contain infrastructure for the Markmandsgade-project. 

The initially most important thing is resource booking, - rooms, co-workingspace-seat, ... Maybe as fixed price before a certain date, and dutch auction afterwards.

# Resource Booking Design

Database:

- event
    - about (resource/person)
    - time
    - tags, description, participant-limit, ...
- booking
    - credit
    - resource/person
    - start/end
    - event
    - state (fulfilled?)
- resource ()
    - booking-granularity
    - pricing model
- person
    - credit

Views:

- calendar (tag/resource/person)
- resource-booking
    - event creation

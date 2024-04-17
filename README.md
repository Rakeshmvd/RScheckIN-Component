# RScheckIN-Component
RScheckIN Tool component for Joomla - free to use as is.

At the checkin of the event, if you require to be able to have a easy frontend checkin system that enables you to checkmark the subscribers/tickets at point of entry.


Requirements:
Joomla https://www.joomla.org
RSevents https://www.rsjoomla.com/joomla-extensions/joomla-events.html
RSform https://www.rsjoomla.com/joomla-extensions/joomla-form.html

INSTALL
- Like any Joomla component
- Create menu item to RScheckIN in backend
- Login in frontend with Admin/Event owner
  


STEPS 
To get all the functions of the RScheckIN component.


Ticket note (frontend)
    1. Add this hidden field in your ticketform in RSform that is used by RSevents, to this exact name of hidden field: Subscription_Note
    2. Enable registration: Checkmark - within your event of RSevents.
    3. Event registration: Select the Registration form in your events of RSevents.


Adding tickets (frontend)
    4. Event registration: Checkmark; Automatically approve free registrations
    5. Add new coupon: Door ticket, Coupon codes; CASH (or DOOR or FREE), Apply a discount of; 100% Percent


Owner
    6. Contact: Owner: your prefered owner of the event that needs access to RScheckIN


Group access
    7. Groups: Create a new group with access to Subscriptions permissions.


Extra RSform fields to display (with mobile in landscape mode)
    8. Add the exact names of (max 3) fields in CheckIN settings seperated with commma (no spaces).


Use other ticketform then default settings (optional)
    9. If you wish to use a different ticketform when adding subscribers in frontend, you can select this form in RScheckIN settings.

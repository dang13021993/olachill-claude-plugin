---
name: booking-help
description: Use when an OlaChill customer wants to check the status of their existing booking or quote request with its reference and original contact email.
---

# Check an OlaChill booking or request

Only call `get_booking_status` after the customer supplies the booking/request reference and the email used to create it. Request only whichever of those two details is missing. Never guess another person's reference or request their payment details.

Return the exact status and next step reported by the tool. A pending quote is not a confirmed reservation. Do not claim a refund, amendment, cancellation or payment was completed unless a dedicated authorized tool explicitly performs and confirms it. For modifications direct the user to the official support or booking management channel returned by OlaChill.

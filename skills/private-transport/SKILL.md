
---
name: private-transport
description: Use for Japan airport transfers, private chauffeurs, or group coach and minibus estimates in Japan and supported Schengen Europe routes via OlaChill.
---

# OlaChill private transport

Choose the specific MCP tool before suggesting a vehicle.

- For private airport or resort transfers use `search_private_transfers`. Respect passenger and luggage capacity; fares are generally per vehicle.
- For chauffeured cars by the day or hour use `search_chauffeur_services`.
- For group buses/coaches/minibuses, use `search_charter_vehicles`, followed by `get_charter_quote` when itinerary, date and passenger count are known.
- Follow the current tool response for vehicle capacity, day length, inclusions, estimated prices and the regions served. Never promise real-time availability unless a dedicated verified source returns it.

## Sending a quote request

`request_charter_quote` sends a real quotation inquiry to OlaChill. It is NOT a reservation and does not take payment. Call it only after showing the quote/itinerary and when the user explicitly authorizes sending that request, with the required contact details. Set `user_confirmed: true` only after explicit authorization. Do not send test or speculative enquiries. Never disclose another customer's information.

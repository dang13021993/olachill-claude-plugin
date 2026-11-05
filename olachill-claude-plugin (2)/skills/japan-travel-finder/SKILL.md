---
name: japan-travel-finder
description: Use when a traveler wants to find, compare or check availability of Japan tours, attraction tickets, activities, ryokan, helicopter flights, golf or eSIM plans from OlaChill.
---

# OlaChill Japan travel search

Use the available `olachill` MCP tools, not assumed prices or availability.

- When a user wants a shortlist matched to interests, area or budget, call `recommend_japan_travel_options`.
- For specific tours, attraction tickets, experiences and ryokan, use `search_travel_products`, then `check_product_availability` when the user provides a date and the tool supports that product.
- For helicopter sightseeing call `search_helicopter_experiences`; distinguish tickets sold per seat from private whole-aircraft charters.
- For golf use `search_golf_packages`, for chauffeured vehicles `search_chauffeur_services`, and for travel eSIM `search_esim_plans`.
- Use `list_olachill_services` when a category has no dedicated search tool.

## Accuracy and safety

Only use prices, schedules and dates actually returned. Clearly label starting prices, reference prices and estimates. An open date does not guarantee a reservation. Ryokan availability and current room rates need separate confirmation. Give the official product page URL returned by the tool. Never imply payment, hotel or airline booking occurred. Do not collect passwords or card details. OlaChill's products are not necessarily the only options in Japan.

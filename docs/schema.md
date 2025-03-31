# 📊 DönerIndex Data Schema

This document defines all fields collected in the DönerIndex dataset.

| Column | Description |
|--------|-------------|
| `price` | Total cost of the döner in euros (€) |
| `weight` | Weight in grams (g) |
| `time_of_day` | Time of purchase (HH:MM, 24-hour format) |
| `date` | Date of purchase (YYYY-MM-DD) |
| `length` | Length of the döner in centimeters |
| `width` | Width of the döner in centimeters |
| `height` | Height of the döner in centimeters |
| `meat_type` | Type of meat (e.g., chicken, veal, lamb, tofu) |
| `bread_type` | Type of bread used (e.g., pita, yufka, sandwich, dürüm) |
| `type` | Portion/form type (e.g., normal, big, dürüm) |
| `extra_ingredients` | Extra ingredients, semicolon-separated (e.g., onion;cheese) |
| `price_of_tea` | Price of a tea in euros (€) |
| `availability_of_tea` | Whether tea is available (yes/no) |
| `shop_name` | Name of the döner shop |
| `address` | Full address of the shop |
| `city` | City where the shop is located |
| `zip` | Postal code |
| `gps` | GPS coordinates in "lat,long" format |
| `altitude` | Altitude of the shop in meters |
| `AGS` | Official municipality code |
| `distance_to_transport` | Distance to the nearest public transport (meters) |
| `opening_date` | Date the shop opened (YYYY-MM-DD) |
| `available_seats` | Number of seats available for customers |
| `shop_size_m2` | Estimated shop area in square meters |
| `google_rating` | Google rating (0–5) |
| `social_media` | Does the shop have social media? (yes/no) |
| `card_payment` | Accepts card payment (yes/no) |
| `paypal_payment` | Accepts PayPal (yes/no) |
| `stamp_card` | Offers loyalty/stamp card (yes/no) |

# Movie Theater Ticket Kiosk

This self-service kiosk lets a customer view available movies and showtimes, choose an available seat, and buy a ticket. After the purchase, the system provides a confirmation. It must also prevent the same seat from being sold twice for the same showtime.

## About this homework

I am using this toy system to practice software engineering tools. This repository contains homework documents; no software implementation is required.

## Requirements

The five kiosk requirements are listed in [requirements.md](requirements.md).

## Purchase Ticket use case

**Primary Actor:** Customer

**Precondition:** The customer has selected a movie, showtime, and available seat.

**Main Steps:**

1. The customer starts the purchase for the selected ticket.
2. The kiosk displays the movie, showtime, seat, and ticket details.
3. The customer reviews and confirms the ticket details.
4. The kiosk requests payment.
5. The customer submits payment.
6. The kiosk verifies payment and seat availability, completes the purchase, and displays a confirmation.
7. The customer receives the purchase confirmation.

**Postcondition:** The ticket purchase is confirmed, and the seat is no longer available for that showtime.

The [use-case diagram](diagrams/Movie-Kiosk-Use-Case.png) shows the three customer goals for this kiosk.

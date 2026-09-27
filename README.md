# Movie Theater Ticket Kiosk

This self-service kiosk lets a customer view available movies and showtimes, choose an available seat, and buy a ticket. After the purchase, the system provides a confirmation. It must also prevent the same seat from being sold twice for the same showtime.

## About this homework

I am using this toy system to practice software engineering tools. This repository contains homework documents; no software implementation is required.

## Requirements

The five kiosk requirements are listed in [requirements.md](requirements.md).

## Purchase Ticket use case

**Primary Actor:** Customer

**Precondition:** I have selected a movie, showtime, and available seat.

**Main Steps:**

1. I start the ticket purchase for my selected movie, showtime, and seat.
2. The kiosk shows me the ticket details.
3. I check the details and confirm that I want to buy the ticket.
4. The kiosk asks me to pay.
5. I pay for the ticket.
6. The kiosk checks that the seat is still available, completes the purchase, and shows a confirmation.
7. I receive the ticket purchase confirmation.

**Postcondition:** My ticket is confirmed, and the seat is no longer available for that showtime.

The [use-case diagram](diagrams/Movie-Kiosk-Use-Case.png) shows the three customer goals for this kiosk.

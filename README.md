# Event Tickets

## Purpose
Ticket sales for a venue event is a very difficult architecture design for a computer system.
The solution needs to provide a high performance, reliable system to purchase unique ticket locations.
Needs to publish un-purchased tickets, hold tickets that are in the cart, and exclude ticket that are purchased.

## Architecture
### Frontend
AWS apprunner django python code
### Backend
AWS DynamoDB - Tables for each venue section
Aurora RDS - ticket purchase information
Cache ?
# MSE - 2: Avoid Microservices calliing each other directly
Date: 15-05-2023
## Status 
Accepted

## Context

## Decision
We don’t let ms-flights call ms-reservations to assemble the seating chart, and instead have the BFF API handle the interaction

## Consequences

# Airbnb Clone – Use Case Diagram

This document describes the Use Case Diagram visualizing the interactions between users and the system.

The diagram `use-case-diagram.png` included in this directory shows all major actors and their interactions with the backend.

---

## Actors

- **Guest**
  - A user who browses properties and makes bookings.
- **Host**
  - A user who lists and manages properties.
- **Admin**
  - A system administrator who oversees platform activity.
- **Payment Processor**
  - An external payment gateway (e.g., Stripe, PayPal).

---

## Main Use Cases

Below are the primary use cases captured in the diagram.

### User Management
- Register an account
- Log in
- Update profile

### Property Management
- Create property listing
- Edit property listing
- Delete property listing
- View properties
- Search properties

### Booking System
- Request booking
- Confirm booking
- Cancel booking
- View booking history

### Payments
- Make payment
- View payment records

### Reviews
- Submit review
- View reviews

### Messaging
- Send message
- Receive message

### Administration
- View all users
- Manage listings
- Moderate reviews
- View platform metrics

---

## Diagram Overview

The use case diagram visually maps:

- Each actor to their use cases.
- Shared use cases (e.g., login applies to Guests, Hosts, and Admins).
- System boundaries.

---

## Deliverable

The diagram file is named:


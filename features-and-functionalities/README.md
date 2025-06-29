# Airbnb Clone Backend – Features and Functionalities

This document provides an overview of the core features and functionalities that the Airbnb Clone backend system must support.

The diagram `features-and-functionalities.png` included in this directory visually maps all these features.

---

## 1. User Management

- **User Registration**
  - Sign up with email and password.
  - Store hashed passwords securely.
  - Validate email uniqueness.

- **User Authentication**
  - Login and token-based session management.
  - Role-based access control (guest, host, admin).

- **User Profile Management**
  - View and update profile information.
  - Manage contact details.

---

## 2. Property Management

- **Property Listing**
  - Create new property listings (hosts only).
  - Store property details: name, description, location, price per night.

- **Property Editing**
  - Update existing property details.

- **Property Deletion**
  - Remove listings.

- **Property Search and Browsing**
  - Filter properties by location, price, and availability.

---

## 3. Booking System

- **Booking Creation**
  - Guests can request bookings with start and end dates.

- **Booking Management**
  - Confirm or cancel bookings.
  - Track booking status (pending, confirmed, canceled).

- **Booking History**
  - Users can view their past and upcoming bookings.

---

## 4. Payments

- **Payment Processing**
  - Record payment transactions.
  - Support multiple payment methods (credit card, PayPal, Stripe).

- **Payment Tracking**
  - View payment history linked to bookings.

---

## 5. Reviews

- **Review Submission**
  - Guests can leave reviews for properties.

- **Review Management**
  - Retrieve reviews for properties.

---

## 6. Messaging

- **User Messaging**
  - Send and receive messages between hosts and guests.
  - Store message history.

---

## 7. Administration

- **Admin Dashboard**
  - View all users, properties, bookings, and payments.
  - Moderate listings and reviews.

---

## Deliverable

The diagram `features-and-functionalities.png` visually maps these modules and their relationships.

---

## Repository Structure


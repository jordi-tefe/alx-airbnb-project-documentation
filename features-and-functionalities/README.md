# Airbnb Clone - Backend Features and Functionalities

This document outlines the key features and functionalities of the Airbnb Clone backend system.

## 1. User Management
- **Registration**: Guests or Hosts can register using email and password.
- **Login/Authentication**: JWT-based login; supports OAuth (Google, Facebook).
- **Profile Management**: Users can update profile info including photo, preferences.

## 2. Property Listings Management
- **Add Listings**: Hosts can add properties with name, location, description, and price.
- **Edit/Delete Listings**: Modify or remove properties.
- **Image Upload**: Upload property images (stored via local or cloud storage).

## 3. Search and Filtering
- **Search by**: Location, price range, guests, amenities.
- **Pagination**: Included for large datasets.

## 4. Booking Management
- **Create Bookings**: Guests book properties with validated dates.
- **Cancel Bookings**: Hosts or guests can cancel.
- **Track Booking Status**: Pending, Confirmed, Cancelled, Completed.

## 5. Payment Integration
- **Process Payments**: Using Stripe/PayPal for guests and hosts.
- **Transaction Records**: Logged for admin use.

## 6. Reviews and Ratings
- **Leave Review**: Guests post reviews after booking.
- **Reply to Review**: Hosts can respond.
- **Rating Limits**: 1 to 5 stars.

## 7. Notifications System
- **Send Notifications**: Via email or in-app for booking updates, payments, etc.

## 8. Admin Dashboard
- **Monitor and Control**: View/manage users, bookings, payments.

---

### Exported Diagram
Diagram: `features-and-functionalities/features-overview.png`

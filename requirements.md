# Backend Requirement Specifications - Airbnb Clone

## 1. User Authentication
- **Endpoint**: POST `/api/auth/register`
  - Input: name, email, password
  - Output: JWT token
  - Validation: email must be unique
- **Endpoint**: POST `/api/auth/login`
  - Input: email, password
  - Output: JWT token

## 2. Property Management
- **Endpoint**: POST `/api/properties`
  - Input: title, description, location, price, image
  - Output: property object
  - Auth: Host only

- **Endpoint**: PUT `/api/properties/:id`
  - Input: updates
  - Output: updated object

## 3. Booking System
- **Endpoint**: POST `/api/bookings`
  - Input: user_id, property_id, start_date, end_date
  - Output: booking_id, total_price
  - Validation: Dates must not overlap

- **Performance Criteria**:
  - Response time < 300ms
  - Booking conflict check optimized via indexed date fields

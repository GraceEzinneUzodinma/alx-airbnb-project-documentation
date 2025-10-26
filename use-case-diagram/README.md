# Use Case Diagram

This document contains the use case diagram for the Airbnb Clone project, illustrating the interactions between different actors (users) and the system.

## Actors

### 1. Guest
A user who searches for properties, makes bookings, and leaves reviews.

### 2. Host
A user who lists properties, manages bookings, and communicates with guests.

### 3. Admin
A system administrator who manages users, properties, bookings, and moderates content.

### 4. Payment Gateway
An external system that processes payments securely.

## Use Cases

### Guest Use Cases
- Register Account
- Login
- Search Properties
- View Property Details
- Book Property
- Make Payment
- Cancel Booking
- Write Review
- Send Message to Host
- View Booking History
- Manage Profile

### Host Use Cases
- Register Account
- Login
- Create Property Listing
- Update Property Listing
- Delete Property Listing
- Manage Property Availability
- View Bookings
- Accept/Reject Booking
- Cancel Booking
- Respond to Reviews
- Send Message to Guest
- Manage Profile

### Admin Use Cases
- Login
- Manage Users (View, Edit, Delete)
- Manage Properties (View, Edit, Delete)
- Manage Bookings (View, Monitor)
- View Payment Transactions
- Moderate Reviews
- View System Analytics
- Generate Reports

### System Use Cases
- Send Notifications (Email/SMS)
- Process Payments (via Payment Gateway)
- Validate Booking Dates
- Calculate Total Price
- Generate Booking Confirmation
- Send Payment Receipt

## Relationships

### Include Relationships
- Book Property **includes** Make Payment
- Register Account **includes** Send Confirmation Email
- Cancel Booking **includes** Process Refund (if applicable)

### Extend Relationships
- Search Properties **extends** to Filter by Amenities
- Search Properties **extends** to Sort by Price/Rating
- Book Property **extends** to Apply Promo Code

### Generalization
- Guest and Host both **generalize** from User (both can register, login, manage profile)

## Diagram

The use case diagram visually represents these interactions and is stored as `use-case-diagram.png` in this directory.

## Tools Used
- Draw.io (diagrams.net) for creating the use case diagram

## How to View
Open the `use-case-diagram.png` file to view the complete visual representation of all use cases and their relationships.
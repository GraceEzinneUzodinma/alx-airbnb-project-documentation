# Data Flow Diagram (DFD)

This directory contains the Data Flow Diagram for the Airbnb Clone project, illustrating how data moves through the system.

## What is a Data Flow Diagram?

A Data Flow Diagram (DFD) is a visual representation that shows:
- **External Entities**: Users or systems that interact with the application (Guest, Host, Admin, Payment Gateway)
- **Processes**: Operations that transform or manipulate data (Register User, Create Booking, Process Payment)
- **Data Stores**: Where data is stored (User Database, Property Database, Booking Database)
- **Data Flows**: Arrows showing how data moves between entities, processes, and data stores

## DFD Components

### External Entities
- **Guest**: User searching for and booking properties
- **Host**: User listing and managing properties
- **Admin**: System administrator managing the platform
- **Payment Gateway**: External service processing payments

### Processes
1. User Registration & Authentication
2. Property Management
3. Property Search & Filtering
4. Booking Management
5. Payment Processing
6. Review & Rating System
7. Messaging System
8. Admin Operations

### Data Stores
- **User Database**: Stores user account information
- **Property Database**: Stores property listings and details
- **Booking Database**: Stores reservation information
- **Payment Database**: Stores transaction records
- **Review Database**: Stores reviews and ratings
- **Message Database**: Stores communication history

### Key Data Flows

#### User Registration Flow
Guest/Host → Registration Process → User Database

#### Property Listing Flow
Host → Create Property Process → Property Database

#### Booking Flow
Guest → Search Properties → Property Database → Booking Process → Booking Database → Payment Process → Payment Gateway → Payment Database

#### Review Flow
Guest → Write Review Process → Review Database → Property Database (updates rating)

#### Messaging Flow
Guest/Host → Send Message Process → Message Database → Receive Message Process → Host/Guest

## Diagram

The complete data flow diagram is stored as `data-flow.png` in this directory.

## Tools Used
- Draw.io (diagrams.net) for creating the data flow diagram

## How to View
Open the `data-flow.png` file to view the complete visual representation of data flows in the system.

## Notes
This is a Level 1 DFD showing the main processes and data flows. More detailed Level 2 DFDs can be created for individual processes if needed.
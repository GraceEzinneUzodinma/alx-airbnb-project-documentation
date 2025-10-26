# Flowcharts

This directory contains flowcharts that visualize the workflow and processes of key backend features in the Airbnb Clone project.

## What is a Flowchart?

A flowchart is a diagram that represents a process, showing the steps as boxes of various kinds, and their order by connecting them with arrows. Flowcharts are used to analyze, design, document, or manage a process or program.

## Flowchart Symbols

- **Oval/Rounded Rectangle**: Start/End points
- **Rectangle**: Process/Action steps
- **Diamond**: Decision points (Yes/No questions)
- **Parallelogram**: Input/Output operations
- **Arrows**: Flow direction

## Process: Property Booking

This flowchart visualizes the complete workflow for a guest booking a property, including:

### Steps Covered:
1. **Start**: Guest initiates booking process
2. **User Authentication**: Check if user is logged in
3. **Property Selection**: Guest selects property and dates
4. **Availability Check**: System validates property availability
5. **Price Calculation**: System calculates total booking cost
6. **Payment Processing**: Guest completes payment
7. **Booking Confirmation**: System creates booking record
8. **Notification**: Send confirmation to guest and host
9. **End**: Booking process complete

### Decision Points:
- Is user logged in? (Yes → Continue, No → Redirect to login)
- Is property available? (Yes → Continue, No → Show error)
- Is payment successful? (Yes → Confirm booking, No → Show error)

### Data Interactions:
- Read from: User Database, Property Database
- Write to: Booking Database, Payment Database
- External: Payment Gateway API

## Files

- **property-booking-flowchart.png**: Complete flowchart for the property booking process

## Tools Used
- Draw.io (diagrams.net) for creating the flowchart

## How to View
Open the PNG file to view the complete visual representation of the booking process workflow.
# Movie Ticket Booking Management

## Project Description
A Pega application for managing movie ticket booking requests.

## Case Type
Movie Ticket Request

## Case Lifecycle
1. Initial Stage
2. Availability
3. Approval
4. Booking Execution

## Data Objects
- Movie
- Show

## Key Features
- Submit movie ticket requests
- Check show availability
- Calculate total booking cost
- Approve booking requests
- Process ticket booking
- Booking SLA
- Route requests based on Show Type
- Send booking confirmation email

## SLA
- Goal: 1 day
- Deadline: 2 days

## Routing
- Premium Show → Premium ShowQueue
- Standard Show → Standard ShowQueue

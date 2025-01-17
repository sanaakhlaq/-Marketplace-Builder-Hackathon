# Car Rental E-commerce

This repository contains the architecture, documentation, and code for a Car Rental E-commerce application. This project is part of the Marketplace Builder Hackathon 2025.

---

## Features
1. **User-Friendly Booking System**: Rent cars easily with a streamlined interface.
2. **Dynamic Pricing Models**: Adjust pricing based on rental duration and features.
3. **Secure Payments**: Integrated with secure payment gateways.

---

## Project Structure
- **frontend/**: React/Next.js code for the user interface.
- **backend/**: Node.js/Express API for server-side functionality.
- **database/**: Schema and scripts for MongoDB.
- **diagrams/**: System architecture and process flows.

---

## System Architecture
![System Architecture](diagrams/system-architecture.png)

---

## How to Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Car-Rental-Ecommerce.git

     User Visits Frontend
                                   │
                                   ▼
                            Browse Available Cars
                                   │
                                   ▼
                           View Car Details Page
                                   │
                                   ▼
                          Check Availability and Pricing
                                   │
                                   ▼
                                Place Booking
             ┌────────────────────┼────────────────────┐
             ▼                                         ▼
   Save Booking Details in DB                  Process Payment
             │                                         │
             ▼                                         ▼
 Fetch Booking Confirmation                  Payment Gateway API
      and Invoice Email                               │
             │                                         ▼
             ▼                              Save Payment Details in DB
      Update Car Availability                         │
             │                                         ▼
             ▼                                Send Payment Confirmation
      Display Booking Info                            to User
             │                                         │
             ▼                                         ▼
    Send Confirmation Email                     Final Confirmation
          to User                                      │
             │                                         ▼
             ▼                                       End
           End


   

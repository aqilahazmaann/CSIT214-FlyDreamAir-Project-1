# FlyDreamAir Project Management System

## 1. Project Overview

FlyDreamAir is a comprehensive airline management system developed as part of **CSIT214 IT Project Management**. This project simulates a real-world software system to manage flight booking, seat selection, and reservation tracking, with a primary focus on documenting the project management lifecycle.

## 2. Features

* **Flight Search:** Supports domestic and international route searching.
* **Modular Booking Flow:** A sophisticated, multi-stage booking process separated for better maintainability:
1. **Dashboard:** Search and select flights.
2. **Passenger Management:** Capture and validate passenger details.
3. **Seat Selection:** Interactive grid for choosing cabin seating.
4. **In-Flight Services:** Ancillary service customization.
5. **Checkout & Payment:** Secure transaction simulation.


* **Secure Administration:** Role-Based Access Control (RBAC) simulation for back-office management.
* **State Persistence:** Uses `localStorage` to bridge data between distinct HTML modules, simulating backend session management.

## 3. Technology Stack

* **Frontend:** HTML5, Tailwind CSS (Custom 'blurple' and 'safetyOrange' branding).
* **Logic:** Vanilla JavaScript (ES6+).
* **State Management:** LocalStorage API.

## 4. Project Management Approach

*This project was managed using [Traditional / Agile] project management practices.*

### Key Project Management Deliverables:

* **Business Case:** Strategic justification for the FlyDreamAir system.
* **Project Charter:** Outlining stakeholders, scope, and objectives.
* **WBS & Schedule:** Breakdown of tasks and timeline tracking.
* **Risk Management:** Identification and mitigation strategies for development risks.
* **Effort/Cost Estimation:** Calculation of resource allocation and project costs.

## 5. Getting Started

1. **Clone the repository** to your local machine.
2. **Authentication:** Open `Authentication.html` to log in or register.
* **Default Credentials:** Users can register or use existing mock data (`john@example.com` / `password123`).
* **Admin Access:** Use the "Login as Administration" button (Credentials: `admin@flydreamair.com` / `securepassword123`).



## 6. Project Structure

```text
/
├── Authentication.html     # Login, Registration & Admin Gateway
├── admin.html              # Back-Office Admin Dashboard (Protected)
├── dashboard.html          # Flight Search Interface
├── seat-selection.html     # Modular Seat Selection
├── inflight-services.html  # Modular Ancillary Services
├── payment.html            # Transaction Processing
├── reservations.html       # My Bookings View
└── docs/                   # Project Charter, WBS, and Risk Reports

```

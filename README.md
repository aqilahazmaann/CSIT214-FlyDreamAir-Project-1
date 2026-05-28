# FlyDreamAir Project Management System

## 1. Project Overview

FlyDreamAir is a comprehensive airline management system developed as part of **CSIT214 IT Project Management**. This project simulates a real-world software system to manage flight booking, seat selection, and reservation tracking, with a primary focus on documenting the project management lifecycle.

## 2. Features

* **Flight Search:** Supports domestic and international route searching by origin, destination, and date.
* **Dynamic Booking Flow:** A multi-stage state-driven booking system:
1. **Dashboard:** Search and select flights.
2. **Passenger Management:** Capture and validate passenger details.
3. **Booking Assets:** Choose seats and add ancillary in-flight services.
4. **Checkout & Payment:** Secure transaction simulation.
5. **Reservations:** View, modify, or cancel existing itineraries.


* **State Persistence:** Uses `localStorage` to bridge data between separate HTML modules, simulating backend session management.

## 3. Technology Stack

* **Frontend:** HTML5, Tailwind CSS (for rapid UI development).
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
2. **Open `Authentication.html**` in any modern web browser to start the user session.
3. **Default Credentials:** Users can register or use existing mock data (`john@example.com` / `password123`).

## 6. Project Structure

```text
/
├── Authentication.html   # Login & User Registration
├── dashboard.html        # Flight Search Interface
├── booking-assets.html   # Seat & Services Logic
├── payment.html          # Transaction Processing
├── reservations.html     # My Bookings View
└── docs/                 # Project Charter, WBS, and Risk Reports

```

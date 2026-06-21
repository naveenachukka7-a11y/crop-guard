# 🌱 CropGuard: Unified Web Platform

## 📖 Overview
**CropGuard** is a responsive, single-page web application designed to bridge the gap between agricultural producers and cold storage facilities. By providing real-time crop spoilage countdowns and a seamless routing system, the platform empowers farmers to secure storage for their harvest before it perishes, while giving facility managers the tools to efficiently handle inbound high-risk inventory.

---

## ✨ Core Features

* **Role-Based Access Control:** Secure portal entry with dedicated interfaces for both Farmers and Storage Facility Managers, utilizing an OTP verification system.
* **Dynamic Spoilage Tracking:** Calculates and visually counts down the exact time remaining before a specific crop batch spoils, based on harvest dates and crop-specific baseline data.
* **Storage Routing System:** Allows farmers to view nearby government-subsidized and private cold storage options, compare pricing, and authorize logistics dispatches.
* **Live Manager Dashboard:** Equips storage managers with a real-time queue of incoming high-risk crops, allowing for quick acceptance or declination of batches to manage overhead space.
* **Environment Logging:** Integrates live data visualization tracking core temperature, humidity percentages, and power draw within the cold storage facility.
* **Ledger Generation:** Enables users to instantly export their tracking logs and active batch records into a downloadable PDF format.

---

## 🛠️ Technology Stack

| Component | Technology Used |
| :--- | :--- |
| **Frontend Structure** | HTML5 |
| **Styling** | Vanilla CSS3 (Custom Variables, Flexbox, CSS Grid) |
| **Application Logic** | Vanilla JavaScript (DOM manipulation, interval tracking) |
| **Data Visualization** | Chart.js (Doughnut charts for audits, Line charts for live temp logs) |
| **Document Export** | html2pdf.js |
| **Typography** | Google Fonts (DM Sans, Space Grotesk) |

---

## 🚀 Getting Started

Because this platform is built entirely with client-side technologies, no complex server setup or local environment installation is required to view the interface.

### Prerequisites
A modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, or Safari).

### Running the Application
1. Clone the repository to your local machine:
```bash
   git clone [https://github.com/naveenachukka7-a11y/crop-guard.git](https://github.com/naveenachukka7-a11y/crop-guard.git)
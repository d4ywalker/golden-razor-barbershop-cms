# Golden Razor Barbershop - Appointment Booking & E-Commerce Platform

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/)
[![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)](https://php.net/)
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://mysql.com/)
[![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white)](https://stripe.com/)
[![WhatsApp](https://img.shields.io/badge/WhatsApp_API-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://whatsapp.com/)
[![License](https://img.shields.io/badge/License-Proprietary-red?style=for-the-badge)](https://github.com/d4ywalker)

Golden Razor Barbershop is a full-stack, enterprise-ready Appointment Booking, E-Commerce, and Business Management Web System developed for luxury barbershops, salons, and grooming lounges.

Featuring real-time slot booking, automated Stripe payment processing, instant WhatsApp booking notifications, a product merchandise store, and a comprehensive administration analytics dashboard.

---

## Key Modules & Features

### 1. Online Appointment Booking Engine (index.php / main.php / api_booking.php)
- Dynamic barber selection, service catalog (Haircut, Beard Trim, Royal Shave, VIP Treatment).
- Real-time calendar slot reservation preventing double bookings.
- Interactive seat and schedule selection with price breakdown.

### 2. Stripe Checkout & Online Payment Processing (api_stripe_checkout.php / payment_success.php)
- Automated Stripe payment session integration for card and contactless checkout.
- Webhook status validation and instant receipt generation.
- Graceful cancellation handling (payment_cancel.php).

### 3. Automated WhatsApp & Email Notifications (helper_fonnte.php / helper_email.php)
- Instant booking confirmation sent directly to customer WhatsApp numbers via Fonnte Gateway API.
- Automated appointment reminders and barber schedule dispatch.
- Transactional email confirmations.

### 4. Grooming Products E-Commerce Store (api_product_order.php)
- Built-in online store for pomades, beard oils, styling clays, and grooming tools.
- Shopping cart, delivery address manager, and automated order tracking.

### 5. Administration Control & Analytics Dashboard (admin_dashboard.php / loginadmin.php)
- Live metrics: Daily revenue, total bookings, barber performance, and inventory status.
- Schedule manager: Set barber working hours, holidays, and break intervals.
- Customer CRM: Full customer database with appointment history and lifetime value.

### 6. Customer Self-Service Portal (user_dashboard.php)
- User profile management and past booking records.
- One-click appointment rescheduling and receipt downloads.

---

## Technical Architecture

```
golden-razor-barbershop-cms/
|-- index.php                   # Landing Page & Quick Booking
|-- main.php                    # Full Interactive Booking Flow
|-- admin_dashboard.php         # Master Administration Portal
|-- user_dashboard.php          # Customer Booking & Profile Portal
|-- loginadmin.php / logout.php # Secure Role-Based Authentication
|-- api_booking.php             # Appointment Scheduling REST Endpoint
|-- api_booking_stripe.php      # Stripe Checkout Session Creator
|-- api_stripe_checkout.php     # Direct Stripe Payment Gateway
|-- api_product_order.php       # E-Commerce Product Order API
|-- helper_fonnte.php           # WhatsApp Notification Service
|-- helper_email.php            # Transactional Email Dispatcher
|-- payment_success.php         # Automated Payment Callback & Receipt
|-- payment_cancel.php          # Payment Cancellation Handler
|-- config.php                  # Database Connection & Environment Config
\-- images/                     # UI Graphics, Badges & Product Photos
```

---

## Full Source Code & Deployment Package Access

This project is released under a Proprietary Commercial / Turnkey License.  
The full production-ready source code, database migrations, and deployment packages are available for clients, business owners, and collaborators.

### How to Unlock Full Source Code & Deployment:

1. Reach out directly via Discord, Facebook, or Instagram:
   - Discord: ahmad.bai
   - Facebook: https://www.facebook.com/near.ahmad
   - Instagram: https://instagram.com/ahmadbaihaqi27

2. Donation & Payment Channels:
   - PayPal: vishaka.ahmad@gmail.com
   - USDT (TRC-20 / TRON Network): TY4KH1tfqfPTd3vQ2Vw4EzeEuKEmdsyyjL

3. Services Available:
   - Complete source code ZIP archive & SQL database schema.
   - Custom branding, domain setup, and Stripe/WhatsApp API key integration.
   - Cloud hosting deployment on cPanel, Hostinger, VPS, or AWS.

---

## Author & Support

Developed by [Nex2killer (d4ywalker)](https://github.com/d4ywalker)  
- Discord: ahmad.bai
- Facebook: https://www.facebook.com/near.ahmad
- Instagram: https://instagram.com/ahmadbaihaqi27
- PayPal: vishaka.ahmad@gmail.com
- USDT (TRC-20): TY4KH1tfqfPTd3vQ2Vw4EzeEuKEmdsyyjL
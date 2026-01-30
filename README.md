# LuxeBook - Salon Booking System

Complete booking system for nail techs, hair salons, and beauty professionals.

## Features

### Client Side (index.html)
- 📅 Interactive calendar with availability
- ⏰ Time slots (booked times blocked out)
- 💅 Service menu with pricing & deals
- 👤 Client accounts (sign up/login)
- 📋 View your appointments

### Admin Dashboard (admin.html)
- 🔐 Password protected
- ✅ Confirm/decline appointments
- 🕐 Set availability per day
- ✏️ Edit individual time slots
- 💰 **Change service prices**
- 🏷️ **Create deals & promotions**
- 👥 View all clients

## Quick Start

1. Upload both files to GitHub
2. Enable GitHub Pages
3. Client: `yourusername.github.io/repo-name/`
4. Admin: `yourusername.github.io/repo-name/admin.html`
5. Default password: `admin123`

## Admin Features

### Services & Pricing
- Add new services
- Edit service names, duration, and prices
- Delete services

### Deals & Promotions
- Percentage off (e.g., 20% off)
- Fixed amount off (e.g., $10 off)
- Set new price (e.g., Now $40)
- Optional expiration dates

### Availability Management
- Add single days
- Quick add: Weekdays or All 7 days
- Edit individual time slots per day
- Remove specific slots or entire days

## Customization

### Change Admin Password
In admin.html, find and change:
```javascript
const ADMIN_PASSWORD = 'admin123';
```

### Change Colors
Edit the CSS variables in either file:
```css
:root {
    --cream: #F9F6F1;
    --charcoal: #1A1A1A;
    --gold: #B8956E;
    --sage: #A8B5A0;
}
```

## Data Storage

Uses localStorage (browser-based):
- ✅ Data persists on same device
- ✅ Works offline
- ⚠️ Not synced across devices

For production with multiple devices, connect to a backend database.

## Files

```
├── index.html  # Client booking page
├── admin.html  # Admin dashboard
└── README.md
```

---
**Made for Lanez Web Co** 🚀

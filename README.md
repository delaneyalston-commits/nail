# LuxeBook - Salon Booking System

A complete booking system for nail techs, hair salons, and beauty professionals with client accounts and admin dashboard.

## Features

### Client Side (`index.html`)
- 📅 Interactive calendar showing available dates
- ⏰ Time slot selection (booked times are blocked out)
- 💅 Service menu with pricing
- 👤 Client account creation & login
- 📋 View your upcoming appointments
- ✅ Booking confirmation with pending status

### Admin Dashboard (`admin.html`)
- 🔐 Password-protected access
- 📊 Stats overview (pending, confirmed, weekly bookings)
- ✅ Confirm or decline appointment requests
- 🕐 Set your available dates and time slots
- 👥 View all registered clients
- 📱 Fully responsive design

## Quick Start

1. Download both files (`index.html` and `admin.html`)
2. Open `index.html` in your browser for the client booking page
3. Open `admin.html` for the admin dashboard
4. Default admin password: `admin123`

## GitHub Pages Deployment

1. Create a new repository on GitHub
2. Upload both HTML files
3. Go to **Settings** → **Pages**
4. Set Source to **Deploy from branch**
5. Select **main** branch and **/ (root)**
6. Your site will be live at:
   - Client: `https://yourusername.github.io/repo-name/`
   - Admin: `https://yourusername.github.io/repo-name/admin.html`

## How It Works

### For You (Admin)
1. Go to `admin.html` and log in with your password
2. Add your available dates and time slots in the "Availability" section
3. When clients book, you'll see pending requests in the dashboard
4. Confirm or decline appointments as needed

### For Your Clients
1. They visit your main page (`index.html`)
2. Create an account (name, email, phone, password)
3. Select an available date on the calendar
4. Choose a time slot (booked times are grayed out)
5. Select a service and complete booking
6. Their appointment shows as "pending" until you confirm

## Customization

### Change Admin Password
In `admin.html`, find this line and change it:
```javascript
const ADMIN_PASSWORD = 'admin123';
```

### Change Services
In `index.html`, edit the services section:
```html
<div class="service-item" data-service="yourservice" data-price="50" data-duration="60">
    <div class="service-info">
        <h4>Your Service Name</h4>
        <span>60 minutes</span>
    </div>
    <div class="service-price">$50</div>
</div>
```

### Change Colors
Modify the CSS variables at the top of either file:
```css
:root {
    --cream: #F9F6F1;
    --charcoal: #1A1A1A;
    --blush: #E8D5D0;
    --rose: #C9A9A6;
    --gold: #B8956E;
    --sage: #A8B5A0;
}
```

## Data Storage

This system uses browser localStorage, meaning:
- ✅ Data persists on the same device/browser
- ✅ Works offline after first load
- ⚠️ Data is device-specific (not synced across devices)
- ⚠️ Clearing browser data will erase bookings

For a production system with multiple devices, you'd want to connect to a backend database.

## Tech Stack

- Pure HTML/CSS/JavaScript
- No frameworks or dependencies
- Google Fonts (Cormorant Garamond, DM Sans)
- localStorage for data persistence

## Files

```
├── index.html    # Client booking page
├── admin.html    # Admin dashboard (password protected)
└── README.md     # This file
```

## License

MIT License - feel free to use for your business!

---

**Made for Lanez Web Co** 🚀

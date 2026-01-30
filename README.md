# LuxeBook - Salon Booking Website

A beautiful, responsive booking website for nail techs, hair salons, and beauty professionals.

![Preview](https://img.shields.io/badge/Status-Ready-green)

## Features

### Client View
- 📅 Interactive calendar with availability indicators
- ⏰ Time slot selection
- 💅 Service menu with pricing
- 📝 Booking form with confirmation

### Provider Dashboard
- 📆 Set available dates and time ranges
- 👥 View upcoming appointments
- 📊 Quick stats overview
- ❌ Remove availability slots

## Quick Start

1. Download or clone this repo
2. Open `index.html` in your browser
3. That's it! No build process needed.

## GitHub Pages Deployment

1. Push this repo to GitHub
2. Go to **Settings** → **Pages**
3. Set Source to **Deploy from branch**
4. Select **main** branch and **/ (root)**
5. Your site will be live at `https://yourusername.github.io/repo-name`

## Customization

### Change Services
Edit the services in the HTML under the `services-list` div:

```html
<div class="service-item" data-service="yourservice" data-price="50">
    <div class="service-info">
        <h4>Your Service Name</h4>
        <span>Duration</span>
    </div>
    <div class="service-price">$50</div>
</div>
```

### Change Colors
Modify the CSS variables at the top of the `<style>` section:

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

## Tech Stack

- Pure HTML/CSS/JavaScript
- No frameworks or dependencies
- Google Fonts (Cormorant Garamond, DM Sans)

## License

MIT License - feel free to use for your clients!

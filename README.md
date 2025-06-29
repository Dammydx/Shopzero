# Shopzero - Multi-Vendor eCommerce Marketplace

A complete, responsive, PWA-ready multi-vendor eCommerce marketplace built with React, Vite, Tailwind CSS, and Supabase.

## 🌎 Live Site
[View the portfolio](#) *(https://dammydx.github.io/Shopzero/)*

## 🚀 Features

### Customer Features
- Browse products from multiple vendors
- Advanced search and filtering
- Wishlist and compare products
- Secure checkout with Paystack
- Order tracking and history
- User profiles and settings
- Flash sales and deals
- PWA support with offline functionality

### Vendor Features
- Vendor registration and approval system
- Product management (add, edit, delete)
- Order management
- Earnings dashboard
- Inventory tracking
- Image uploads (up to 5 per product)

### Admin Features
- Admin dashboard with analytics
- Vendor approval and management
- Product moderation
- Order oversight
- User management
- Flash sales configuration
- System settings

## 🛠️ Tech Stack

- **Frontend**: React 18, TypeScript, Vite
- **Styling**: Tailwind CSS
- **Animations**: Framer Motion
- **Backend**: Supabase (Database, Auth, Storage)
- **Payments**: Paystack
- **State Management**: Zustand
- **PWA**: Vite PWA Plugin
- **Icons**: Lucide React

## 🏗️ Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── auth/           # Authentication components
│   ├── cart/           # Shopping cart components
│   ├── layout/         # Layout components
│   └── ui/             # Generic UI components
├── hooks/              # Custom React hooks
├── layouts/            # Page layouts
├── lib/                # External library configurations
├── pages/              # Page components
│   ├── admin/          # Admin pages
│   ├── auth/           # Authentication pages
│   ├── customer/       # Customer pages
│   ├── static/         # Static pages
│   └── vendor/         # Vendor pages
├── store/              # Zustand state stores
├── types/              # TypeScript type definitions
└── utils/              # Utility functions
```

## 🚀 Getting Started



## 🗄️ Database Schema

The application uses the following main tables:
- `users` - User profiles and authentication
- `vendors` - Vendor business information
- `products` - Product catalog with images and pricing
- `orders` & `order_items` - Order management
- `admin_settings` - System configuration
- `contact_messages` - Customer inquiries

## 🔐 Authentication

The app supports multiple authentication methods:
- Email/Password (no email confirmation required)
- Google OAuth
- Facebook OAuth
- Password reset functionality

### Admin Access
- Default admin password: `****`
- Can be changed in admin settings
- Access admin panel at `/admin`

## 💳 Payment Integration

Paystack is integrated for secure payments:
- Supports all major payment methods
- Secure tokenization
- Real-time transaction status
- Webhook support for order updates

## 📱 PWA Features

The app is PWA-ready with:
- Service worker for offline functionality
- App manifest for installation
- Responsive design for all devices
- Push notification capability (can be extended)

## 🎨 Design System

### Colors
- Primary: Teal (#1abc9c)
- Accent: Midnight Blue (#1a1f36)  
- Background: Cream White (#fefefe)
- CTA Buttons: Indigo (#4b0082)

### Typography
- Body: Inter font family
- Headings: Poppins font family

## 🚀 Deployment

The app can be deployed to various platforms:
- Github page (recommended)




## 📄 License

This project is licensed under the MIT License.

## 🆘 Support

For support and questions:
- Email: daramolaire@gmail.com
- Create an issue in the repository
- Check the FAQ section

## 🚧 Roadmap

Upcoming features:
- Mobile app (React Native/Capacitor)
- Advanced analytics
- Multi-language support
- Advanced search with AI
- Subscription products
- Affiliate system

---

Built with ❤️ By Dammy
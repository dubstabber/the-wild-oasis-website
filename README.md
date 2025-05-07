# 🏡 The Wild Oasis - Luxury Cabin Booking Platform

![Next.js](https://img.shields.io/badge/Next.js-14.2-black?style=for-the-badge&logo=next.js)
![React](https://img.shields.io/badge/React-18-blue?style=for-the-badge&logo=react)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4-38B2AC?style=for-the-badge&logo=tailwind-css)
![Supabase](https://img.shields.io/badge/Supabase-2.49-3ECF8E?style=for-the-badge&logo=supabase)
![NextAuth](https://img.shields.io/badge/NextAuth-5.0-666?style=for-the-badge)

## 🌄 Project Overview

The Wild Oasis is a full-stack luxury cabin booking platform built with modern web technologies. Set in the heart of the Italian Dolomites, this application offers guests a seamless experience to browse, book, and manage reservations for high-end mountain retreats.

### ✨ Live Demo: [Visit The Wild Oasis](https://the-wild-oasis-website-roan-eta.vercel.app)

## 🚀 Key Features

- **Responsive, Modern UI** - Beautiful and intuitive interface with TailwindCSS
- **Authentication System** - Secure Google OAuth integration via NextAuth
- **Cabin Browsing & Filtering** - Filter accommodations by capacity and other criteria
- **Interactive Booking System** - Date selection with availability checking
- **User Profiles** - Personal account management for guests
- **Reservation Management** - View and manage bookings
- **Optimized Performance** - Server-side rendering and static generation with Next.js App Router

## 💻 Technical Implementation

### Architecture

This application follows a modern architecture using Next.js 14's App Router for server components and routing, with Supabase as the backend database and authentication provider.

### Technology Stack

- **Frontend:**
  - Next.js 14 (App Router)
  - React 18 with Server and Client Components
  - TailwindCSS for styling
  - date-fns for date manipulation
  - react-day-picker for date selection UI

- **Backend & Data:**
  - Supabase for database and storage
  - Next.js API routes for server-side operations
  - NextAuth for authentication

- **Deployment:**
  - Optimized for Vercel deployment
  - Environment variable management
  - Production-ready build configuration

## 🔧 Development Workflow

### Setup

```bash
# Clone repository
git clone https://github.com/yourusername/the-wild-oasis-website.git
cd the-wild-oasis-website

# Install dependencies
npm install

# Set up environment variables (see .env.example)

# Start development server
npm run dev
```

Visit [http://localhost:3000](http://localhost:3000) to see the application.

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run prod` - Build and start production server
- `npm run lint` - Run ESLint

## 🧠 What I Learned

- Next.js App Router architecture and best practices
- Server Component optimization for improved performance
- Integration of Supabase with Next.js for backend operations
- Secure authentication flows with NextAuth
- Complex state management in a booking application
- Responsive design implementation with TailwindCSS
- Date manipulation and availability logic for booking systems

## 📝 Future Enhancements

- Admin dashboard for property management
- Payment integration with Stripe
- Enhanced filtering and search capabilities
- Multilingual support
- Review and rating system
- Mobile application with React Native

## 🔒 Environment Variables

To run this project, you need to set up the following environment variables:

```
AUTH_GOOGLE_ID=your_google_client_id
AUTH_GOOGLE_SECRET=your_google_client_secret
# Add Supabase credentials and other necessary variables
```

## 📱 Responsive Design

The Wild Oasis is fully responsive and optimized for all device sizes, from mobile phones to large desktop screens.

## 🌟 Acknowledgments

- UI design inspired by luxury hospitality websites
- Special thanks to the Next.js and Supabase communities
- Icons provided by Heroicons

---

*Developed with ❤️ by Łukasz Kwiecień - Frontend Developer specializing in React and Next.js applications*

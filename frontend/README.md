# Docto - Doctor Appointment Booking System

A modern, responsive web application for booking appointments with trusted doctors. Built with React, Vite, and Tailwind CSS.

## 🌟 Features

- **Doctor Listings**: Browse through an extensive list of qualified doctors across various specialties
- **Specialty Search**: Filter doctors by medical specialties (General Physician, Gynecologist, Dermatologist, Pediatricians, Neurologist, Gastroenterologist)
- **Appointment Booking**: Easy-to-use interface for scheduling appointments
- **User Authentication**: Secure login system for patients
- **User Profile Management**: Manage personal information and view appointment history
- **Responsive Design**: Fully responsive UI that works seamlessly on desktop, tablet, and mobile devices
- **Interactive Navigation**: Smooth navigation with React Router

## 🚀 Tech Stack

- **Frontend Framework**: React 18.3.1
- **Build Tool**: Vite 6.0.5
- **Styling**: Tailwind CSS 3.4.17
- **Routing**: React Router DOM 7.1.1
- **State Management**: React Context API
- **Code Quality**: ESLint with React plugins

## 📁 Project Structure

```
frontend/
├── public/              # Static assets
├── src/
│   ├── assets/         # Images, icons, and static data
│   ├── components/     # Reusable React components
│   │   ├── Header.jsx
│   │   ├── NavBar.jsx
│   │   ├── SpecialityMenu.jsx
│   │   └── TopDoctors.jsx
│   ├── context/        # React Context for state management
│   │   └── AppContext.jsx
│   ├── pages/          # Page components
│   │   ├── Home.jsx
│   │   ├── Doctors.jsx
│   │   ├── About.jsx
│   │   ├── Contact.jsx
│   │   ├── Login.jsx
│   │   ├── Appointment.jsx
│   │   ├── MyProfile.jsx
│   │   └── MyAppointments.jsx
│   ├── App.jsx         # Main application component
│   ├── main.jsx        # Application entry point
│   └── index.css       # Global styles
├── index.html
├── tailwind.config.js
├── vite.config.js
└── package.json
```

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Docto/frontend
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` (or the port shown in your terminal)

## 📜 Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the project for production
- `npm run preview` - Preview the production build locally
- `npm run lint` - Run ESLint to check code quality

## 🎨 Key Components

### Header
Landing page header with call-to-action for booking appointments.

### SpecialityMenu
Interactive menu displaying different medical specialties with clickable icons.

### TopDoctors
Showcases the top 10 doctors with their details and availability status.

### NavBar
Responsive navigation bar with user authentication dropdown and menu links.

## 🔧 Configuration

### Tailwind CSS
Custom configuration in [`tailwind.config.js`](tailwind.config.js):
- Primary color: `#5f6FFF`
- Custom grid template for auto-fill layouts
- Responsive breakpoints for mobile-first design

### Vite
Configuration in [`vite.config.js`](vite.config.js) includes React plugin for optimal development experience.

## 📱 Responsive Design

The application is fully responsive with breakpoints:
- **Mobile**: < 640px
- **Tablet**: 640px - 1024px
- **Desktop**: > 1024px

## 🔐 Authentication

The application includes a user authentication system with:
- Login/Signup functionality
- User profile management
- Protected routes for authenticated users
- Logout capability

## 🎯 Features in Development

- Contact page implementation
- Appointment management system
- User profile editing
- Payment integration
- Email notifications

## 📄 License

This project is private and proprietary.

## 👥 Contributing

Please contact the project maintainers for contribution guidelines.

## 📞 Support

For support, please contact the development team.

---

# 🏆 Gold Inventory Management System (GIMS)

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-Softmusk%20Info%20Pvt%20LTD-green.svg)
![React](https://img.shields.io/badge/React-18.2.0-blue)
![Firebase](https://img.shields.io/badge/Firebase-9.x-orange)

</div>

## 📋 Overview

GIMS is a comprehensive full-stack web application designed specifically for gold industry intermediaries. It streamlines the management of raw gold material orders and sales for jewelers, providing a robust platform for inventory management, secure transactions, and business analytics.

## ✨ Key Features

- 🔐 **Secure Authentication**
  - Firebase-based authentication system
  - Role-based access control
  - Secure user sessions

- 📦 **Inventory Management**
  - Real-time inventory tracking
  - Product categorization by gold karats
  - Stock level monitoring
  - Automated stock alerts

- 💼 **Business Operations**
  - Customer and supplier management
  - GST and commission rate configuration
  - Real-time gold rate updates
  - Transaction processing

- 📊 **Reporting & Analytics**
  - Real-time transaction reports
  - Sales analytics
  - Custom invoice generation
  - Business performance metrics

## 🏗️ System Architecture

### Frontend
- **Framework**: React.js
- **Build Tool**: Vite
- **Styling**: CSS3
- **State Management**: React Hooks

### Backend
- **Database**: Firebase Realtime Database
- **Authentication**: Firebase Authentication
- **Hosting**: Firebase Hosting

## 📁 Project Structure

```
src/
├── components/          # Reusable UI components
├── pages/              # Page-level components
├── firebase/           # Firebase configuration
├── styles/             # Global styles
├── utils/              # Utility functions
├── hooks/              # Custom React hooks
├── context/            # React context providers
└── assets/             # Static assets
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v14.0.0 or higher)
- npm (v6.0.0 or higher)
- Firebase account

### Installation

1. Clone the repository
```bash
git clone https://github.com/your-username/gold-inventory-system.git
cd Goldproject
```

2. Install dependencies
```bash
npm install
```

3. Configure Firebase
   - Create a new Firebase project
   - Enable Authentication (Email/Password)
   - Set up Realtime Database
   - Add your Firebase configuration to `src/firebase/firebaseConfig.js`

4. Start the development server
```bash
npm run dev
```

## 🔧 Configuration

### Firebase Setup
1. Go to [Firebase Console](https://console.firebase.google.com/)
2. Create a new project
3. Enable Authentication → Sign-in method → Email/Password
4. Enable Realtime Database
5. Copy Firebase configuration to `src/firebase/firebaseConfig.js`

## 📱 Core Modules

### Admin Module
- Secure admin authentication
- System configuration management
- User access control

### Home Module
- Profile management
- GST configuration
- Commission rate settings
- Gold rate management

### Master Entry Module
- Customer management
- Supplier management
- Real-time dashboard

### Inventory Module
- Product management
- Stock control
- Sales processing

### Account Module
- Customer database
- Supplier database
- Transaction history

### Report Module
- Transaction reports
- Invoice generation
- Analytics dashboard

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the Softmusk Info Pvt LTD License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Mohammadharshad Mulla**
- GitHub: [Your GitHub Profile]
- LinkedIn: [Your LinkedIn Profile]

## 🙏 Acknowledgments

- Special thanks to Softmusk Info Pvt LTD for their support
- All contributors who have helped shape this project

---

<div align="center">
Made with ❤️ by Mohammadharshad M Mulla
</div>

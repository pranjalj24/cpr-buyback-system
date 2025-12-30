# CPR Screen Buyback Management System

## 📱 About This Project

A comprehensive web application for managing iPhone screen buyback operations at CPR (Cell Phone Repair by Assurant).

### ✨ Key Features

- **User Authentication**: Secure login and registration system
- **Batch Management**: Create, edit, and track screen buyback batches
- **Supplier Optimization**: Automatically calculates optimal supplier allocation to maximize revenue
- **Live Calculations**: Real-time pricing updates as you enter quantities
- **Price Management**: Easy-to-use pricing table for managing supplier rates
- **Dashboard Analytics**: Track total batches, analyzed batches, and revenue
- **Export Functionality**: Download batch data as JSON files
- **Multi-User Support**: Role-based access (Admin & User roles)

### 🏢 Supported Suppliers

- Mobile Sentrix
- Phone LCD Parts
- Injured Gadgets

### 📱 Supported Models

- iPhone 16 Series (Pro Max, Pro, Plus, Standard)
- iPhone 15 Series (Pro Max, Pro, Plus, Standard)
- Easily add more models through Settings

### 🔐 Demo Login

- **Username**: admin
- **Password**: admin123

## 🚀 How to Use

1. **Login**: Use the demo credentials or create a new account
2. **Create a Batch**: Click "New Batch" to start
3. **Enter Quantities**: Input OEM/Refurb and Aftermarket screen quantities
4. **Run Analysis**: Click "Run Analysis" to optimize supplier allocation
5. **Save**: Save your batch for future reference
6. **View Reports**: Check dashboard for analytics and revenue tracking

## 💾 Data Storage

All data is stored locally in your browser using localStorage. This means:
- Data persists between sessions
- No external server required
- Data is private to each user's browser
- Clearing browser data will reset the application

## 🛠️ Technical Details

- **Framework**: React 18
- **Styling**: Tailwind CSS
- **Storage**: Browser localStorage
- **Hosting**: GitHub Pages compatible

## 📊 Workflow

1. **Inventory Entry**: Enter screen quantities for each iPhone model
2. **Automatic Optimization**: System finds best supplier prices for each item
3. **Revenue Calculation**: Calculates maximum revenue based on optimal allocation
4. **Supplier Breakdown**: Shows which screens go to which supplier
5. **Export & Tracking**: Save and track historical batches

## 🎨 Color Scheme

- Primary: CPR Red (#DC2626)
- Secondary: White
- Accents: Green (success), Blue (info), Gray (neutral)

## 👤 Created By

Developed for CPR (Cell Phone Repair by Assurant) internal operations.

---

**Version**: 1.0  
**Last Updated**: December 2024

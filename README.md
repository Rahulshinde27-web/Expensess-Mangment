# ExpensePro ERP - Expense Management System

A complete web-based expense management system that works offline and can be deployed anywhere.

## Features

- 💰 **Income & Expense Tracking**
- 👥 **Multi-user Support** with Admin/User roles
- 📊 **Dashboard with Charts** (Chart.js)
- 📱 **Responsive Design** for mobile and desktop
- 💾 **Offline Support** with IndexedDB
- 📎 **File Attachments** support
- 📈 **Reports & Analytics**
- 🖨️ **Export to CSV/Excel/PDF**
- 🔄 **Data Backup & Restore**
- 🔔 **Notifications**
- 📅 **Calendar View**
- 👤 **User Profiles**
- ⚙️ **Customizable Settings**

## Quick Start

### Option 1: Deploy to GitHub Pages

1. Fork this repository
2. Enable GitHub Pages in repository settings
3. Set source to `main` branch
4. Your app will be available at `https://[username].github.io/expensepro/`

### Option 2: Deploy to any Web Host

1. Clone the repository
2. Upload all files to your web server
3. Access via your domain

### Option 3: Run Locally

1. Clone the repository
2. Open `index.html` in a modern browser
3. No server required!

## Usage

### Default Login Credentials

- **Admin**: `admin` / `admin123`
- **User**: `user` / `user123`

### Adding Transactions

1. Click "Add Transaction" in sidebar
2. Fill in transaction details
3. Add attachments if needed
4. Submit for approval

### Admin Functions

- Approve/Reject transactions
- Manage users
- View system analytics
- Backup/restore data
- Configure settings

### Reports

- Generate custom reports
- Filter by date, type, category
- Export in multiple formats
- Save report templates

## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Charts**: Chart.js
- **Database**: IndexedDB
- **Date Handling**: Luxon
- **Export**: SheetJS (xlsx)
- **Icons**: Font Awesome
- **PWA**: Service Worker

## Browser Support

- Chrome 60+
- Firefox 55+
- Safari 11+
- Edge 79+

## Data Storage

All data is stored locally in your browser using IndexedDB. No data is sent to any server unless you configure a backend.

## Backup & Security

- Regular backups recommended
- Export data to JSON/CSV
- Store backups securely
- Use strong passwords

## Customization

### Change Default Settings

Edit `config.json` to modify:
- App name and version
- Default categories
- Currency settings
- Feature flags

### Add Custom Categories

1. Edit `config.json` categories section
2. Add new income/expense categories
3. The system will automatically pick them up

### Change Theme Colors

Edit `styles/main.css` CSS variables:
```css
:root {
  --primary-color: #4361ee;
  --success-color: #10b981;
  --danger-color: #ef4444;
  /* ... other colors */
}

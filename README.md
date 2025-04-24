🚀 Project Overview: Deployment link 👇

https://billing-and-stock-management-system.vercel.app/ 

🎨 Frontend
Built with: React ⚛️ (Functional Components + Hooks)

State Management: useState, useEffect

UI/UX:

Responsive design 📱 for all screen sizes

Smooth animations with Framer Motion 🎭

Scrollable modals for mobile compatibility 🔄

⚙️ Backend Integration
Database: Supabase 🛢

Features:

Real-time data sync 🔄

Custom SQL functions for inventory control 📊

📄 PDF Generation
Invoices:

Created using jsPDF 🖨

Tabular format with jspdf-autotable 📑

Features:

Automatic tax calculations 🧾

🔗 QR Code Payments
Technology: qrcode.react 🏦

Features:

UPI QR Code with pre-filled payment amount 💰

UPI ID: sabarivasan1239@okhdfcbank 🆔

⚠️ Error Handling
Robust handling of database errors 🛡

Graceful fallbacks for schema changes 🛠

Clear, user-friendly error messages 🔔

🗄 Database Schema

📦 Products Table

Column	Type
id	Primary Key
name	String
price	Number
quantity	Number
category	String
created_at	Timestamp

💳 Transactions Table

Column	Type
id	Primary Key
customer_name	String
customer_phone	String
total_amount	Number
payment_method	String (Optional)
items	JSON Array (Purchased Items)
created_at	Timestamp

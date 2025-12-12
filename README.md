# Rice Mill Slot Booking System 🌾

**Built by:** Poonam Suryawanshi & Prisha Patil

A real-time web application that helps rice mill owners manage customer flow and reduce waiting time. Customers can book processing slots online, see available slots in real-time, and get automated time allocation based on the number of rice bags. Admins can monitor bookings, close specific slots, and all updates reflect instantly.

---

## Features ✅
- Real-time slot booking for customers
- Automated time allocation (1 bag = 15 minutes)
- Admin dashboard to view all bookings and close slots
- Daily reset of slots at midnight
- Responsive UI for both desktop and mobile
- Prevents overcrowding and reduces waiting time

---

## How It Works 🛠
1. Mill operates from **9 AM to 6 PM**.  
2. Customers select the number of bags → system calculates start and end times automatically.  
3. Customers book slots in real-time; updates are reflected for everyone instantly.  
4. Admin can view all bookings and close any slot for maintenance or holidays.  
5. All slots reset automatically every 24 hours.

---

## Tech Stack 💻
**Frontend:** HTML, CSS, JavaScript, Socket.io (Client)  
**Backend:** Node.js, Express.js, Socket.io (Server), Node-cron  
**Database:** SQLite3

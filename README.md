# The Wild Oasis Admin

A user-friendly web app designed for hotel staff to efficiently manage operations, including reservations, cabin assignments, and revenue tracking.

## 🚀 Live Demo
[The Wild Oasis Admin - Live](https://main.d1w0l9jtjchm1q.amplifyapp.com/dashboard)

## 📂 Tech Stack
- **Frontend:** React.js, React-Query, React-Hook-Form, Styled-Components
- **Backend & Database:** Supabase
- **Deployment:** AWS Amplify

## ✨ Features
- **Reservations Management:**
  - Check-in/check-out guests
  - Edit and filter bookings
  - Paginated booking list for easy navigation
- **Cabin Management:**
  - Add, edit, and remove cabins
  - Filter and sort cabins
- **Analytics Dashboard:**
  - Displays occupancy rates, revenue, and booking trends
- **Dark Mode:**
  - Intuitive toggle for dark mode
- **Authentication & Security:**
  - Secure login via Supabase authentication
  

## 📦 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/SumitNub12/the-wild-oasis-dashboard.git
   cd the-wild-oasis-dashboard
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables:
   - Create a `.env` file in the root directory and add your Supabase credentials:
     ```env
    
     VITE_SUPABASE_KEY=your-anon-key
     ```
4. Start the development server:
   ```bash
   npm start
   ```

## 🛠 Deployment
The project is deployed on **AWS Amplify**. To deploy manually:
1. Build the project:
   ```bash
   npm run build
   ```
2. Deploy using AWS Amplify following their setup guide.

## 🤝 Contributing
Feel free to contribute by submitting pull requests or reporting issues.


---

Happy coding! 🚀


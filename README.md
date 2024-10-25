# Finance Tracker Web Application

A full-stack web application for tracking personal finances, including income and expenses. Built with React.js for the frontend and Node.js for the backend, featuring real-time charts and analytics.

## 🌟 Features

- **Income & Expense Tracking**: Easy-to-use interface for managing financial transactions
- **Visual Analytics**: Interactive charts using Chart.js for financial data visualization
- **Transaction History**: Comprehensive view of past transactions
- **Category Management**: Organize transactions by categories
- **Date-based Filtering**: Filter transactions by date using react-datepicker
- **Responsive Design**: Works seamlessly on desktop and mobile devices

## 🚀 Live Demo

- Frontend: [Netlify Deployment](https://your-netlify-url.netlify.app)
- Backend API: [Render Deployment](https://finance-tracker-es0o.onrender.com/api/v1)

## 🛠️ Built With

- **Frontend**:
  - React.js 18.2.0
  - Chart.js 4.2.0 & react-chartjs-2 5.2.0
  - Styled Components 5.3.6
  - Axios 1.3.2
  - React DatePicker 4.10.0
  - Moment.js 2.29.4

- **Backend**:
  - Node.js
  - Express.js
  - MongoDB
  - Deployed on Render

## 📋 Prerequisites

- Node.js (version 16 or higher)
- npm (Node Package Manager)
- Modern web browser
- Internet connection

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/finance-tracker.git
   cd finance-tracker
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a `.env` file in the root directory:
   ```env
   REACT_APP_API_URL=https://finance-tracker-es0o.onrender.com/api/v1
   ```

4. **Run the development server**
   ```bash
   npm start
   ```

5. **Build for production**
   ```bash
   npm run build
   ```

## 📱 Usage

1. **Add Income/Expense**
   - Click on the respective button to add new transaction
   - Fill in the required details (title, amount, date, category)
   - Submit the form

2. **View Transactions**
   - See all transactions listed chronologically
   - Filter by date or category
   - View detailed breakdown in charts

3. **Analytics**
   - Check total income vs expenses
   - View category-wise breakdown
   - Analyze trends through visual charts

## 🔗 API Endpoints

### Income Routes
- GET `/api/v1/get-incomes` - Fetch all incomes
- POST `/api/v1/add-income` - Add new income
- DELETE `/api/v1/delete-income/:id` - Delete specific income

### Expense Routes
- GET `/api/v1/get-expenses` - Fetch all expenses
- POST `/api/v1/add-expense` - Add new expense
- DELETE `/api/v1/delete-expense/:id` - Delete specific expense

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## 👏 Acknowledgments

- Chart.js for data visualization
- Styled Components for styling
- React DatePicker for date selection
- Moment.js for date formatting

## 📞 Contact

Your Name - [your-email@example.com](mailto:your-email@example.com)

Project Link: [https://github.com/your-username/finance-tracker](https://github.com/your-username/finance-tracker)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
#   f i n a n c e _ t r a c k e r _ f r o n t e n d 
 
 

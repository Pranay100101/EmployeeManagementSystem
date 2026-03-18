# Employee Management System (EMS)

A modern React-based Employee Management System built with Vite, featuring admin and employee dashboards for task management.

## 🚀 Features

- **Admin Dashboard**: Create and assign tasks to employees
- **Employee Dashboard**: View and manage personal tasks
- **Task Management**: Create, accept, complete, and track tasks
- **Authentication**: Secure login system for admins and employees
- **Responsive Design**: Modern UI with Tailwind CSS

## 🛠️ Tech Stack

- **Frontend**: React 18, Vite
- **Styling**: Tailwind CSS
- **Icons**: React Icons
- **Build Tool**: Vite
- **Deployment**: Vercel

## 📋 Prerequisites

- Node.js (v16 or higher)
- npm or yarn

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/ems.git
   cd ems
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   ```
   http://localhost:5173
   ```

## 🔐 Login Credentials

### Admin Access
- **Email**: admin@example.com
- **Password**: 123

### Employee Access
- **Email**: e@e.com | **Password**: 123
- **Email**: employee2@example.com | **Password**: 123
- **Email**: employee3@example.com | **Password**: 123
- **Email**: employee4@example.com | **Password**: 123
- **Email**: employee5@example.com | **Password**: 123
- **Email**: neha@example.com | **Password**: 123

## 📁 Project Structure

```
ems/
├── public/
├── src/
│   ├── components/
│   │   ├── Auth/
│   │   │   └── Login.jsx
│   │   ├── Dashboard/
│   │   │   ├── AdminDashboard.jsx
│   │   │   └── EmployeeDashboard.jsx
│   │   └── TaskList/
│   │       ├── AcceptTask.jsx
│   │       ├── CompleteTask.jsx
│   │       ├── FailedTask.jsx
│   │       ├── NewTask.jsx
│   │       └── TaskList.jsx
│   ├── context/
│   │   └── AuthProvider.jsx
│   ├── utils/
│   │   └── localStorage.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── package.json
├── vite.config.js
├── tailwind.config.js
└── README.md
```

## 🎯 Usage

1. **Login** with admin or employee credentials
2. **Admin**: Create tasks and assign them to employees
3. **Employee**: View tasks, accept new tasks, mark as completed
4. **Task States**: New → Active → Completed/Failed

## 🚀 Deployment

### Vercel (Recommended)
1. Push code to GitHub
2. Connect GitHub to Vercel
3. Deploy automatically

### Manual Build
```bash
npm run build
npm run preview
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Your Name**
- GitHub: [@your-username](https://github.com/your-username)
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/your-profile)

---

⭐ **Star this repo** if you found it helpful!

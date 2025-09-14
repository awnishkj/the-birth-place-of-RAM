# 🕉️ The Divine of Ayodhya - Ram Janmabhoomi

A comprehensive web application dedicated to the sacred city of Ayodhya, the birthplace of Lord Ram. This platform provides pilgrims and devotees with essential information about temples, accommodations, food, travel, and spiritual experiences in Ayodhya.

## ✨ Features

### 🏛️ Sacred Places
- **Ram Mandir** - Complete information about the main temple
- **Kanak Bhawan** - Details about Sita's palace
- **Saryu Ghat** - Information about the holy river banks
- **Hanuman Garhi** - Guide to the Hanuman temple
- **Raja Dasharath Mahal** - Historical palace information

### 🏨 Accommodation & Services
- **Dharmshala** - Religious guest houses
- **Hotels** - Modern accommodation options
- **Bhojnalaya** - Traditional dining halls
- **Restaurants** - Local dining options

### 🎯 Additional Features
- **Travel Guide** - Transportation and route information
- **Prasad Information** - Sacred offerings and their significance
- **Photo Gallery** - Beautiful images of Ayodhya
- **Contact Form** - Get in touch with us
- **Registration** - User account management

## 🛠️ Technology Stack

### Frontend
- **React 18** with TypeScript
- **Vite** for fast development and building
- **Tailwind CSS** for styling
- **Shadcn/ui** for modern UI components
- **React Router** for navigation
- **React Query** for data fetching
- **Lucide React** for icons

### Backend
- **Node.js** with Express
- **Nodemailer** for email functionality
- **CORS** for cross-origin requests
- **dotenv** for environment variables

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/awnishkj/the-birth-place-of-RAM.git
   cd the-birth-place-of-RAM
   ```

2. **Install Frontend Dependencies**
   ```bash
   cd frontend
   npm install
   ```

3. **Install Backend Dependencies**
   ```bash
   cd ../server
   npm install
   ```

4. **Environment Setup**
   Create a `.env` file in the server directory:
   ```env
   EMAIL_USER=your-email@gmail.com
   EMAIL_PASS=your-app-password
   ```

### Running the Application

1. **Start the Backend Server**
   ```bash
   cd server
   npm run dev
   ```
   Server will run on `http://localhost:5000`

2. **Start the Frontend Development Server**
   ```bash
   cd frontend
   npm run dev
   ```
   Frontend will run on `http://localhost:5173`

### Building for Production

1. **Build the Frontend**
   ```bash
   cd frontend
   npm run build
   ```

2. **Start Production Server**
   ```bash
   cd server
   npm start
   ```

## 📁 Project Structure

```
the-divine-of-ayodhya/
├── frontend/                 # React frontend application
│   ├── src/
│   │   ├── components/      # Reusable UI components
│   │   ├── pages/          # Page components
│   │   ├── lib/            # Utility functions
│   │   └── App.tsx         # Main application component
│   ├── public/             # Static assets
│   └── package.json        # Frontend dependencies
├── server/                  # Node.js backend
│   ├── server.js           # Express server setup
│   ├── .env               # Environment variables (not in repo)
│   └── package.json        # Backend dependencies
└── README.md               # Project documentation
```

## 🎨 UI Components

The application uses a modern design system with:
- **Responsive Design** - Works on all device sizes
- **Dark/Light Mode** - Theme switching capability
- **Accessibility** - WCAG compliant components
- **Modern Animations** - Smooth transitions and effects

## 📧 Contact Form Integration

The contact form is integrated with email functionality:
- Form submissions are sent via Nodemailer
- Gmail SMTP integration
- Form validation and error handling
- Success/failure notifications

## 🔧 Development

### Available Scripts

**Frontend:**
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build

**Backend:**
- `npm run dev` - Start development server with nodemon
- `npm start` - Start production server

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the ISC License.

## 🙏 Acknowledgments

- Dedicated to Lord Ram and the sacred city of Ayodhya
- Thanks to all devotees and pilgrims who inspired this project
- Built with love and devotion for the spiritual community

## 📞 Contact

For any queries or suggestions, please use the contact form on the website or reach out to us at ayodhyablossom@gmail.com

---

**Jai Shri Ram! 🚩**

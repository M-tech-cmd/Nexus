# 📊 Nexus Dashboard

A modern, feature-rich admin dashboard built with React, featuring real-time data visualization, multiple chart types, and a comprehensive e-commerce management system.

![Nexus Dashboard](https://github.com/M-tech-cmd/Nexus/blob/326334d593f480ae10f2d0f45101410d33e2f007/src/data/hero.jpg)
![Status](https://github.com/M-tech-cmd/Nexus/blob/326334d593f480ae10f2d0f45101410d33e2f007/src/data/preview.jpg)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

## 🚀 Live Demo

**[View Live Demo](https://nexus-three-rust.vercel.app)**

## ✨ Features

### 📈 Dashboard & Analytics
- **Real-time Statistics**: Track earnings, customers, products, and sales
- **Interactive Charts**: Line, Area, Bar, Pie, Financial, and Pyramid charts
- **Revenue Tracking**: Comprehensive revenue updates with visual representations
- **Performance Metrics**: Monitor key business indicators at a glance

### 🛍️ E-commerce Management
- **Product Catalog**: Manage inventory with detailed product information
- **Order Management**: Track and process customer orders
- **Customer Database**: Comprehensive customer relationship management
- **Sales Analytics**: Detailed sales performance tracking

### 📊 Data Visualization
- **Multiple Chart Types**: 
  - Line Charts for trend analysis
  - Area Charts for cumulative data
  - Bar Charts for comparisons
  - Pie Charts for distribution
  - Financial Charts for stock/trading data
  - Pyramid Charts for hierarchical data
  - Stacked Charts for multi-series data
- **Color Mapping**: Temperature and data intensity visualization
- **Sparklines**: Compact inline charts for quick insights

### 🎨 User Interface
- **Theme Customization**: Multiple color themes (Blue, Green, Purple, Red, Indigo, Orange)
- **Dark/Light Mode**: Full theme switching capability
- **Responsive Design**: Optimized for desktop, tablet, and mobile
- **Modern UI Components**: Built with Syncfusion and Tailwind CSS

### 📅 Productivity Apps
- **Calendar**: Full-featured scheduling with drag-and-drop
- **Kanban Board**: Task management with customizable workflows
- **Rich Text Editor**: Advanced document editing capabilities
- **Color Picker**: Professional color selection tools

### 👥 Team Management
- **Employee Directory**: Manage team members and roles
- **Customer Portal**: Track customer interactions and history
- **User Profiles**: Customizable user settings and preferences

## 🛠️ Tech Stack

### Frontend
- **React 18.x** - UI framework
- **React Router DOM** - Navigation and routing
- **Tailwind CSS** - Utility-first styling
- **Syncfusion EJ2** - Premium UI components

### Data Visualization
- **Recharts** - Chart library
- **Syncfusion Charts** - Advanced charting components
- **D3.js** - Data-driven visualizations

### Icons & Assets
- **React Icons** - Comprehensive icon library
  - Remix Icons (ri)
  - Bootstrap Icons (bs)
  - Feather Icons (fi)
  - Ant Design Icons (ai)
  - Material Design Icons (md)
  - Hero Icons (hi)
  - Tabler Icons (ti)
  - Game Icons (gi)

### Development Tools
- **ESLint** - Code linting with Airbnb style guide
- **Create React App** - Build tooling
- **Git** - Version control

## 📦 Installation

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/nexus-dashboard.git
   cd nexus-dashboard
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm start
   ```

4. **Open in browser**
   ```
   http://localhost:3000
   ```

## 🏗️ Build for Production

```bash
npm run build
```

This creates an optimized production build in the `build/` folder.

## 📁 Project Structure

```
nexus/
├── public/
│   ├── index.html
│   └── favicon.ico
├── src/
│   ├── components/
│   │   ├── Charts/          # Chart components
│   │   ├── Button.jsx       # Reusable button component
│   │   ├── Cart.jsx         # Shopping cart
│   │   ├── ChartsHeader.jsx # Chart header component
│   │   ├── Chat.jsx         # Chat interface
│   │   ├── Footer.jsx       # Footer component
│   │   ├── Header.jsx       # Page header
│   │   ├── Navbar.jsx       # Navigation bar
│   │   ├── Notification.jsx # Notification center
│   │   ├── Sidebar.jsx      # Sidebar navigation
│   │   ├── ThemeSettings.jsx # Theme customization
│   │   └── UserProfile.jsx  # User profile dropdown
│   ├── contexts/
│   │   └── ContextProvider.js # Global state management
│   ├── data/
│   │   ├── dummy.js         # Mock data
│   │   └── avatar*.jpg      # User avatars
│   ├── pages/
│   │   ├── Calendar.jsx     # Calendar page
│   │   ├── ColorPicker.jsx  # Color picker tool
│   │   ├── Customers.jsx    # Customer management
│   │   ├── Ecommerce.jsx    # Dashboard home
│   │   ├── Editor.jsx       # Rich text editor
│   │   ├── Employees.jsx    # Employee management
│   │   ├── Kanban.jsx       # Kanban board
│   │   ├── Orders.jsx       # Order management
│   │   └── Charts/          # Chart pages
│   ├── App.js               # Main app component
│   ├── App.css              # Global styles
│   └── index.js             # Entry point
├── .eslintrc.js             # ESLint configuration
├── .gitignore
├── package.json
├── tailwind.config.js       # Tailwind configuration
└── README.md
```

## 🎨 Available Themes

- **Blue Theme** (#1A97F5)
- **Green Theme** (#03C9D7)
- **Purple Theme** (#7352FF)
- **Red Theme** (#FF5C8E)
- **Indigo Theme** (#1E4DB7)
- **Orange Theme** (#FB9678)

## 🌐 Pages & Routes

### Dashboard
- `/` or `/ecommerce` - Main dashboard

### Management Pages
- `/orders` - Order management
- `/employees` - Employee directory
- `/customers` - Customer management

### Applications
- `/calendar` - Event scheduling
- `/kanban` - Task board
- `/editor` - Rich text editor
- `/color-picker` - Color selection tool

### Charts
- `/line` - Line chart visualization
- `/area` - Area chart visualization
- `/bar` - Bar chart visualization
- `/pie` - Pie chart visualization
- `/financial` - Financial/candlestick charts
- `/color-mapping` - Color intensity mapping
- `/pyramid` - Pyramid chart
- `/stacked` - Stacked column chart

## 🔧 Configuration

### Environment Variables
Create a `.env` file in the root directory:

```env
ESLINT_NO_DEV_ERRORS=true
DISABLE_ESLINT_PLUGIN=false
```

### Tailwind CSS
Custom configuration in `tailwind.config.js` for:
- Custom colors
- Extended utilities
- Responsive breakpoints

## 🐛 Known Issues

- Circular dependency warnings in ESLint (non-blocking)
- Web search tool compatibility (informational only)

## 🚀 Deployment

### Vercel (Recommended)
1. Push your code to GitHub
2. Import project in Vercel dashboard
3. Deploy automatically

### Netlify
1. Build the project: `npm run build`
2. Deploy the `build/` folder
3. Configure redirects for React Router

## 📝 License

This project is licensed under the MIT License.

## 👨‍💻 Author

**Manuel**
- GitHub: (https://github.com/M-tech-cmd)

## 🙏 Acknowledgments

- [Syncfusion](https://www.syncfusion.com/) - Premium UI components
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [React Icons](https://react-icons.github.io/react-icons/) - Icon library
- [Recharts](https://recharts.org/) - Chart library

## 📧 Support

For support, kimaniemma20.com or open an issue on GitHub.

## 🗺️ Roadmap

- [ ] Backend API integration
- [ ] User authentication
- [ ] Real-time data updates
- [ ] Export functionality for reports
- [ ] Advanced filtering and search
- [ ] Multi-language support
- [ ] Mobile app version

---

⭐ Star this repository if you find it helpful!

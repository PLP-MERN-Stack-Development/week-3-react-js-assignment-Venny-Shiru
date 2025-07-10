# 🎯 TaskManager Pro - React Application

A modern, responsive task management application built with React.js, JSX, and Tailwind CSS. This project demonstrates advanced component architecture, state management, API integration, and contemporary UI/UX design patterns.

## 🚀 Live Demo

🌐 **[View Live Application](https://your-deployed-app-url.vercel.app)**

## 📸 Screenshots

### Light Theme - Task Manager
![Task Manager Light Theme](https://via.placeholder.com/800x400/ffffff/000000?text=Task+Manager+Light+Theme)

### Dark Theme - Task Manager
![Task Manager Dark Theme](https://via.placeholder.com/800x400/1f2937/ffffff?text=Task+Manager+Dark+Theme)

### Users Directory
![Users Directory](https://via.placeholder.com/800x400/f3f4f6/374151?text=Users+Directory+with+API+Integration)

### Mobile Responsive Design
![Mobile View](https://via.placeholder.com/400x600/3b82f6/ffffff?text=Mobile+Responsive+Design)

## ✨ Features

### 🎨 **Modern UI/UX**
- Beautiful, contemporary design with smooth animations
- Fully responsive layout (mobile, tablet, desktop)
- Dark/Light theme toggle with system preference detection
- Interactive elements with hover effects and transitions
- Professional color scheme and typography

### 📋 **Task Management**
- ✅ Add new tasks with instant validation
- ✅ Mark tasks as completed/uncompleted
- ✅ Delete tasks with confirmation
- ✅ Filter tasks (All, Active, Completed)
- ✅ Search tasks in real-time
- ✅ Persistent storage using localStorage
- ✅ Task counters and status indicators

### 👥 **User Directory**
- 📡 Fetch user data from JSONPlaceholder API
- 🔍 Search users by name, email, or company
- 📄 Pagination with customizable page size
- 🎭 Grid/List view toggle
- ⚡ Loading states and error handling
- 🔄 Retry functionality for failed requests

### 🛠 **Technical Features**
- 🏗️ Component-based architecture with reusable components
- 🪝 Modern React hooks (useState, useEffect, useContext)
- 🎯 Custom hooks for localStorage integration
- 🎨 Tailwind CSS for utility-first styling
- 📱 Mobile-first responsive design
- ♿ Accessibility features and keyboard navigation

## 🏗️ Project Structure

```
src/
├── components/
│   ├── Button.jsx              # Reusable button component
│   ├── Card.jsx                # Card container component
│   ├── Navbar.jsx              # Navigation component
│   ├── Footer.jsx              # Footer component
│   └── Layout.jsx              # Main layout wrapper
├── hooks/
│   └── useLocalStorage.js      # Custom hook for localStorage
├── context/
│   └── ThemeContext.js         # Theme management context
├── pages/
│   ├── TaskManager.jsx         # Task management page
│   └── Users.jsx               # Users directory page
├── App.jsx                     # Main application component
└── index.js                    # Application entry point
```

## 🛠️ Technologies Used

- **React 18** - Modern React with hooks
- **Tailwind CSS** - Utility-first CSS framework
- **Lucide React** - Beautiful icon library
- **JSONPlaceholder API** - Mock REST API for testing
- **JavaScript ES6+** - Modern JavaScript features
- **Vite** - Fast build tool and development server

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/taskmanager-pro.git
   cd taskmanager-pro
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173`

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 📦 Component Documentation

### Button Component
```jsx
<Button 
  variant="primary"     // primary, secondary, danger, outline
  size="md"             // sm, md, lg
  onClick={handleClick}
  disabled={false}
>
  Click Me
</Button>
```

### Card Component
```jsx
<Card 
  hover={true}          // Enable hover effects
  className="p-6"       // Additional classes
>
  <h3>Card Title</h3>
  <p>Card content</p>
</Card>
```

### Custom Hook Usage
```jsx
const [tasks, setTasks] = useLocalStorage('tasks', []);
```

## 🎯 API Integration

The application integrates with the JSONPlaceholder API to demonstrate:
- Fetching data from external APIs
- Handling loading states
- Error handling and retry logic
- Data transformation and filtering
- Pagination implementation

**API Endpoint**: `https://jsonplaceholder.typicode.com/users`

## 🎨 Theme System

The application features a complete theme system:
- **Light Theme**: Clean, modern light interface
- **Dark Theme**: Easy-on-the-eyes dark interface
- **Theme Persistence**: Remembers user preference
- **System Integration**: Respects system theme preference

## 📱 Responsive Design

Breakpoints used:
- **Mobile**: < 640px
- **Tablet**: 640px - 1024px
- **Desktop**: > 1024px

## 🔧 State Management

### Local State
- Component-level state using `useState`
- Form inputs and UI interactions
- Loading and error states

### Context API
- Global theme state management
- Theme toggle functionality
- Provider pattern implementation

### LocalStorage
- Persistent task storage
- Theme preference storage
- Custom hook abstraction

## 🚀 Deployment

### Deploy to Vercel
```bash
npm run build
npx vercel --prod
```

### Deploy to Netlify
```bash
npm run build
# Upload dist folder to Netlify
```

### Deploy to GitHub Pages
```bash
npm run build
# Configure GitHub Pages to serve from dist folder
```

## 📈 Performance Optimizations

- Component memoization where appropriate
- Efficient re-rendering strategies
- Lazy loading for better performance
- Optimized bundle size with Vite
- Image optimization and lazy loading

## ♿ Accessibility Features

- Semantic HTML structure
- ARIA labels and roles
- Keyboard navigation support
- Focus management
- Color contrast compliance
- Screen reader compatibility

## 🧪 Testing

Future enhancements could include:
- Unit tests with Jest and React Testing Library
- E2E tests with Cypress
- Component testing with Storybook
- Performance testing with Lighthouse

## 🔮 Future Enhancements

- [ ] User authentication and authorization
- [ ] Real-time collaboration features
- [ ] Task categories and tags
- [ ] Due dates and reminders
- [ ] Drag-and-drop task reordering
- [ ] Export/import functionality
- [ ] Advanced filtering and sorting
- [ ] Task analytics and reporting
- [ ] PWA capabilities
- [ ] Offline support

## 🐛 Known Issues

- None currently identified

## 📚 Learning Objectives Achieved

✅ **Component Architecture**: Built reusable, composable components  
✅ **State Management**: Implemented complex state logic with hooks  
✅ **API Integration**: Fetched and managed external data  
✅ **Responsive Design**: Created mobile-first, responsive layouts  
✅ **Modern CSS**: Utilized Tailwind CSS utility-first approach  
✅ **User Experience**: Implemented intuitive interactions and feedback  
✅ **Code Organization**: Structured code for maintainability  
✅ **Error Handling**: Implemented robust error states and recovery  

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/new-feature`
3. Commit your changes: `git commit -m 'Add new feature'`
4. Push to the branch: `git push origin feature/new-feature`
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Your Name**
- GitHub: [@yourusername](https://github.com/yourusername)
- Email: your.email@example.com
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/yourprofile)

## 🙏 Acknowledgments

- [React Documentation](https://reactjs.org/docs) - For comprehensive React guides
- [Tailwind CSS](https://tailwindcss.com) - For the amazing utility-first CSS framework
- [Lucide Icons](https://lucide.dev) - For beautiful, consistent icons
- [JSONPlaceholder](https://jsonplaceholder.typicode.com) - For the mock API
- [Vite](https://vitejs.dev) - For the lightning-fast build tool

## 📞 Support

If you have any questions or run into issues:
1. Check the [Issues](https://github.com/yourusername/taskmanager-pro/issues) page
2. Create a new issue if your problem isn't already reported
3. Provide as much detail as possible including:
   - Steps to reproduce
   - Expected behavior
   - Actual behavior
   - Screenshots if applicable

---

**Built with ❤️ for educational purposes**

*This project demonstrates modern React development practices and serves as a comprehensive example of component architecture, state management, and API integration.*
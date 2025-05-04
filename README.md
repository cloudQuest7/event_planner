# Gatherion - Modern Event Planning Platform 🎉
<div align="center">
  <img src="./public/images/gatherion.jpg" alt="Gatherion UI" width="600"/>
  <p><em>Gatherion's modern dark theme interface</em></p>
</div>
An interactive event planning platform built with Next.js, Framer Motion, and Tailwind CSS, featuring a stunning dark theme UI and fluid animations.

## ✨ Features

- **Interactive UI**: Smooth animations and transitions using Framer Motion
- **Real-time Updates**: Dynamic RSVP system with instant notifications
- **Responsive Design**: Fully responsive across all devices
- **Dark Theme**: Modern dark theme with gradient accents
- **Event Management**:
  - Create and manage events
  - RSVP functionality
  - Attendee tracking
  - Event themes and customization
  - Location management
  - Capacity controls

## 🚀 Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/gatherion.git
```

2. Install dependencies:
```bash
cd gatherion
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## 🛠️ Built With

- **Frontend**: Next.js 13 with App Router
- **Styling**: Tailwind CSS
- **Animations**: Framer Motion
- **Icons**: Lucide Icons
- **Type Safety**: TypeScript

## 🐛 Known Issues

Currently facing deployment issues due to:
1. TypeScript errors related to unused variables
2. Multiple attribute warnings in JSX
3. Missing dependency warnings in useEffect hooks

To fix deployment issues:
```typescript
// 1. Remove unused variables or mark them with underscore
const _unused = '';

// 2. Fix JSX attributes
// Instead of:
<button transition-transform transition-all>
// Use:
<button className="transition-transform transition-all">

// 3. Add missing dependencies to useEffect
useEffect(() => {
  // effect
}, [dependency1, dependency2]);
```

## 📝 Todo

- [ ] Fix TypeScript errors
- [ ] Resolve deployment issues
- [ ] Add user authentication
- [ ] Implement database integration
- [ ] Add event sharing functionality

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👩‍💻 Author

Anjali Jayakumar

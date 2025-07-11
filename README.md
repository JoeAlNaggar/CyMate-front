# CyMate - Advanced Cybersecurity Platform 🔐

> **Develop & Defend Together** - Step Into The New Era Of Cybersecurity & Developer Innovation

[![Next.js](https://img.shields.io/badge/Next.js-14.2.5-black?style=flat-square&logo=next.js)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-18.2.0-blue?style=flat-square&logo=react)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?style=flat-square&logo=typescript)](https://typescriptjs.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4.17-38B2AC?style=flat-square&logo=tailwind-css)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

## 🌟 Overview

CyMate is a comprehensive cybersecurity platform that combines automated security tools, collaborative community features, and innovative developer resources into one unified ecosystem. Built with modern web technologies, it empowers cybersecurity professionals, developers, and organizations to detect threats, share knowledge, and build secure solutions together.

### ✨ Key Features

- **🛡️ Advanced Security Toolkit**: Malware detection, network scanning, web vulnerability assessment, and threat intelligence
- **👥 Collaborative Community**: Forums, blogs, Q&A, and knowledge sharing
- **💡 Innovation Hub**: Inspiration gallery, tool marketplace, and integration platform
- **📊 Real-time Monitoring**: Risk tracking, threat analysis, and security insights
- **🔐 Enterprise-Grade Security**: Authentication, authorization, and data protection
- **🎨 Modern UI/UX**: Responsive design with dark/light themes and smooth animations

## 🚀 Getting Started

### Prerequisites

- **Node.js** 18.x or higher
- **npm** 9.x or higher (or yarn/pnpm)
- **Git** for version control

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/JoeAlNaggar/CyMate-front.git
   cd CyMate-front
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000) to see the application.


## 🏗️ Architecture

### Tech Stack

**Frontend:**
- [Next.js 14.2.5](https://nextjs.org/) - React framework with App Router
- [React 18.2.0](https://reactjs.org/) - UI library
- [TypeScript 5](https://typescriptjs.org/) - Type safety
- [Tailwind CSS 3.4.17](https://tailwindcss.com/) - Utility-first CSS framework
- [Framer Motion](https://framer.com/motion/) - Animation library
- [Radix UI](https://radix-ui.com/) - Accessible component primitives
- [Lucide React](https://lucide.dev/) - Beautiful icons

**State Management & Forms:**
- React Context API for authentication
- React Hook Form with Zod validation
- Axios for API communications

**Styling & Components:**
- Shadcn/ui component library
- CSS variables for theming
- Responsive design with mobile-first approach
- Glass morphism and neumorphism effects

### Project Structure

```
cymate-react18.2/
├── app/                          # Next.js App Router
│   ├── (auth)/                   # Authentication pages
│   │   ├── login/
│   │   ├── register/
│   │   ├── forgot-password/
│   │   └── verify-email/
│   ├── (main)/                   # Main application pages
│   │   ├── dashboard/
│   │   ├── toolkit/              # Security tools
│   │   │   ├── malware-detection/
│   │   │   ├── network-scanning/
│   │   │   ├── web-vulnerability/
│   │   │   └── threat-intelligence/
│   │   ├── community/            # Community features
│   │   ├── innovation/           # Innovation hub
│   │   │   ├── inspiration/
│   │   │   └── tools/
│   │   ├── settings/
│   │   └── components/           # Shared components
│   ├── contexts/                 # React contexts
│   ├── lib/                      # Utilities and configurations
│   └── services/                 # API services
├── components/                   # Reusable UI components
│   └── ui/                       # Shadcn/ui components
├── lib/                          # Shared utilities
└── public/                       # Static assets
```


## 🛡️ Security Features

### Toolkit Components

1. **Malware Detection**
   - File upload scanning
   - URL analysis
   - Real-time threat assessment
   - Integration with VirusTotal API

2. **Network Scanning**
   - IP scanning and discovery
   - Port scanning
   - DNS analysis
   - Firewall testing
   - Protocol analysis

3. **Web Vulnerability Scanner**
   - OWASP Top 10 coverage
   - Security misconfiguration detection
   - Cryptographic failure analysis
   - SSRF detection
   - Component vulnerability assessment

4. **Threat Intelligence**
   - Real-time threat feeds
   - IOC (Indicators of Compromise) analysis
   - Risk assessment
   - Threat landscape insights

### Authentication & Authorization

- JWT-based authentication
- Secure session management
- Role-based access control
- Password encryption with bcrypt
- Email verification system

## 👥 Community Features

- **Discussion Forums**: Topic-based discussions and Q&A
- **Blog Platform**: Technical articles and insights
- **Knowledge Sharing**: Best practices and tutorials
- **Collaboration Tools**: Project sharing and team formation
- **Reputation System**: Effort scoring and community recognition

## 💡 Innovation Hub

- **Inspiration Gallery**: Real-world project showcases
- **Tool Marketplace**: Third-party security tools integration
- **Resource Library**: Templates, guides, and documentation
- **Developer Portal**: API documentation and SDKs

## 🔧 Configuration

### Theme Configuration

The application supports both light and dark themes with automatic system preference detection. Customize themes in:

- `app/globals.css` - CSS variables and base styles
- `tailwind.config.ts` - Tailwind theme configuration
- `components/theme-provider.tsx` - Theme context provider

### Component Customization

Components are built with Radix UI and styled with Tailwind CSS. Customize in:

- `components/ui/` - Base UI components
- `app/(main)/components/` - Application-specific components
- `lib/utils.ts` - Utility functions

## 📱 Responsive Design

CyMate is fully responsive and optimized for:

- **Desktop**: Full-featured experience with sidebar navigation
- **Tablet**: Adaptive layout with collapsible sidebar
- **Mobile**: Touch-friendly interface with bottom navigation


### Code Style

- Use TypeScript for type safety
- Follow ESLint configuration
- Use Prettier for code formatting
- Write meaningful commit messages
- Add comments for complex logic

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


**Built with ❤️ for the cybersecurity community**

*CyMate - Where security meets innovation* 
# Yoom

A modern video calling application built with Next.js and Stream Video SDK, offering seamless video conferencing experiences similar to Zoom.

## 🚀 Features

- **High-Quality Video Calls**: Crystal clear video and audio communication
- **Real-time Communication**: Powered by Stream Video SDK for low-latency connections
- **User Authentication**: Secure authentication with Clerk
- **Modern UI**: Clean and intuitive interface built with Tailwind CSS
- **Meeting Scheduling**: Schedule meetings with react-datepicker integration
- **Responsive Design**: Works seamlessly across desktop and mobile devices
- **Dark Theme**: Professional dark theme for comfortable viewing

## 🛠️ Tech Stack

- **Framework**: Next.js 14.1.4
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Video SDK**: Stream Video React SDK
- **Authentication**: Clerk
- **UI Components**: Radix UI primitives
- **Date Picker**: React DatePicker
- **Icons**: Lucide React

## 📦 Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd yoom
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
Create a `.env.local` file in the root directory and add:
```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
NEXT_PUBLIC_STREAM_API_KEY=your_stream_api_key
STREAM_SECRET_KEY=your_stream_secret_key
```

4. Run the development server:
```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 🔧 Configuration

### Clerk Authentication
The app uses Clerk for user authentication with a custom appearance configuration:
- Custom logo integration
- Dark theme styling
- Social button variants

### Stream Video SDK
Integrated with Stream's Video SDK for:
- Real-time video communication
- Audio/video controls
- Screen sharing capabilities
- Meeting management

## 🚀 Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## 🎨 Styling

The application uses:
- **Tailwind CSS** for utility-first styling
- **Custom CSS variables** for theme consistency
- **Radix UI** components for accessible UI primitives
- **Dark theme** as the primary design system

## 🔐 Authentication

User authentication is handled by Clerk with:
- Social login options
- Custom branding
- Secure session management
- User profile management

## 📱 Responsive Design

Yoom is fully responsive and optimized for:
- Desktop computers
- Tablets
- Mobile phones
- Various screen sizes and orientations

## 🌟 Key Dependencies

- `@clerk/nextjs` - Authentication
- `@stream-io/video-react-sdk` - Video calling functionality
- `@radix-ui/*` - UI components
- `tailwindcss` - Styling
- `lucide-react` - Icons
- `react-datepicker` - Date/time selection

## 🔗 Links

- [Stream Video SDK Documentation](https://getstream.io/video/docs/)
- [Clerk Documentation](https://clerk.com/docs)
- [Next.js Documentation](https://nextjs.org/docs)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)

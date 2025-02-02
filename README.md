# Multilingual FAQ Component

A beautiful and accessible FAQ component built with React, TypeScript, and shadcn/ui that supports multiple Indian languages.


## Features

- 🌐 Support for 10 Indian languages plus English
- 🎨 Beautiful dark theme UI with smooth animations
- ♿ Fully accessible with keyboard navigation
- 📱 Responsive design for all screen sizes
- 🔄 Interactive accordion-style questions
- ⚡ Built with performance in mind

### Supported Languages

- English
- हिंदी (Hindi)
- বাংলা (Bengali)
- తెలుగు (Telugu)
- मराठी (Marathi)
- தமிழ் (Tamil)
- ગુજરાતી (Gujarati)
- ಕನ್ನಡ (Kannada)
- മലയാളം (Malayalam)
- ଓଡିଆ (Odia)

## Tech Stack

- React 18
- TypeScript
- Tailwind CSS
- shadcn/ui components
- Lucide React icons

## Getting Started

1. Clone the repository:
```bash
git clone <repository-url>
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

## Project Structure

```
src/
├── components/
│   └── ui/          # shadcn/ui components
├── App.tsx          # Main FAQ component
├── index.css        # Global styles
└── main.tsx        # Application entry point
```

## Usage

The FAQ component can be easily integrated into any React application. Simply import and use the component:

```tsx
import App from './App';

function YourComponent() {
  return (
    <div>
      <App />
    </div>
  );
}
```

## Customization

### Adding New Languages

To add a new language, update the `faqData` array in `App.tsx`:

```tsx
const faqData = [
  {
    question: {
      en: "Your question in English",
      // Add your new language
      newLang: "Your question in new language"
    },
    answer: {
      en: "Your answer in English",
      // Add your new language
      newLang: "Your answer in new language"
    }
  }
];
```

### Styling

The component uses Tailwind CSS for styling. You can customize the appearance by modifying the classes in `App.tsx` or updating the Tailwind configuration in `tailwind.config.js`.

## Accessibility

The FAQ component follows WCAG guidelines and includes:

- Proper ARIA labels
- Keyboard navigation
- Focus management
- High contrast colors
- Screen reader support

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- [shadcn/ui](https://ui.shadcn.com/) for the beautiful UI components
- [Lucide](https://lucide.dev/) for the icons
- All contributors who help maintain and improve this project
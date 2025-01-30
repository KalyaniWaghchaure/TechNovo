# TechNova - Modern Technology Solutions Website

A modern, responsive website built with React and Bootstrap for TechNova, showcasing technology solutions and services.

##  Features

- Modern and responsive design
- Animated hero section with gradient background
- Service cards with hover effects
- Statistics section
- Call-to-action sections
- Mobile-first approach
- SEO-friendly structure

## Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v14.0.0 or later)
- npm (v6.0.0 or later)

## Installation

1. Clone the repository
```bash
git clone https://github.com/your-username/technova.git
cd technova
```

2. Install dependencies
```bash
npm install
```

3. Start the development server
```bash
npm run dev
```

The application will open in your default browser at `http://localhost:3000`

## Dependencies

- React (v18.0.0 or later)
- React Bootstrap
- React Router DOM
- AOS (Animate On Scroll)

## Project Structure

```
technova/
├── public/
│   ├── images/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── common/
│   │   │   ├── Header.jsx
│   │   │   └── Footer.jsx
│   │   └── sections/
│   │       ├── Hero.jsx
│   │       └── Services.jsx
│   ├── pages/
│   │   ├── Home.jsx
│   │   ├── About.jsx
│   │   ├── Services.jsx
│   │   └── Contact.jsx
│   ├── styles/
│   │   └── main.css
│   ├── App.jsx
│   └── index.js
└── README.md
```

##  Available Pages

1. **Home Page**
   - Hero section with animated illustration
   - Services overview
   - Statistics section
   - Call-to-action sections

2. **Services Page**
   - Detailed service descriptions
   - Service features
   - Case studies

3. **About Page**
   - Company information
   - Team members
   - Mission and vision

4. **Contact Page**
   - Contact form
   - Office location map
   - Contact information

## Development

### Running Tests
```bash
npm test
```

### Building for Production
```bash
npm run build
```

The build files will be located in the `dist` directory.

## 🔧 Customization

### Colors
The main colors can be modified in `src/styles/main.css`:
```css
:root {
  --primary-color: #0d6efd;
  --secondary-color: #0a58ca;
  --text-color: #333333;
  /* Add more custom colors as needed */
}
```

### Images
Replace the placeholder images in the `public/images` directory with your own images.

## Responsive Design

The website is fully responsive and optimized for:
- Mobile devices (320px and up)
- Tablets (768px and up)
- Desktops (1024px and up)
- Large screens (1440px and up)

## Performance Optimizations

- Lazy loading of images
- Code splitting
- Optimized assets
- Minimized bundle size

##  Environment Variables

Create a `.env` file in the root directory:
```env
REACT_APP_API_URL=your_api_url
REACT_APP_GOOGLE_MAPS_KEY=your_google_maps_key
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Acknowledgments

- React team for the amazing framework
- Bootstrap team for the responsive design system
- All contributors who have helped with the project

## Contact

For any queries or support, please contact:
- Email: kalyaniwaghchaure2@gmail.com


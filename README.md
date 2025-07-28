# Decision Point: QuikForms Integration Strategy

An interactive presentation designed to guide leadership through strategic options for solving PDF form-filling bottlenecks.

## Features

- **Interactive Option Comparison**: Tab-based interface to explore three strategic paths
- **Visual Analysis**: Radar chart comparing options across key business drivers
- **Responsive Design**: Optimized for desktop and mobile viewing
- **Modern UI**: Built with Tailwind CSS and Chart.js
- **Smooth Animations**: Fade-in effects and interactive elements

## Local Development

1. Clone the repository
2. Start the local development server:
   ```bash
   npm run dev
   # or
   python3 -m http.server 8000
   ```
3. Open [http://localhost:8000](http://localhost:8000) in your browser

## Deployment

### Deploy to Vercel

1. Install Vercel CLI (if not already installed):
   ```bash
   npm i -g vercel
   ```

2. Deploy to Vercel:
   ```bash
   vercel
   ```

3. For production deployment:
   ```bash
   vercel --prod
   ```

### Alternative: Deploy via Vercel Dashboard

1. Push your code to GitHub
2. Connect your repository to Vercel
3. Vercel will automatically detect the static site and deploy it

## Project Structure

```
quik/
├── index.html          # Main HTML file
├── vercel.json         # Vercel configuration
├── package.json        # Project metadata
├── .gitignore         # Git ignore rules
└── README.md          # This file
```

## Technologies Used

- **HTML5**: Semantic markup
- **Tailwind CSS**: Utility-first CSS framework
- **Chart.js**: Interactive radar chart
- **Vanilla JavaScript**: Interactive functionality
- **Vercel**: Deployment platform

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## License

MIT License
# Hollow Knight Completionist Checklist

A completion tracking website for Hollow Knight. Visit [bladepoint6969.github.io/hollow-knight-checklist](https://bladepoint6969.github.io/hollow-knight-checklist).

## Development

### Prerequisites

- Node.js (v14 or higher)
- npm

### Setup

```bash
npm install
```

### Build Commands

```bash
# Development with live reload
npm run dev

# Production build
npm run build
```

### Project Structure

- `twig/` - HTML templates
- `scss/` - Sass stylesheets
- `js/` - JavaScript files
- `gameData.json` - Game completion data
- `gulpfile.js` - Build configuration

### Maintenance

- Game data is stored in `gameData.json`
- Templates use Twig templating engine
- Styles are compiled from Sass
- Build outputs to `dist/` directory (generated)

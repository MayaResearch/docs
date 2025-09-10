# Maya Research API Documentation

This repository contains the documentation for Maya Research APIs, built with [Mintlify](https://mintlify.com).

## 📚 Documentation Structure

- **VeenaMAX TTS API** - Advanced Text-to-Speech API for Indian languages
- **API Reference** - Interactive API playground and endpoints
- **Getting Started** - Quick start guides and tutorials

## 🚀 Local Development

### Prerequisites

- Node.js 18+ installed
- npm or yarn package manager

### Installation

1. Install Mintlify CLI globally:
```bash
npm install -g mintlify
```

2. Navigate to the docs directory:
```bash
cd /Users/sthipp005/Documents/personal/mayaresearch/docs
```

3. Start the development server:
```bash
mintlify dev
```

The documentation will be available at `http://localhost:3000`

## 📝 Making Changes

1. Edit `.mdx` files for content changes
2. Update `docs.json` for navigation and configuration
3. Modify `openapi.yaml` for API specification updates

## 🌐 Deployment

### Deploy to Mintlify hosting:
```bash
mintlify deploy
```

### Build for self-hosting:
```bash
mintlify build
```

## 📁 Project Structure

```
docs/
├── index.mdx                           # Home page
├── veenamax-tts-api.mdx               # VeenaMAX overview
├── api-reference/
│   ├── endpoint/
│   │   └── veenamax-generate.mdx      # API endpoint documentation
│   └── openapi.yaml                   # OpenAPI specification
├── docs.json                          # Mintlify configuration
└── README.md                          # This file
```

## 🔗 Important Links

- **Website**: https://mayaresearch.ai
- **API**: https://api.mayaresearch.ai
- **Support**: https://mayaresearch.ai
- **Documentation**: https://mayaresearch.ai

## 🎨 Customization

- **Colors**: Purple theme (#7C3AED primary)
- **Logo**: Place your logo files in `/logo/` directory
- **Favicon**: Update `/favicon.svg`

## 📊 Analytics

Update the GTM tag ID in `docs.json`:
```json
"analytics": {
  "gtm": {
    "tagId": "GTM-YOUR-ID"
  }
}
```

## 🤝 Support

For any questions or issues, contact: support@mayaresearch.ai

---

Built with ❤️ by Maya Research
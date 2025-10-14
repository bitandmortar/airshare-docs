# AirShare User Documentation

Welcome to the AirShare documentation! This comprehensive guide covers everything you need to know about using AirShare.

## 📚 Documentation Overview

### Getting Started
- **[Introduction](/content/1.getting-started/1.introduction.md)** - What is AirShare and why use it?
- **[Installation](/content/1.getting-started/2.installation.md)** - Install on Windows, macOS, or Linux
- **[Quick Start](/content/1.getting-started/3.quick-start.md)** - Send your first file in 2 minutes
- **[First-Time Setup](/content/1.getting-started/4.first-time-setup.md)** - Configure AirShare for best experience

### User Guide
- **[Sending Files](/content/2.guide/1.sending-files.md)** - Learn all the ways to send files
- **[Receiving Files](/content/2.guide/2.receiving-files.md)** - Receive and manage incoming files
- **[Using the Radar](/content/2.guide/3.using-radar.md)** - Discover and manage nearby devices
- **[Transfer History](/content/2.guide/4.transfer-history.md)** - Track and search all your transfers
- **[Settings Reference](/content/2.guide/5.settings.md)** - Complete settings documentation

### Troubleshooting
- **[Common Issues](/content/3.troubleshooting/1.common-issues.md)** - Solutions to frequent problems
- **[FAQ](/content/3.troubleshooting/2.faq.md)** - Frequently asked questions

### Advanced Topics
- **[Privacy & Security](/content/4.advanced/1.privacy-security.md)** - How AirShare protects your data
- **[Licensing Guide](/content/4.advanced/2.licensing.md)** - Free tier, Pro features, activation
- **[Updates & Versioning](/content/4.advanced/3.updates.md)** - How updates work
- **[Performance Optimization](/content/4.advanced/4.performance.md)** - Get maximum transfer speeds
- **[Network Setup](/content/4.advanced/5.network-setup.md)** - Firewall, router, enterprise networks

## 🚀 Quick Links

- **[Download AirShare](https://github.com/airsharehq/airshare/releases/latest)**
- **[GitHub Repository](https://github.com/airsharehq/airshare)**
- **[Report Issues](https://github.com/airsharehq/airshare/issues)**
- **[Discussions](https://github.com/airsharehq/airshare/discussions)**

## 🌐 Viewing the Documentation

### Local Development

To run the documentation site locally:

```bash
# Navigate to docs folder
cd docs

# Install dependencies
npm install

# Start development server
npm run dev
```

The documentation will be available at `http://localhost:3000`

### Building for Production

```bash
# Build the documentation
npm run build

# The built site will be in .output/
```

## 📝 Documentation Structure

```
docs/
├── content/                    # Markdown documentation files
│   ├── index.md               # Homepage
│   ├── 1.getting-started/     # Getting started guides
│   ├── 2.guide/               # User guides
│   ├── 3.troubleshooting/     # Help and troubleshooting
│   └── 4.advanced/            # Advanced topics
├── public/                     # Static assets
├── package.json               # Dependencies
└── README.md                  # This file
```

## 🛠️ Technology Stack

This documentation is built with:

- [Nuxt 4](https://nuxt.com) - The web framework
- [Nuxt Content](https://content.nuxt.com/) - File-based CMS
- [Nuxt UI](https://ui.nuxt.com) - UI components
- [Docus](https://docus.dev) - Documentation theme
- [Tailwind CSS 4](https://tailwindcss.com/) - Styling

## 📄 License

Documentation content is licensed under [MIT License](https://opensource.org/licenses/MIT).

AirShare application itself is proprietary software - see main [LICENSE](../LICENSE) file for details.

## 💬 Contributing

Found a typo or want to improve the documentation?

1. Fork the repository
2. Make your changes in the `docs/content/` folder
3. Submit a pull request

For major changes, please open an issue first to discuss what you would like to change.

## 📞 Support

- **Email**: support@airshare.com (Pro users)
- **GitHub Issues**: [Bug reports](https://github.com/airsharehq/airshare/issues)
- **GitHub Discussions**: [Questions & discussions](https://github.com/airsharehq/airshare/discussions)

---

**Happy sharing with AirShare!** ✈️

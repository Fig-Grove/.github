# 🌳 Fig Grove

**Production-ready tools for Figma plugin development**

Fig Grove is a suite of open-source tools that transforms Figma plugin development from a painful, manual process into a delightful, automated experience.

## 🎯 Mission

We're building the foundational infrastructure that the Figma plugin ecosystem desperately needs - reliable testing, efficient storage, and seamless automation.

## 📦 Ecosystem

### Core Tools

#### 🧪 [QuickFig](https://github.com/Fig-Grove/quickfig)
Production-ready testing framework with real QuickJS constraint validation
- Test against actual Figma runtime constraints (8MB memory, 16ms UI blocking)
- No more "works locally, crashes in Figma" surprises
- 95.8% test migration success rate

#### 🏺 [FigJar](https://github.com/Fig-Grove/figjar)
Intelligent storage solution with automatic compression and chunking
- Drop-in replacement for Figma's limited storage APIs
- Handles 100KB per-call and 5MB total limits automatically
- Smart strategies: direct → chunked → compressed

#### 🌾 [Fig Harvest](https://github.com/Fig-Grove/fig-harvest) *(Coming Soon)*
Complete automation suite for Figma plugin development
- Watch mode with auto-reload in Figma
- Integrated testing on every change
- Build optimization and bundling

### Storage Extensions (coming soon)

- 📁 `@fig-grove/figjar-shared` - SharedPluginData support
- ☁️ `@fig-grove/figjar-s3` - AWS S3 storage
- 🐙 `@fig-grove/figjar-github` - GitHub as storage
- 📝 `@fig-grove/figjar-gist` - Free Gist storage
- *More coming soon...*

## 🚀 Quick Start

```bash
# Install testing framework
npm install -D @fig-grove/quickfig

# Add storage solution
npm install @fig-grove/figjar

# Coming soon: automation
npm install -g @fig-grove/fig-harvest
```

## 💡 Why Fig Grove?

**Before Fig Grove:**
- Manual testing with console.log debugging
- Mystery crashes from constraint violations
- Tedious reload cycles
- No automation possibilities
- Storage limits breaking plugins

**After Fig Grove:**
```bash
# One command to rule them all
fig-harvest watch ./my-plugin

✅ Automatic rebuild on save
✅ Instant Figma reload
✅ Constraint validation
✅ Performance profiling
✅ Storage optimization
✅ Ready for production
```

## 🤝 Contributing

We welcome contributions! Each tool has its own repository with specific contribution guidelines. 

- Found a bug? Open an issue
- Have an idea? Start a discussion
- Want to contribute? Check out our good first issues

## 📚 Documentation

Visit each tool's repository for detailed documentation:
- [QuickFig Docs](https://github.com/Fig-Grove/quickfig#readme)
- [FigJar Docs](https://github.com/Fig-Grove/figjar#readme)
- [Fig Harvest Docs](https://github.com/Fig-Grove/fig-harvest#readme)

## 🌱 Philosophy

Fig Grove tools are:
- **Open Source** - Free forever, community-driven
- **Production-Ready** - Battle-tested in real plugins
- **Developer-First** - Built by developers, for developers
- **Modular** - Use what you need, when you need it

## 📈 Roadmap

- [x] QuickFig - Testing framework
- [x] FigJar - Storage solution
- [ ] Fig Harvest - Automation suite
- [ ] Storage adapters ecosystem
- [ ] CI/CD integration
- [ ] Plugin templates
- [ ] Performance profiling dashboard

## 📄 License

All Fig Grove tools are released under the MIT License.

---

Built with ❤️ for the Figma plugin community

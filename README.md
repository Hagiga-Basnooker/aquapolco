# 📦 Aquapolco Queue Management System

A real-time queue management application for Aquapolco warehouse operations with cloud synchronization across devices.

## 🚀 Latest Version: v1.0.1

**Release Date:** March 17, 2026

### Features
- ☁️ **Cloud Persistence**: Real-time sync across Mac, iPhone, and web browsers using JSONBin
- 📍 **GPS Verification**: 1000m radius check with manager override option
- 👥 **Role-Based Access**: Admin (manager) and Staff (warehouse crew) modes
- 📊 **Order Management**: Real-time tracking with 3 status levels (ממתין/בהכנה/מוכן)
- 🗑️ **Recycle Bin**: Soft-delete with restore functionality
- 📋 **Audit Logging**: Complete history of all changes with timestamps
- 🇮🇱 **Hebrew RTL Support**: Full Hebrew language interface

## 📚 Version History

See [CHANGELOG.md](CHANGELOG.md) for detailed version history.

### Version Map
- **v1.0.1** (Current) - Enhanced with logo and legal notices
- **v1.0.0** (Stable) - Initial release with cloud sync

## 🔍 Git Versioning Guide

### Understanding Git Tags
Git tags are **labels** pointing to specific commits in your repository. They're not separate files or folders—they're stored in Git's metadata.

```bash
# View all versions
git tag -l

# Checkout a specific version
git checkout v1.0.0
git checkout v1.0.1

# View tag info
git show v1.0.1
```

### When to Create a New Version
1. After implementing a feature
2. When fixing important bugs
3. Before deploying to production

### How to Create a New Version
```bash
# Make your changes and commit
git add .
git commit -m "Your changes"

# Create a new tag
git tag -a v1.0.2 -m "Version 1.0.2 - Description of changes"

# Push to GitHub
git push origin main
git push origin --tags
```

## 📋 Release Notes (GitHub Releases)

View detailed release notes on GitHub:
- Go to: https://github.com/Aquapolco/aquapolco/releases
- Each release shows what changed and allows easy downloads

## 🛠️ Development Setup

```bash
# Clone the repository
git clone https://github.com/Aquapolco/aquapolco.git
cd aquapolco

# No build required - it's a single HTML file!
# Just open index.html in your browser
```

## 📱 Access Points

- **Live App**: https://aquapolco.github.io/aquapolco/
- **Repository**: https://github.com/Aquapolco/aquapolco
- **Releases**: https://github.com/Aquapolco/aquapolco/releases
- **Main File**: `index.html`

## 🔐 Security Notes

- JSONBin credentials stored in code (development only)
- Consider moving to environment variables for production
- Passwords stored in browser localStorage

## 📄 License & Support

Created as a custom queue management solution for Aquapolco Ltd.

---

**Last Updated:** 2026-03-17 | **Status:** v1.0.1 Active

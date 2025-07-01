# Bitmap BRC-420 Community App Store

A community app store for Umbrel containing the Bitmap BRC-420 Indexer - a comprehensive Bitcoin inscription indexer for BRC-420 tokens, bitmaps, and parcels.

## 🚀 About

This community app store provides access to the Bitmap BRC-420 Indexer, which enables you to:

- Index and track BRC-420 inscriptions on your Umbrel node
- Browse Bitcoin bitmap inscriptions with full parcel support  
- Real-time blockchain monitoring with robust validation
- Beautiful web interface for exploring inscriptions
- Complete REST API for programmatic access
- Privacy-first local operation using only your Umbrel services

## 📦 Apps in this Store

### Bitmap BRC-420 Indexer
- **Description**: Comprehensive Bitcoin inscription indexer
- **Features**: BRC-420 tokens, bitmaps, parcels, real-time indexing
- **Dependencies**: Bitcoin Core, Ordinals, Mempool (optional)
- **Port**: 8080
- **Source**: [GitHub Repository](https://github.com/switch-900/Bitmap-BRC420-Indexer)

## 🔧 Installation

### Method 1: Add Community App Store to Umbrel

1. Go to your Umbrel app store
2. Click "Community App Stores" 
3. Add this repository: `https://github.com/switch-900/bitmap-brc420-community-app-store`
4. Browse and install the Bitmap BRC-420 Indexer

### Method 2: Direct Installation

You can also install apps directly by copying the app manifests to your Umbrel's community app store directory.

## 🏗 App Structure

```
apps/
  bitmap-brc420-indexer/
    umbrel-app.yml      # App manifest
    docker-compose.yml  # Docker services
    README.md          # App documentation
```

## 🔒 Privacy & Security

- **Local Operation**: All apps run entirely on your Umbrel node
- **No External Dependencies**: Uses only internal Umbrel services
- **Data Sovereignty**: Your data never leaves your device
- **Open Source**: All code is publicly available and auditable

## 🛠 Development

This community app store follows Umbrel's community app store standards:

- Apps are packaged as Docker containers
- Configurations use Umbrel's internal service discovery
- All apps integrate seamlessly with existing Umbrel services
- Comprehensive documentation and support resources

## 📈 Performance

Apps in this store are optimized for:
- Home server environments (Raspberry Pi, low-power devices)
- Local network operation with minimal bandwidth usage
- Efficient resource utilization
- Reliable operation with automatic recovery

## 🤝 Support

For support with apps in this store:

- **App Issues**: [Main App Repository Issues](https://github.com/switch-900/Bitmap-BRC420-Indexer/issues)
- **Store Issues**: [App Store Repository Issues](https://github.com/switch-900/bitmap-brc420-community-app-store/issues)
- **Umbrel Support**: [Umbrel Community](https://community.getumbrel.com/)

## 🔄 Updates

Apps in this store are automatically updated when:
- New versions are pushed to the main application repository
- Docker images are rebuilt and published
- App manifests are updated in this store

## 🎯 Roadmap

Future additions to this community app store may include:
- Additional Bitcoin inscription tools
- Enhanced parcel management features
- Integration with other Bitcoin services
- Performance monitoring and analytics tools

## 📜 License

This community app store and all included apps are open source. See individual app repositories for specific license details.

---

**⚡ Bitcoin Native** - Built specifically for Bitcoin inscriptions with deep protocol understanding.

**🔒 Privacy First** - All processing happens locally on your Umbrel node.

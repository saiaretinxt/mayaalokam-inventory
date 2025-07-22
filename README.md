# Modified ox_inventory

A beautifully redesigned and enhanced version of the popular ox_inventory system for FiveM servers. This project features a modern UI overhaul with improved visual effects, better user experience, and enhanced functionality.

## ✨ Features

### 🎨 Visual Enhancements
- **Modern UI Design**: Completely redesigned interface with contemporary styling
- **Beautiful Context Menus**: Enhanced right-click menus with gradient backgrounds and smooth animations
- **Improved Animations**: Smooth transitions, hover effects, and interactive elements
- **Better Typography**: Enhanced fonts and text rendering for better readability
- **Glassmorphism Effects**: Modern blur effects and translucent backgrounds
- **Enhanced Color Scheme**: Carefully chosen color palette for better visual hierarchy

### 🚀 Performance Improvements
- **Optimized Rendering**: Better performance with React optimizations
- **Smooth Interactions**: Buttery smooth drag and drop operations
- **Reduced Resource Usage**: Optimized code for better server performance

### 🎯 User Experience
- **Intuitive Controls**: Enhanced keyboard shortcuts and mouse interactions
- **Better Tooltips**: Improved item information display
- **Responsive Design**: Works seamlessly across different screen resolutions
- **Enhanced Hotbar**: Beautiful hotbar with improved visibility

## 📦 Installation

### Prerequisites
- FiveM server with ox_inventory already installed
- Basic knowledge of FiveM resource management

### Step-by-Step Installation

1. **Download the Project**
   ```bash
   git clone https://github.com/saiaretinxt/ox-inventory-modified.git
   cd ox-inventory-modified
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Build the Project**
   ```bash
   npm run build
   ```

4. **Replace ox_inventory Build Folder**
   
   ⚠️ **Important**: Make sure to backup your original ox_inventory before proceeding!
   
   - Navigate to your FiveM server's `resources` folder
   - Find the `ox_inventory` resource folder
   - **Backup** the original `web/build` folder (rename it to `web/build_backup`)
   - Copy the newly generated `build` folder from this project
   - Replace the `web/build` folder in your ox_inventory resource

5. **Restart Your Server**
   ```bash
   restart ox_inventory
   ```

## 🛠️ Development

### Building for Development
```bash
npm run start
```

### Building for Production
```bash
npm run build
```

### Watch Mode (for active development)
```bash
npm run watch
```

## 📁 Project Structure

```
ox-inventory-modified/
├── src/
│   ├── components/
│   │   ├── inventory/
│   │   └── utils/
│   ├── store/
│   ├── hooks/
│   ├── helpers/
│   └── styles/
├── public/
├── build/          # Generated build files (replace ox_inventory's build folder with this)
├── package.json
└── README.md
```

## 🎨 Customization

### Modifying Colors
Edit the SCSS variables in `src/index.scss`:

```scss
$mainColor: #1a1b23;
$textColor: #e2e3e7;
$accentColor: #4a90e2;
$accentColorHover: #5ba0f2;
```

### Adjusting Grid Size
Modify grid configuration in `src/index.scss`:

```scss
$gridSize: 14vh;
$gridGap: 4px;
```

## 🔧 Configuration

The inventory system uses the same configuration as the original ox_inventory. No additional server-side configuration is needed.

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🐛 Bug Reports

If you encounter any issues, please report them on the [Issues](https://github.com/saiaretinxt/ox-inventory-modified/issues) page with:
- Detailed description of the problem
- Steps to reproduce
- Screenshots (if applicable)
- Server information

## 📜 Changelog

### Version 1.0.0
- Initial release with complete UI overhaul
- Enhanced context menus with modern styling
- Improved animations and transitions
- Better responsive design
- Performance optimizations

## ⚖️ License

This project is based on ox_inventory and maintains compatibility with its original license. Please respect the original ox_inventory license terms.

## 🙏 Credits

- **Original ox_inventory**: [Overextended](https://github.com/overextended/ox_inventory)
- **UI/UX Design**: Enhanced by Sai Areti
- **Icons**: [Yaroph's Icon Pack](https://forum.cfx.re/t/inventory-icons-pack-for-rp-server-hq-draw-24k-cloth-l-1400-objects/5203350)

## 📞 Support

- **Discord**: Join our community server for support
- **GitHub Issues**: Report bugs and request features
- **Documentation**: Check the original ox_inventory documentation for base functionality

## 🎮 Compatibility

- **FiveM**: Latest version
- **ox_inventory**: v2.0.0+
- **Browsers**: Chrome 90+, Firefox 88+, Safari 14+

## 🔒 Security

If you discover any security-related issues, please email saiareti@nxtkraft.com instead of using the issue tracker.

---

### 📝 Quick Installation Summary

1. Clone this repository
2. Run `npm install && npm run build`
3. **Backup your original ox_inventory/web/build folder**
4. Replace it with the new build folder from this project
5. Restart your server
6. Enjoy the enhanced inventory experience!

---

**Made with ❤️ by the Sai Areti**
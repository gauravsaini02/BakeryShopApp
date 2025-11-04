# 🍰 Flutter Sweet Shop App

[![Flutter Version](https://img.shields.io/badge/Flutter-%5E3.7.2-blue.svg)](https://flutter.dev)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20iOS-lightgrey.svg)]()

A complete, production-ready **Sweet Shop E-commerce App** built with Flutter, featuring a modern UI/UX design with state management, responsive layouts, and comprehensive shopping functionality. This app serves as an excellent reference for building e-commerce applications with Flutter.

## 📱 App Screenshots

| Home Screen | Product Details | Shopping Cart | Categories |
|-------------|----------------|---------------|------------|
| ![Home](https://raw.githubusercontent.com/ales-dev-studio/Flutter-Sweet-Shop-App-UI/refs/heads/main/assets/demos/demo-1.png) | ![Details](https://raw.githubusercontent.com/ales-dev-studio/Flutter-Sweet-Shop-App-UI/refs/heads/main/assets/demos/demo-2.png) | ![Cart](https://raw.githubusercontent.com/ales-dev-studio/Flutter-Sweet-Shop-App-UI/refs/heads/main/assets/demos/demo-3.png) | ![Categories](https://raw.githubusercontent.com/ales-dev-studio/Flutter-Sweet-Shop-App-UI/refs/heads/main/assets/demos/demo-4.png) |

## ✨ Features

### 🛍️ **Core Shopping Experience**
- **Product Catalog**: Browse cakes, cupcakes, donuts, pastries, and birthday cakes
- **Product Details**: Detailed product information with weight selection (0.5kg - 4kg)
- **Shopping Cart**: Full cart management with real-time calculations
- **Checkout Flow**: Multi-step checkout with payment methods
- **User Profile**: Account management and preferences

### 🎨 **UI/UX Excellence**
- **Custom Theme System**: Comprehensive theming with bakery-inspired color palette
- **Responsive Design**: Adaptive layouts for all screen sizes
- **Smooth Animations**: Engaging micro-interactions and transitions
- **Modern Navigation**: Curved bottom navigation with SVG icons
- **Search Functionality**: Quick product discovery

### 🚀 **Advanced Features**
- **Banner Carousel**: Auto-scrolling promotional banners
- **Category Browsing**: Organized product categories
- **Rating System**: Customer reviews and ratings
- **Store Locator**: Interactive map integration for store locations
- **Wishlist Support**: Save favorite products

## 🏗️ Architecture & Tech Stack

### **Core Technologies**
- **Flutter SDK**: ^3.7.2
- **State Management**: BLoC/Cubit pattern for reactive state management
- **Architecture**: Clean, feature-based modular structure

### **Key Dependencies**
```yaml
dependencies:
  flutter_bloc: ^9.1.1        # State management
  google_fonts: ^6.2.1        # Typography (Montserrat)
  carousel_slider: ^5.0.0     # Image carousel
  flutter_svg: ^2.2.0         # SVG icon support
  flutter_map: ^8.1.1         # Interactive maps
  animate_do: ^4.2.0          # Animations
  smooth_page_indicator: ^1.2.1  # Page indicators
  readmore: ^3.0.0            # Expandable text
  dotted_border: ^3.1.0       # Decorative borders
  flutter_gen: ^5.10.0        # Asset generation
```

### **Project Structure**
```
lib/
├── core/                      # Core application utilities
│   ├── theme/                # Colors, typography, dimensions
│   ├── utils/                # Helper functions and utilities
│   ├── widgets/              # Reusable UI components
│   └── gen/                  # Generated assets
├── features/                 # Feature modules
│   ├── home_feature/        # Main screens and navigation
│   ├── cart_feature/        # Shopping cart functionality
│   └── map_feature/         # Store location mapping
└── main.dart                # Application entry point
```

## 🚀 Getting Started

### **Prerequisites**
- Flutter SDK ^3.7.2 or higher
- Dart SDK compatible with Flutter version
- Android Studio / VS Code with Flutter extensions
- Android SDK / Xcode for device testing

### **Installation**

1. **Clone the repository**
   ```bash
   git clone https://github.com/ales-dev-studio/Flutter-Sweet-Shop-App-UI.git
   cd Flutter-Sweet-Shop-App-UI
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Generate assets** (if needed)
   ```bash
   flutter packages pub run build_runner build
   ```

4. **Run the application**
   ```bash
   flutter run
   ```

### **Build for Production**

```bash
# Android
flutter build apk --release
flutter build appbundle --release

# iOS
flutter build ios --release

# Web (if supported)
flutter build web --release
```

## 🎯 Key Features Deep Dive

### **Custom Theme System**
- **Primary Colors**: Coral-red (#FB5650) with warm brown accents
- **Typography**: Google Fonts integration with Montserrat family
- **Consistent Spacing**: Dimension system for uniform layouts
- **Light/Dark Theme**: Framework prepared for theme switching

### **State Management with Cubit**
- Reactive state updates across the app
- Clean separation of business logic
- Predictable state changes
- Easy testing and debugging

### **Responsive Design**
- Device-specific utilities
- Adaptive layouts for tablets and phones
- Orientation support
- Consistent experience across devices

### **Interactive Components**
- **Product Cards**: Tap-to-view details with smooth transitions
- **Cart Operations**: Add/remove items with quantity controls
- **Search Bar**: Real-time product filtering
- **Bottom Navigation**: Modern curved design with active states

## 📚 Learning Resources

### **Video Tutorials**
- [Complete YouTube Playlist](https://youtube.com/playlist?list=PLFecs-ae_8FG8O_y6zSL9muONH-iC5kYH&si=pwhuw0HfssxorQ9A) - Step-by-step development guide

### **Design Resources**
- [Figma Design File](https://www.figma.com/design/kgbuMUCvaYoMXLRjDxkZ6s/Sweet-Craze?node-id=1-2&t=ynInnRvFPLgl3VuP-1) - Original UI/UX designs

### **Documentation**
- [Flutter Official Documentation](https://flutter.dev/docs)
- [BLoC State Management](https://bloclibrary.dev/)
- [Material Design Guidelines](https://material.io/design/)

## 🛠️ Development

### **Code Style**
This project follows Flutter/Dart conventions:
- `flutter_lints` for code quality
- Feature-based organization
- Clean architecture principles
- Comprehensive widget documentation

### **Asset Management**
- `flutter_gen` for type-safe asset references
- Organized asset structure in `assets/`
- SVG icons for scalable graphics
- High-quality product images

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add some amazing feature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open a Pull Request**

### **Contribution Guidelines**
- Follow the existing code style
- Add comments for complex logic
- Update documentation as needed
- Test your changes thoroughly

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Flutter Team** for the amazing framework
- **BLoC Library** for excellent state management
- **Google Fonts** for beautiful typography
- **Figma Community** for design inspiration

## 📞 Support

If you have any questions or need support:

- 📧 Create an [Issue](https://github.com/ales-dev-studio/Flutter-Sweet-Shop-App-UI/issues)
- 🐦 Follow for updates and tips
- 📺 Watch the [YouTube tutorial series](https://youtube.com/playlist?list=PLFecs-ae_8FG8O_y6zSL9muONH-iC5kYH&si=pwhuw0HfssxorQ9A)

---

⭐ **Star this repository** if it helped you learn Flutter or inspired your project!


# 🛒 ShopEase - A Basic Shopping App

**ShopEase** is a simple and elegant shopping app built using Flutter, designed to help users browse and explore different categories of products — from electronics and clothing to groceries — all in one place. It’s a minimal, beginner-friendly app perfect for learning how Flutter works with navigation, state management, and UI design.

---

## ✨ Features

- Categorized product listing (Electronics, Clothing, Groceries)
- Beautiful UI with cards and shadows for clean item representation
- Tap-to-view category items using Flutter's `Hero` animation
- Add-to-cart functionality with quantity tracking
- Cart screen to view selected items
- Smooth page navigation and responsive layout
- Fully offline and asset-based (no API required)

---

## 🚀 Getting Started

### 📦 Prerequisites

- Flutter SDK (v3.x or later)
- Dart SDK
- Android Studio or VS Code with Flutter plugin

### 🛠 Installation Steps

1. **Clone the repository:**

```bash
git clone https://github.com/Ayesha2608/shopease_app.git
cd shopease_app
```

2. **Install dependencies:**

```bash
flutter pub get
```

3. **Run the app:**

```bash
flutter run
```

---

## 🧩 Assets

Ensure you have the following local images placed inside the `assets/images/` directory:

```
assets/images/
├── electronics.png
├── laptop.png
├── smartphone.png
├── headphones.png
├── camera.png
├── clothing.png
├── tshirt.png
├── jacket.png
├── dress.png
├── shoes.png
├── groceries.png
├── apple.png
├── milk.png
├── bread.png
├── eggs.png
```

Then declare them in your `pubspec.yaml` like this:

```yaml
flutter:
  assets:
    - assets/images/electronics.png
    - assets/images/laptop.png
    - assets/images/smartphone.png
    - assets/images/headphones.png
    - assets/images/camera.png
    - assets/images/clothing.png
    - assets/images/tshirt.png
    - assets/images/jacket.png
    - assets/images/dress.png
    - assets/images/shoes.png
    - assets/images/groceries.png
    - assets/images/apple.png
    - assets/images/milk.png
    - assets/images/bread.png
    - assets/images/eggs.png
```

---

## 🧠 Learning Goals

This project is ideal for Flutter beginners and intermediate learners who want to:

- Understand Flutter navigation and routing
- Learn how to pass data between screens
- Implement state management using basic `setState()`
- Use `ListView.builder` for dynamic UI rendering
- Organize assets and use them in UI elements
- Build an interactive cart system without external packages
- Practice `Hero` animations to enhance UX transitions

---

## 💡 Usage

- Launch the app and explore categories
- Tap any category to see its items
- Tap item image for detailed view (uses Hero animation)
- Tap "Add to Cart" to add items — quantity updates automatically
- Click the 🛒 cart icon to view selected items

---

## 📜 License

This project is open for learning and personal use. No official license is attached yet. You may add [MIT License](https://choosealicense.com/licenses/mit/) or any preferred one later.

---

## 👩‍💻 Author

**Ayesha Iftikhar**  
GitHub: [@Ayesha2608](https://github.com/Ayesha2608)

If you find this project helpful or have suggestions, feel free to open an issue or submit a pull request. Happy coding! 💙

---

# 🏠 List Mates - Fun Mates Shared List App

A delightful Flutter app that transforms any shared list into a joyful, collaborative experience! Perfect for housemates, families, and couples who want to manage shared items or tasks in a playful and efficient way.

## ✨ Features

### 🏠 Mate Group Management
- Add group members
- Seamlessly switch between mate profiles
- All members have equal access and collaboration rights

### 🛒 List Management
- Add any items with quantities, units, and optional notes
- Mark items as completed
- Delete items you no longer need
- See who added each item for better tracking

### 🎨 Fun Visual Interface
- Items are displayed as colorful, rotating sticky notes
- Dynamic layout that expands as more items are added
- Subtle animations and hover effects enhance interactivity
- Random positioning for a realistic "pinned notes" feel

### 🎉 Engaging User Experience
- Smooth transitions and playful interactions
- Sticky notes animate on hover for visual feedback
- User-based colors for sticky notes
- Interface organically "grows" as lists expand

### 🔄 Real-Time Sync (Firebase)
- Sync items between multiple devices in real-time
- Works offline with local storage fallback
- Secure cloud storage for your mate group data


## 🎯 How to Use

### Adding Mate Group Members
1. On first launch, choose to create or join a mate group
2. **Create Mate Group**: Add mate group name and your prefered display name
3. **Join Mate Group**: Enter the sent code and mate group to join
4. All mate group members can add, edit, and complete items

### Adding Items
1. Tap the "➕" (Add Item) button
2. Enter the item name (required)
3. Use the slider or ± buttons to adjust quantity (1–20)
4. Add a unit (e.g., kg, pcs, box)
5. Include optional notes
6. Tap "Add Item" to add to your shared list

### Managing Items
- **Complete an item**: Tap the green checkmark on any sticky note
- **Delete an item**: Tap the red delete button on any sticky note
- **Switch mate profile**: Use the drawer and choose "Switch Mate"

### Fun Features
- Sticky notes animate and rotate as you hover
- Colors are automatically assigned to differentiate users
- Interface gets more vibrant as more items are added!

## 🛠️ Technical Details

- **State Management**: Provider pattern
- **Local Storage**: Hive & SharedPreferences for data persistence
- **Cloud Sync**: Firebase Firestore for real-time synchronization
- **Animations**: Flutter's built-in animation system
- **UI**: Material Design 3 with custom mate group theme

## 📱 Supported Platforms

- Android
- iOS
- Web
- Linux

## 🎨 Design Philosophy

This app is designed to be:
- **Fun**: Engaging animations and playful interactions
- **Simple**: Easy to use for the whole mate group
- **Visual**: Items are represented as colorful sticky notes
- **Collaborative**: Multiple mate group members can contribute
- **Versatile**: Can be used for groceries, tasks, reminders, or any shared items

## 🔮 Future Enhancements

- Push notifications when items are added/completed
- Item categories (e.g., Groceries, To-Do, Events)
- Activity stats and history tracking
- Custom themes
- Different list types (shopping, chores, events, etc.)
- User authentication and security
- Data export and backup features

---

**Made with ❤️ for housemates, couples, and families who love to stay organized—together.**

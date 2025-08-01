# ThunderStorm Apps Repository

This is an AltStore/SideStore compatible repository for ThunderStorm apps.

## How to Add This Repository to SideStore

1. Open SideStore on your device
2. Go to the **Sources** tab
3. Tap the **+** button
4. Enter this URL: `https://raw.githubusercontent.com/ThunderStorm333/ThunderStormApps/main/apps.json`
5. Tap **Add Source**

## Available Apps

### TransitApp v1.0
- **Description**: A SwiftUI-based iOS application with SwiftData persistence for basic item management
- **Features**: 
  - Clean NavigationSplitView interface
  - iPad compatibility
  - CRUD functionality for items with timestamps
  - CloudKit integration for syncing across devices
- **Requirements**: iOS 17.0+
- **Size**: 36KB

## Repository Structure

```
ThunderStormApps/
├── apps.json          # AltStore manifest file
├── TransitApp.ipa     # App binary
├── icons/             # App icons (optional)
└── README.md          # This file
```

## For Developers

To add more apps to this repository:

1. Add your IPA file to the root directory
2. Update `apps.json` with your app details
3. Commit and push changes

The repository will automatically be available to users who have added the source URL to SideStore.
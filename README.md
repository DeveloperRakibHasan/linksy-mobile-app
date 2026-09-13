# Linksy Android — Release v1.0.0

**Version:** 1.0.0 (Version Code: 1)  
**Package:** `Linksy-release.apk`  
**Package Name:** `com.linksy` (or `com.phonelink`)  
**Target SDK:** Android 14 (API level 34)  
**Minimum SDK:** Android 8.0 Oreo (API level 26)  
**File Size:** ~29.1 MB  
**SHA-256 Checksum:** `a6ce8f233d85d5416438f53ae063fd5132e5db80e8344c3875e986a829427193`  

---

## 🌟 What's New in v1.0.0

- **QR Code Scanner**: Built-in Google ML Kit barcode camera scanner for one-tap pairing with Linksy Desktop.
- **Universal Clipboard Sync**: Background accessibility and clipboard listener for instant cross-device copy & paste.
- **Bi-directional File Transfer**: Send and receive files, images, and documents directly to and from your computer.
- **Live Battery & Device Status**: Automatically broadcasts battery percentage and device status to your paired desktop.
- **Notification Mirroring**: Forwards incoming phone notifications to your desktop in real-time.
- **Firebase Presence & Discovery**: Automatic device discovery and connection fallback.

---

## 📱 System Requirements

- **Android OS**: Android 8.0 (Oreo) or higher (Android 8.0 - 14+)
- **Hardware Permissions**: Camera (for QR code scanning), Notifications, and Accessibility (for background clipboard reading).
- **Network**: Connect to the same Wi-Fi network as your desktop computer.

---

## 📥 Installation Instructions

### Step 1: Transfer APK to Device
Transfer the `Linksy-release.apk` file to your Android phone via:
- USB Cable
- Google Drive / Cloud storage
- Local network file share

### Step 2: Install the APK
1. Tap the `Linksy-release.apk` file on your device.
2. If prompted by Android with *"Install unknown apps"*, allow your browser/file manager to install apps from this source.
3. Tap **Install** and wait for installation to complete.
4. Tap **Open** to launch Linksy.

### Step 3: Grant Required Permissions
For the best experience, Linksy will request:
- **Camera Permission**: To scan the desktop pairing QR code.
- **Notification Permission**: To display foreground service status and mirror notifications.
- **Accessibility Service** *(Optional/Recommended)*: Enables automatic clipboard synchronization when copying text in any app.

---

## 🔗 How to Connect

1. Open **Linksy** on your Android phone.
2. Tap **Scan QR Code**.
3. Point your camera at the QR code shown on Linksy Desktop.
4. Your phone is now paired and ready!

---

## 🛠️ Troubleshooting: Google Play Protect & Installation Issues

### "App blocked by Play Protect" or "App not installed"
> **Warning:** *Google Play Protect: "App blocked to protect your device"* or *"App not installed"*

#### Why does this happen?
1. **Sensitive Background Permissions**: Linksy requires background accessibility (`Accessibility Service`) and notification listener permissions to perform cross-device clipboard sync and notification mirroring.
2. **Sideloaded APK**: Because this APK is downloaded directly and signed outside of the Google Play Store, Android 13/14+ Play Protect flags these permissions by default.
3. **Signature Conflict**: If an earlier build or debug version is already installed on your device, Android will fail with "App not installed".

#### How to fix:
1. **Uninstall Any Previous Versions**:
   - If you have an older version of Linksy installed on your device, **uninstall it first** to prevent signature mismatch errors.
2. **Temporarily Disable Google Play Protect**:
   - Open the **Google Play Store** app.
   - Tap your **Profile Icon** in the top-right corner.
   - Tap **Play Protect**.
   - Tap the **Settings (gear ⚙️)** icon in the top-right corner.
   - Turn **OFF** both:
     - **Scan apps with Play Protect**
     - **Improve harmful app detection**
3. **Install Linksy**:
   - Open your device's Downloads folder or File Manager.
   - Tap `Linksy-release.apk` and proceed with installation.
   - If prompted with *"Blocked by Play Protect"*, tap **More details** and select **Install anyway**.
   *(After installation is complete, you can safely turn Play Protect back on.)*

---

<details>
<summary><b>🇧🇩 বাংলায় সমাধান দেখতে এখানে ক্লিক করুন (Bengali Instructions)</b></summary>

### Google Play Protect ও "App not installed" সমাধান

#### কারণ:
1. Linksy অ্যাপে অটোমেটিক ক্লিপবোর্ড এবং নোটিফিকেশন সিঙ্ক করার জন্য সেনসিটিভ ব্যাকগ্রাউন্ড সার্ভিস ব্যবহার করা হয়েছে (যেমন `Accessibility Service` এবং `Notification Listener`)।
2. অ্যাপটি প্লে-স্টোরের বাইরে থেকে (Sideload) সরাসরি ডাউনলোড করা। Android 13/14+ এ প্লে প্রোটেক্ট এই পারমিশন থাকা অপরিচিত APK-কে ডিফল্টভাবে ব্লক করে দেয়।
3. ফোনে যদি আগে থেকেই কোনো পুরনো বা ভিন্ন সিগনেচারের ভার্সন ইনস্টল করা থাকে, তাহলে "App not installed" দেখায়।

#### সমাধানের ধাপ:
1. **আগের ভার্সন আনইনস্টল করুন:**
   - ফোনে যদি Linksy এর কোনো আগের ভার্সন ইনস্টল করা থাকে, সেটি প্রথমে **Uninstall** করে নিন।

2. **Google Play Protect সাময়িকভাবে বন্ধ করুন:**
   - ফোনে **Google Play Store** ওপেন করুন।
   - উপরে ডানপাশের **প্রোফাইল আইকন**-এ ট্যাপ করুন।
   - মেনু থেকে **Play Protect** সিলেক্ট করুন।
   - উপরে ডানপাশের **Settings (গিয়ার ⚙️)** আইকনে ট্যাপ করুন।
   - **"Scan apps with Play Protect"** এবং **"Improve harmful app detection"** অপশন দুটি **OFF / Disable** করে দিন।

3. **APK ইনস্টল করুন:**
   - এবার আপনার ফাইলের Downloads ফোল্ডার থেকে `Linksy` APK-তে ট্যাপ করে ইনস্টল করুন।
   - যদি "Install anyway" বা "More details" অপশন আসে, তাতে ট্যাপ করে ইনস্টলেশন সম্পন্ন করুন।
   *(অ্যাপ ইনস্টল হয়ে যাওয়ার পর আপনি চাইলে আবার Play Protect অপশনটি ON করে দিতে পারেন।)*

</details>


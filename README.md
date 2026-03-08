BabySleep Coach App

BabySleep Coach is a simple Android application that wraps a web-based parenting platform built with Lovable into a native mobile experience. The app allows parents to access baby sleep guidance, developmental leap information, milestones, and helpful parenting tips directly from their Android device.

The mobile app loads the Lovable web application securely inside an Android WebView and provides a lightweight mobile interface suitable for publishing on the Google Play Store.

---

Features

- Baby sleep guidance and schedules
- Developmental leap tracking
- Milestones and parenting tips
- Mobile-friendly access to the web platform
- Lightweight Android application
- Ready for Google Play Store deployment

---

Technology Stack

This project uses the following technologies:

- Android (Kotlin)
- Android WebView
- Gradle build system
- GitHub for source control
- Lovable web application backend

---

Project Structure

app
└── src
    └── main
        ├── java/com/babysleepcoach/app
        │    └── MainActivity.kt
        ├── res
        └── AndroidManifest.xml

---

Setup Instructions

1. Clone the repository

git clone https://github.com/YOUR-USERNAME/babysleepcoach-app.git

2. Open the project in Android Studio

3. Replace the Lovable web URL inside "MainActivity.kt" with your own Lovable app URL.

Example:

webView.loadUrl("https://yourapp.lovable.app")

4. Build the Android App Bundle (.AAB)

Build → Generate Signed Bundle → Android App Bundle

---

Publishing to Google Play Store

1. Build the release ".aab" file
2. Create an application in the Google Play Console
3. Upload the ".aab" bundle
4. Add app screenshots, description, and privacy policy
5. Submit the app for review

Google typically reviews apps within 1–3 days.

---

Privacy Policy

This application does not collect personal user data directly.
All functionality is provided through the web application hosted on Lovable.

---

License

This project is provided for educational and development purposes.
All branding, content, and data inside the Lovable web application remain the property of the application owner.

---

Author

BabySleep Coach Development Team

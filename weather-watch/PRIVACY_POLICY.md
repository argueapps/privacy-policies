# Privacy Policy for WeatherWatch

**Effective Date:** August 16, 2026  
**Last Updated:** August 16, 2026  

Thank you for choosing **WeatherWatch - Live Weather & Forecast** ("WeatherWatch", "we", "our", or "the extension"). We are committed to protecting your privacy. This Privacy Policy explains how our Chrome extension handles user information in compliance with Google Chrome Web Store Developer Program Policies.

---

### 1. Overview & Single Purpose
WeatherWatch is designed with a strict **privacy-first architecture**. The extension serves a single, focused purpose: to deliver real-time weather forecasts, hourly and 7-day predictions, air quality indices, and multi-city weather tracking directly to your browser's popup and side panel.

---

### 2. Information We Collect and How We Use It

WeatherWatch does **not** collect, sell, monetize, or track your personal identifiable information (PII). Below is the breakdown of how data is handled:

#### A. Location Data (`geolocation` and IP lookup)
* **Purpose:** If you enable automatic location detection, WeatherWatch accesses your approximate geographic coordinates (latitude and longitude) or IP address to fetch relevant meteorological forecasts for your area.
* **Usage:** Coordinates are transmitted strictly in real-time to our weather data provider ([Open-Meteo](https://open-meteo.com/)) to query live weather metrics.
* **Storage:** We do **not** log, track, store, or transmit your location history to any developer-owned database or third-party advertising network.
* **Control:** You may revoke location permissions at any time through Chrome’s extension settings, or manually search and select cities instead of using automatic location detection.

#### B. User Preferences and Local Storage (`storage`)
* **Purpose:** WeatherWatch stores your custom preferences locally on your device via Chrome’s storage APIs (`chrome.storage.local` and `chrome.storage.sync`).
* **Data Stored:**
  * Selected temperature unit (°C or °F) and wind speed unit (km/h, mph, m/s).
  * Appearance preferences (Dark mode / Light mode).
  * Auto-refresh intervals.
  * Your list of saved custom cities.
  * Temporary forecast cache (to speed up loading and reduce network bandwidth).
* **Storage:** This data remains strictly within your browser profile and is never sent to external analytics or developer servers.

#### C. Google Profile Sync (`identity`)
* **Purpose:** If enabled, `chrome.identity` is utilized solely by Google Chrome to synchronize your extension settings and saved city list across your own logged-in Chrome browsers.
* **Access:** WeatherWatch does not access, collect, or store your Google account password, emails, or personal profile details.

---

### 3. Third-Party Service Providers

WeatherWatch communicates only with essential weather and geocoding API endpoints to display forecast data:

| Provider | Purpose | Data Transmitted | Privacy Policy |
| :--- | :--- | :--- | :--- |
| **Open-Meteo API** | Weather, hourly/7-day forecasts, AQI | Geographic coordinates (Lat/Lon) | [Open-Meteo Privacy](https://open-meteo.com/en/terms) |
| **Open-Meteo Geocoding** | Global city search & location resolution | Search query string (City name) | [Open-Meteo Privacy](https://open-meteo.com/en/terms) |
| **IPAPI / BigDataCloud** | Fallback IP location & reverse geocoding | IP address / Coordinates for city name | Privacy compliant |

These third-party providers do not receive any identifying user information such as names, emails, or persistent user identifiers from WeatherWatch.

---

### 4. Chrome Web Store User Data Policy Compliance

In accordance with the Google Chrome Web Store User Data Policy, WeatherWatch explicitly certifies:

* ✅ **No Data Selling:** We do not sell, rent, or trade your personal or location data to any third parties.
* ✅ **No Advertising / Monetization:** We do not use or transfer user data for personalized advertising, credit assessment, or lending purposes.
* ✅ **No Unrelated Uses:** We do not use or transfer user data for purposes unrelated to the extension’s single core functionality (weather forecasting).
* ✅ **No Covert Tracking:** We do not track your browsing history, web activity, search engine queries, or interactions with other websites.

---

### 5. Data Retention & Deletion

* All user preferences and cached forecast data reside locally within your browser storage.
* If you uninstall WeatherWatch, all associated data, settings, and cached forecasts are immediately and permanently removed by Google Chrome from your device.

---

### 6. Changes to This Privacy Policy

We may update this Privacy Policy periodically to reflect changes in our features or legal requirements. Any updates will be reflected with a revised "Last Updated" date at the top of this document.

---

### 7. Contact Us

If you have any questions, suggestions, or concerns regarding this Privacy Policy or WeatherWatch's data practices, please contact us at:

* **Support Email:** `support@weatherwatch-extension.com` *(Replace with your developer email)*
* **Repository / Issue Tracker:** [https://github.com/drarahimi/weather-watch](https://github.com/drarahimi/weather-watch)

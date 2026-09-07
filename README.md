# 📍 GpsTrack — Real-Time GPS Tracking via Telegram

<p align="center">
  <img src="screenshots/map_overview.jpg" alt="GpsTrack Map" width="300"/>
</p>

<p align="center">
  <b>Track your devices in real time, directly on your phone.</b><br/>
  No monthly subscriptions. No complicated setup. Just Telegram.
</p>

<p align="center">
  <a href="https://t.me/White_List_111_bot">
    <img src="https://img.shields.io/badge/Register%20with%20the%20Bot-@White__List__111__bot-2CA5E0?style=for-the-badge&logo=telegram" alt="Get the App"/>
  </a>
  &nbsp;
  <img src="https://img.shields.io/badge/Platform-Android-3DDC84?style=for-the-badge&logo=android" alt="Android"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Unlimited%20Devices-Free-brightgreen?style=for-the-badge" alt="Free"/>
</p>

---

## 🚀 What is GpsTrack?

GpsTrack is an Android app that lets you track one or more GPS devices in real time on an interactive map. It uses **Telegram** as the communication layer — meaning your tracker sends location updates through a Telegram bot, and the app picks them up instantly.

No custom servers. No recurring fees. No ADS. Track unlimited devices, completely free.

---

## ✨ Features

| Feature | Description |
|---|---|
| 📡 Live Tracking | See your device move on the map in real time |
| 🗺️ Interactive Map | Powered by OpenStreetMap — works worldwide |
| 📜 Location History | Scrub through the full day timeline, second by second |
| 🔋 Battery & Speed | See battery level and speed from compatible trackers |
| 📍 Unlimited Devices | Track as many devices as you want, simultaneously |
| 🔔 Geofence Alerts | Get notified when a device enters or exits a zone |
| 🔒 Map Lock | Lock the map to follow a device automatically |
| 🚀 Speed Units | Switch between km/h and mph |
| 🌙 Dark Theme | Clean, modern dark interface |

---

## 📸 Screenshots

<p align="center">
  <img src="screenshots/login.jpg" alt="Login Screen" width="220"/>
  &nbsp;&nbsp;
  <img src="screenshots/map_live.jpg" alt="Live Tracking" width="220"/>
  &nbsp;&nbsp;
  <img src="screenshots/history.jpg" alt="Location History" width="220"/>
</p>

<p align="center">
  <img src="screenshots/geofence.jpg" alt="Geofence Manager" width="220"/>
  &nbsp;&nbsp;
  <img src="screenshots/sidebar.jpg" alt="Device Sidebar" width="220"/>
  &nbsp;&nbsp;
  <img src="screenshots/battery_speed.jpg" alt="Battery and Speed" width="220"/>
</p>

---

## 🔧 How It Works

```
GPS Tracker → sends JSON location → Telegram Bot → GpsTrack App → Map
```

1. Your GPS tracker sends a location message to a Telegram bot in this format:
```json
{"lat": 36.80, "lon": 10.18, "battery": 85, "speed": 72}
```
2. GpsTrack receives it instantly through your Telegram account
3. The map updates in real time

The app also supports native **Telegram Live Location** messages — no tracker configuration needed if you just want to share your phone's location.

---

## 📱 Requirements

- Android 8.0 or higher
- A Telegram account
- A GPS tracker that sends location to a Telegram bot (or any device sharing a live location)

---

## 🎁 Get the App — 100% Free - No ADS

GpsTrack is completely free to download, with no limit on the number of devices you can track — forever.

### Step 1 — Register via the bot

Open Telegram and start a chat with **[@White_List_111_bot](https://t.me/White_List_111_bot)**, then send `/start`.

<p align="center">
  <img src="screenshots/bot_start.jpg" alt="Bot Start" width="300"/>
</p>

### Step 2 — Receive your APK

The bot sends you the APK file directly in Telegram.

<p align="center">
  <img src="screenshots/bot_confirmed.jpg" alt="APK Received" width="300"/>
</p>

### Step 3 — Install and enjoy

Install the APK, log in with the same Telegram account, and start tracking.

---

## 📲 Installation Guide

### Step 1 — Download the APK

Save the APK file sent by the bot to your Android device.

### Step 2 — Allow Unknown Sources

Since GpsTrack is distributed outside the Play Store, you need to allow installation from unknown sources:

1. Go to **Settings → Apps** (or Security on older devices)
2. Tap **Install unknown apps** or **Special app access**
3. Select your file manager or browser
4. Enable **Allow from this source**

> ℹ️ The exact steps may vary depending on your Android version and device manufacturer.

### Step 3 — Install

<p align="center">
  <img src="screenshots/install.jpg" alt="Installation" width="300"/>
</p>

1. Open the APK file from your file manager
2. Tap **Install**
3. Tap **Open** when done

---

## 🔑 First Launch

### Login with Telegram

<p align="center">
  <img src="screenshots/login.jpg" alt="Login" width="300"/>
</p>

1. Enter your phone number with country code 
2. Enter the verification code sent to your Telegram app
3. Enter your 2FA password if you have one enabled

> ℹ️ The app logs in using the **same Telegram account** you used to register with the bot. This is how your registration is verified.

---

## 🗺️ Using the App

### Adding a Device

<p align="center">
  <img src="screenshots/add_device.jpg" alt="Add Device" width="300"/>
</p>

1. Tap the **☰ menu** icon (top left) to open the sidebar
2. Tap **+** to add a new device
3. Tap the device name to rename it
4. Tap **Pick Chat** to assign your tracker's Telegram chat

### Live Tracking

<p align="center">
  <img src="screenshots/map_live.jpg" alt="Live Map" width="300"/>
</p>

Once assigned, the device marker appears on the map and updates in real time. A **green glow** means the device sent an update in the last 15 seconds.

### Map Lock

Tap the **crosshair button** (bottom right) to lock the map onto the selected device. The button turns **blue** when locked. The map follows the device automatically. To unlock, simply pan or zoom the map.

### Bottom Status Bar

<p align="center">
  <img src="screenshots/battery_speed.jpg" alt="Status Bar" width="300"/>
</p>

The bottom bar shows the selected device name, battery level, and speed. Tap the device name to switch between devices.

---

## 📜 Location History

<p align="center">
  <img src="screenshots/history.jpg" alt="History" width="300"/>
</p>

1. Tap **⋮** (top right) → **Location History**
2. A timeline appears at the bottom of the screen
3. Drag the seekbar to scrub through the day — second by second
4. Tap **Date** to view a different day
5. Use **−** and **+** to zoom the timeline in or out
6. Press **▶** to start automatic playback
7. Tap the speed indicator (**1×, 5×, 15×, 60×**) to change playback speed

When a location is found for the selected time, an **amber marker** appears on the map showing coordinates, battery, and speed at that moment.

---

## 📡 Geofence Zones

<p align="center">
  <img src="screenshots/geofence.jpg" alt="Geofences" width="300"/>
</p>

Geofences are virtual boundaries. The app notifies you when a device enters or exits a zone.

### Adding a Zone

1. Open the sidebar → expand a device → tap **Manage Zones**
2. Tap **+ Add Zone**
3. Choose **Circle** (radius in metres) or **Search a place** by name
4. Set enter/exit alerts
5. Tap **Add Zone**

### Managing Zones

Each zone has toggle chips:
- **▶ Enter** — alert when device enters
- **◀ Exit** — alert when device exits
- **🔔 Notify** — master toggle for all alerts
- **✕ Delete** — remove the zone

---

## ❓ Troubleshooting

**Location updates stop after a few minutes**
Go to Settings → Apps → GpsTrack → Battery → select **Unrestricted**. This is especially important on Samsung, Xiaomi, Huawei, and OnePlus devices.

**My chat doesn't appear in the list**
Open a conversation with your tracker bot in the official Telegram app at least once before using GpsTrack.

**Access screen appears after login**
Make sure you registered with [@White_List_111_bot](https://t.me/White_List_111_bot) by sending `/register` first.

**Map shows no tiles**
Check your internet connection. The map requires an active connection to load.

---

## 💛 Support the Project

If you find GpsTrack useful and want to support development, you can send a donation in USDT:

Binance Wallet
```
TUFC9s6Sf8npGnJh6jA9YVFjCD5m6X2Lwh
```
> ⚠️ Network: **TRON (TRC20)** only. Any amount is appreciated 🙏


---

## 📞 Support

For help or questions:

<p align="center">
  <a href="https://t.me/White_List_111_bot">
    <img src="https://img.shields.io/badge/Contact%20Support-@White__List__111__bot-2CA5E0?style=for-the-badge&logo=telegram" alt="Support"/>
  </a>
</p>

Support is available in **English**.

---

## ⚠️ Disclaimer

GpsTrack is intended for lawful use only — tracking your own vehicles, devices, or dependents with their knowledge and consent. The developer is not responsible for any misuse of the application.

---
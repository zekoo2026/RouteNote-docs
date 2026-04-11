# RouteNote User Guide

## Table of Contents

1. [Introduction](#1-introduction)
2. [Main Screen](#2-main-screen)
3. [Recording a Route](#3-recording-a-route)
4. [Adding Memos (Pins)](#4-adding-memos-pins)
5. [Route List](#5-route-list)
6. [Route Details](#6-route-details)
7. [Editing Memos](#7-editing-memos)
8. [Attaching Photos](#8-attaching-photos)
9. [Manual Route Creation](#9-manual-route-creation)
10. [Area Creation](#10-area-creation)
11. [Administrative Boundaries](#11-administrative-boundaries)
12. [Merging Routes](#12-merging-routes)
13. [Search and Filters](#13-search-and-filters)
14. [Color Filters](#14-color-filters)
15. [Arrival Notifications](#15-arrival-notifications)
16. [Exporting Data](#16-exporting-data)
17. [Importing Data](#17-importing-data)
18. [Statistics](#18-statistics)
19. [iCloud Sync & Sharing](#19-icloud-sync--sharing)
20. [Settings](#20-settings)
21. [RouteNote Plus Features](#21-routenote-plus-features)

---

## 1. Introduction
**RouteNote** is a GPS-based tracking and memo management app. It allows you to record your movement in real-time while pinning color-coded memos and photos to any location on the map. It is designed for various uses, such as managing sales territories, recording travel memories, or confirming delivery routes.

---

## 2. Main Screen
The app features a full-screen map powered by Apple Maps.

### Interface Components
**Top Area**
* **User Tracking Button**: Centers the map on your current location. Tapping cycles through: "No Tracking → Follow → Follow with Heading".
* **Compass**: Appears when the map is rotated; tap to reset the map to North-up.
* **2D Button**: Appears in 3D mode; tap to return to a flat 2D view.
* **Map Type**: Switch between Standard, Satellite, and Hybrid (Satellite/Hybrid are Plus features).
* **Info (i) Button**: Opens the Settings screen.

**Bottom Toolbar**
* **Route List**: Access your saved records and routes.
* **Start Recording**: Begins GPS tracking.
* **Stop**: Saves and ends the current tracking session.
* **Add Memo**: Drop a pin at your current or chosen location (available during recording).
* **Create Route**: Create routes manually or merge existing ones.

---

## 3. Recording a Route

### Starting a Record
1. Tap **"Start Recording"** on the toolbar.
2. Enter a title in the dialog and tap **"OK"**.
3. GPS tracking begins, and a blue line will draw your path on the map in real-time.

### During Recording
* Distance traveled is displayed in real-time (Meters or Miles).
* Memos can be added at any time.
* Tracking continues even if the app is in the background.

### Stopping and Saving
1. Tap **"Stop"**.
2. Confirm by tapping **"Save"** to store the route in Core Data.
3. **Temporary Save**: Long-press the "Stop" button to save data without ending the session.

---

## 4. Adding Memos (Pins)
Tap **"Add Memo"** during recording to access the following options:

### Memo Types
* **Text Memo**: Create a memo with text, photos, and a custom color at your current location.
* **Manual Position Memo**: Align a crosshair on the map to place a memo at a specific location (Requires "Specify Memo Position" to be enabled in Settings).

### Quick Color Pins
Quickly add a pin without entering text.
* **Standard (Free)**: Green, Yellow, Red, Blue, Orange, Purple.
* **Extended (Plus)**: Cyan, Brown, Magenta.
* *Note: Labels for each color can be customized in Settings (e.g., "Visited," "Priority").*

---

## 5. Route List
View your saved data categorized into three sections: **Tracks** (GPS logs), **Planned Routes** (Manual), and **Planned Areas** (Polygons).

* **Display Modes**: Switch between All, Bookmarks, History, or Filtered views.
* **Swipe Actions**:
    * **Left Swipe**: Delete or Duplicate a route.
    * **Right Swipe**: Add to or remove from Bookmarks.

---

## 6. Route Details
Tap the **(i)** icon next to a route to see detailed information:
* **Stats**: Start/Arrival times, Duration, Distance, and Addresses.
* **Map View**: View the route as a polyline or the area as a polygon.
* **Actions**: Edit titles, add comments, reorder memos, or export the specific route.

---

## 7. Editing Memos
Tap a pin on the map and select the **(i)** button on the callout.
* **Content**: Edit text, change pin color, and update addresses (Manual address editing requires Plus).
* **Arrival Notification**: Set an alert to trigger when you approach this location.
* **Share**: Open in external map apps or share text/photos to other apps.

---

## 8. Attaching Photos
* **Adding**: Take a photo using the **Camera** (with pinch-to-zoom in Plus) or select from your **Photo Library**.
* **Limit**: Up to **4 photos** per memo (2 or more photos require Plus).
* **Optimization**: Enable "Limit Photo Size" (640x480) in Settings to save storage.

---

## 9. Manual Route Creation
1. Go to **"Create Route"** → **"Create Route"** on the toolbar.
2. Choose **"Route"** mode and your transport type (Walk or Drive).
3. Align the crosshair and use **"Add Route"** (follows roads) or **"Add Straight"** (direct line).

---

## 10. Area Creation
1. In the creation screen, select **"Area"**.
2. Place 3 or more points.
3. Tap **"Complete Area"** to close the polygon and save it as an "Area Plan".

---

## 11. Administrative Boundaries
Automatically generate area boundaries using OpenStreetMap data.
1. Tap **"Region"** in the creation screen.
2. Select a level: **Region, Prefecture, County, Municipality, Ward, or Neighborhood**.
* *Note: Most levels beyond "Region" require RouteNote Plus.*

---

## 12. Merging Routes
Combine multiple routes into a single record (Plus feature).
1. Go to **"Create Route"** → **"Merge Routes"**.
2. Select two or more routes to merge.
3. Tap **"Merge"** to consolidate all track data and memos.

---

## 13. Search and Filters
* **Route Search**: Filter by Title, Comment, or Departure/Arrival addresses.
* **Pin Search (Plus)**: Search for routes containing specific text or addresses within memos.

---

## 14. Color Filters
On the map memo panel, you can toggle the visibility of memos by their pin color.
1. Tap the menu button on the memo panel.
2. Select **"Filter by Pin Color"**.

---

## 15. Arrival Notifications
Receive an alert when you approach a specific memo location.
1. Tap the **Bell icon** in the memo edit screen.
2. A 100m monitoring radius is set around the location.
* *Limit: Up to 20 locations can be monitored simultaneously.*

---

## 16. Exporting Data
Export data in four formats:

| Format | Extension | Content | Plus Required |
| :--- | :--- | :--- | :---: |
| **RNOTE** | `.rnote` | Compressed (JSON + Photos) | Yes |
| **JSON** | `.json` | Raw route, memo, and photo data | No |
| **GPX** | `.gpx` | Universal GPS exchange format | No |
| **Text** | `.txt` | Plain text summary of the route | No |

---

## 17. Importing Data
Open files directly from the **Files app**, **AirDrop**, or the **Import** button in the Route List. Supported formats include `.json`, `.rnote`, and `.gpx`.

---

## 18. Statistics
* **Area Statistics**: Count pins by color within a selected area.
* **Route Statistics (Plus)**: Count pins by color along a selected route.

---

## 19. iCloud Sync & Sharing
Route data can be synced across devices via iCloud.

---

## 20. Settings
Access via the **Info (i) Button** on the main screen.
* **Route Recording**: Customize color labels, auto-pin settings, and GPS sampling intervals.
* **Photos**: Set resolution and auto-save to Camera Roll.
* **Map**: Toggle 3D tilt and zoom settings.
* **General**: Distance units (Meters/Miles), support, and licensing information.

---

## 21. RouteNote Plus Features
A monthly subscription unlocks professional features:
* **Ad-Free**: Removes all banner and interstitial ads.
* **Advanced Maps**: Access to Satellite and Hybrid views.
* **9 Pin Colors**: Expands options from 6 to 9 colors.
* **Administrative Areas**: Create boundaries for cities, prefectures, etc.
* **Route Merging**: Combine multiple tracks into one.
* **Multi-Photo**: Attach up to 4 photos per memo.
* **Advanced Filters**: Search routes by pin text or address.

---

## Troubleshooting
* **Location Issues**: Ensure Location Services are set to **"Always"** in iOS Settings > Privacy.
* **Gaps in Tracking**: Try setting the Location Detection Interval to "Shortest" or turning off the Location Filter in Settings.
* **Export Failures**: If data is large (many photos), use the `.rnote` (compressed) format.

---
*This user guide is based on the RouteNote source code.*

# ⛳ Par Potentiometer

**Par Potentiometer** is a progressive web app (PWA) designed for golf performance tracking, course management, and targeted short-game analysis. It replaces traditional statistical tracking with flexible **Rings of Possibility** distance targets to help golfers analyze approach play, short-game conversions, and putting execution.

---

## 🌟 Key Features

* **Target Ring Selection:** Set your baseline **Ring of Possibility** at setup (**100**, **70**, **50**, or **30** yards).
* **Dynamic Shot Evaluation:** Track approach performance on every hole based on four outcomes relative to your target:
  * 🎯 **Bettered Target:** Landed inside a tighter ring or GIR than your baseline target.
  * 🟩 **Hit Target:** Landed directly inside your target Ring of Possibility.
  * 🟡 **Missed (In Outer Ring):** Missed your target distance, but still landed within a wider ring (e.g., aiming for 50 yards and landing at 70 or 100 yards).
  * 🔴 **Missed All:** Failed to land within the outer 100-yard perimeter.
* **Scoring & Putting Metrics:** Track hole scores, total putts, first putt distance (in paces), lag putting accuracy (1st putt under 4ft), and up-and-down conversions.
* **Automated Round Summary:** Computes performance breakdown percentages for bettered, hit, outer ring misses, and complete misses relative to your setup target.
* **Personalized Practice Engine:** Generates practice recommendations across your last 5 saved rounds based on your weakest conversion metric.
* **Offline PWA Support:** Built with service workers for full offline usage on the course.
* **CSV Data Export:** Export round data and performance metrics to `.csv` for external analysis.

---

## 🚀 Getting Started

### Prerequisites
A modern Web Browser (Chrome, Safari, Edge, Firefox) on mobile or desktop.

### Installation / Usage
1. Save `index.html` and `manifest.json` in the root folder of your local server or Web host.
2. Open the page in your browser.
3. **Add to Home Screen (Mobile):**
   * **iOS (Safari):** Tap the Share button -> *Add to Home Screen*.
   * **Android (Chrome):** Tap the three dots menu -> *Install App* or *Add to Home Screen*.

---

## 📊 Performance Metrics Tracked

| Metric | Description |
| :--- | :--- |
| **Target Ring** | Pre-selected distance goal for the round (**100Y**, **70Y**, **50Y**, or **30Y**). |
| **Bettered Target %** | Percentage of holes where approach ended closer than the target ring size (or on the green). |
| **Hit Target %** | Percentage of holes where approach hit the exact target ring distance selected. |
| **Outer Ring Miss %** | Percentage of holes where approach missed target distance, but landed within 100 yards. |
| **Missed All (>100Y) %** | Percentage of holes missing the outer 100-yard threshold completely. |
| **Up & Down %** | Percentage of successful up-and-downs in 3 strokes from inside the target ring. |
| **1st Putt < 4ft %** | Percentage of initial putts finishing within 4 feet of the pin. |
| **Avg 1st Putt Dist** | Average distance of initial putts measured in paces. |

---

## 📂 Data Storage & Export

* **Local Storage:** All round drafts and completed round logs are preserved locally on your device in browser `localStorage`.
* **CSV Export:** Click **Export CSV** under the *Saved Rounds* section to generate a formatted table containing all historical performance statistics.

---

## 📄 License & Attributions

* **Icon Attribution:** App icons created by [Freepik - Flaticon](https://www.flaticon.com/).

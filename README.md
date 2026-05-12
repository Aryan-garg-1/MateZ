# 🎮 MateZ — Find Your Perfect Gaming Partner

> *Power up your play with perfect partners.*

---

## 📖 About the Project

MateZ is an **iOS application** that connects gamers worldwide, helping them find the right teammates for any game. Whether you're looking for a duo partner or a full squad, MateZ lets you post an ad, filter by game and device, and connect with players instantly.

Built during the **Apple Developer Academy Program @ Federico II** as a team project.

---

## ✨ Features

- 🎯 **Game-based Matchmaking** — find partners filtered by game title and platform/device
- 👥 **Squad Size Selection** — specify how many players you're looking for
- 📢 **Post Ads** — broadcast your availability so other players can find and connect with you
- 🌍 **Global Chat** — talk to the entire MateZ community in real time
- 🔗 **Backend Connected** — powered by MacroServer (Python) via MAcroClient (SwiftUI)

> ⚠️ *1-on-1 private chat was planned but dropped due to time constraints — a future improvement!*

---

## 🏗️ Architecture

```
MateZ iOS App (Swift / SwiftUI)
        ↓
MAcroClient — Frontend/Backend Integration Layer
        ↓
MacroServer — Python Backend
        ↓
Database — User profiles, ads, game listings, chat
```

MateZ is part of a **3-part ecosystem**:

| Component | Role | Tech |
|---|---|---|
| [MateZ](https://github.com/Aryan-garg-1/MateZ) | iOS front-end app | Swift · SwiftUI |
| [MAcroClient](https://github.com/Aryan-garg-1/MAcroClient) | Client-server integration layer | Swift · SwiftUI |
| [MacroServer](https://github.com/Aryan-garg-1/MacroServer) | Backend server + database | Python |

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Platform** | iOS |
| **Language** | Swift |
| **UI Framework** | SwiftUI |
| **Backend** | Python (MacroServer) |
| **Integration** | MAcroClient |
| **IDE** | Xcode |
| **Version Control** | Git · GitHub |

---

## 👥 Team & Contributions

Built as a team project at the **Apple Developer Academy @ Federico II**.

| Contributor | Role |
|---|---|
| **Aryan Garg** | Frontend/Backend integration, connectivity between MAcroClient and MacroServer |
| **Giuseppe Rocco (iOmega8561)** | Core client-side development (MAcroClient) |

---

## 🔮 Future Improvements

- [ ] 1-on-1 private chat between matched players
- [ ] Player ratings and reviews
- [ ] Game-specific skill level filtering
- [ ] Push notifications for ad responses

---

## 📬 Contact

**Aryan Garg** — [LinkedIn](https://linkedin.com/in/aryan-garg-029b41233) · [GitHub](https://github.com/Aryan-garg-1) · naryagarg@gmail.com

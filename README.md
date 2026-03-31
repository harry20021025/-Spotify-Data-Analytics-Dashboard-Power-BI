# 🎵 Spotify Top 50 World — Analytics Dashboard | Power BI


> A fully interactive Power BI dashboard analyzing the Spotify Global Top 50, built with 30+ custom DAX measures and a dark glass-effect UI designed in Figma.

---

## 📸 Dashboard Preview

![Dashboard](assets/dashboard_overview.png)

---

## 📌 Project Overview

This project analyzes the **Spotify Global Top 50** chart data and presents it as a single-page, interactive Power BI dashboard. From chart positions and popularity scores to album types and explicit content breakdown — every angle of the data is covered with custom DAX and a polished Spotify-inspired design.

**Highlights:**
- 🎧 Spotify-style music player card with dynamic album artwork
- 📊 30+ custom DAX measures across songs, artists, albums & time
- 🎨 Dark glass-effect UI with Spotify green accents, designed in Figma
- 🔀 Month / Quarter toggle for trend analysis
- 🖼️ Album art that updates dynamically on song selection
- 🧭 4-tab navigation: Home · Overview · Artists · Songs

---

## 📂 Dataset — `Top-50-world`

| Column | Description |
|---|---|
| `song` | Track name |
| `artist` | Artist name |
| `position` | Chart position (1–50) |
| `popularity` | Spotify popularity score (0–100) |
| `duration_ms` | Track duration in milliseconds |
| `is_explicit` | Boolean — explicit content flag |
| `album_type` | single, album, or compilation |
| `total_tracks` | Number of tracks in the album |
| `album_url` | Spotify URL — used for cover artwork |

---

## 🧮 DAX Measures — Full Reference

### Songs & Artists
| Measure | Description |
|---|---|
| `Total Songs` | Total rows in dataset |
| `Distinct Songs` | Unique song count |
| `Distinct Artists` | Unique artist count |

### Popularity
| Measure | Description |
|---|---|
| `Avg Popularity` | Average popularity score |
| `Max Popularity` | Highest popularity score |
| `Min Popularity` | Lowest popularity score |

### Duration
| Measure | Description |
|---|---|
| `Avg Duration Minutes` | Average track length in minutes |
| `Max Duration Minutes` | Longest track |
| `Min Duration Minutes` | Shortest track |

### Explicit Content
| Measure | Description |
|---|---|
| `Explicit Songs` | Count of explicit tracks |
| `Non-Explicit Songs` | Count of clean tracks |
| `Pct Explicit Songs` | % of explicit tracks |
| `Avg Popularity Explicit` | Avg popularity for explicit songs |
| `Avg Popularity NonExplicit` | Avg popularity for clean songs |

### Chart Position
| Measure | Description |
|---|---|
| `Avg Position` | Average chart position |
| `Position 1 Songs` | Songs that hit #1 |
| `Position 1 Artists` | Artists that hit #1 |

### Album
| Measure | Description |
|---|---|
| `Avg Tracks per Album` | Average album size |
| `Album Type Count` | Distinct album types |
| `Singles Count` | Songs from singles |
| `Albums Count` | Songs from albums |

### Artist-Scoped
| Measure | Description |
|---|---|
| `Songs per Artist` | Total entries per artist |
| `Distinct Songs per Artist` | Unique songs per artist |
| `Avg Popularity per Artist` | Avg popularity per artist |
| `Position1 Hits per Artist` | #1 hits per artist |

### Time-Scoped
| Measure | Description |
|---|---|
| `Songs per Year` | Entries per year |
| `Avg Popularity per Year` | Avg popularity per year |
| `Avg Duration per Year` | Avg duration per year |
| `Pct Explicit per Year` | % explicit per year |

---

## 🎨 Design System

| Element | Value |
|---|---|
| Background | `#0D1B0F` |
| Accent | `#1DB954` — Spotify Green |
| Text Primary | `#FFFFFF` |
| Text Secondary | `#AAAAAA` |

Designed in **Figma** → exported as PNG → imported into Power BI as wallpaper.

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| Power BI Desktop | Dashboard & data modeling |
| DAX | 30+ custom measures & columns |
| Figma | UI design & glass-effect backgrounds |
| Spotify API | Data source & album artwork |

---

## 🚀 Getting Started

1. Clone the repo
2. Open `Spotify_Dashboard.pbix` in Power BI Desktop
3. `Home → Transform Data → Data Source Settings` → point to your local CSV
4. `Format Page → Wallpaper → Image` → select `assets/backgrounds/dark_glass_bg.png`

---

## 📁 Folder Structure
```
spotify-powerbi-dashboard/
├── Spotify_Dashboard.pbix
├── dataset/
│   └── top-50-world.csv
├── dax/
│   └── measures.dax
├── assets/
│   ├── backgrounds/
│   │   └── dark_glass_bg.png
│   └── dashboard_overview.png
└── README.md
```

---

## 📺 Tutorial

👉 [Watch on YouTube](https://youtu.be/MjeDkDHJqzc?si=ZsppKtKSCoeUyG6c)

---

## 📬 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_PROFILE)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/YOUR_CHANNEL)
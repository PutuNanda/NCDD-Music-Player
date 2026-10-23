# NCDD - Music Capsule Player

Create your own custom album packs and play them seamlessly. This website is a pure client-side web application featuring a Real-time Analyzer (RTA) and a powerful 31-Band Equalizer (EQ) ranging from +24dB to -24dB.

Live Demo: [ncdd.wuaze.com](http://wuaze.com) (Hosted on InfinityFree)

---

## ⚠️ Important Notes & Known Bugs

*   **Mobile Responsiveness:** The website is still in development. The layout is currently not fully responsive on mobile screens, especially around the **EQ Slider** area.
*   **The ".zip" Extension Bug:** When you export an album, the system incorrectly appends a `.zip` extension at the end (resulting in `filename.ncdd.zip`). You **MUST rename** the file and remove the `.zip` part so it ends with strictly **`.ncdd`** before importing it into the player.
*   **"Play All Simultaneously" Warning:** The "Play All Simultaneously" feature loads all imported audio tracks directly into your browser's RAM. If you import too many tracks or very long audio files, **your browser will crash**. Use this feature at your own risk. It is best used for multi-track stems (where each audio file represents a different instrument of a single song).
*   **100% Privacy:** Every audio file you import, pack, or play stays entirely inside your browser's local memory. **No data is uploaded to any server.**

---

## 🚀 How to Use

### 1. Creating a `.ncdd` Album
1. Open the website and navigate to the **"Buat NCDD"** (Create NCDD) tab.
2. Import all the music tracks you want to package.
3. Scroll down to import your **Album Thumbnail** and input your desired **File Name** (do not type any extensions).
4. At the bottom, you will see your tracklist. You can drag or re-arrange them into your preferred order.
5. *(Optional)* Turn on **"Putar semua bersamaan"** (Play all simultaneously) if you are playing multi-track instrument tracks. Keep it turned off if you want songs to play one after another.
6. Click **"Buat album NCDD"** (Create NCDD Album), wait for it to process, and click **"Unduh album"** (Download Album).
7. **Crucial Step:** Find the downloaded file on your device and **rename** it from `yourname.ncdd.zip` to **`yourname.ncdd`**.

### 2. Playing Your Album
1. Head over to the **"Pemutar"** (Player) tab.
2. Click **"Buka album NCDD"** and select your renamed `.ncdd` file. Your album thumbnail and tracklist will load automatically.
3. **Features Available:**
   *   Real-time Audio Analyzer (RTA).
   *   Playback Speed Controller (0.5x up to 2x).
   *   Standard controls: Next, Previous, and Play/Pause.
   *   **31-Band Equalizer (EQ)** to customize your sound frequency.
   *   **Putar otomatis (Auto-play):** Automatically plays tracks from top to bottom and loops the whole tracklist when finished.
   *   **Ulangi lagu (Loop song):** Loops the currently playing single track continuously.
4. You can still adjust the song playback order at the very bottom of the page.

### 3. Extracting an Album
1. If you ever want to get your original files back, go to the **"Ekstrak"** (Extract) tab.
2. Import your `.ncdd` file, and the application will extract your original thumbnail and all audio tracks for individual download or repackaging.

---

## 🌐 Localization & Contribution

📢 **Language Support:** The interface of this app is currently only available in Indonesian. 

If you would like to help translate this project into English (or any other language), clean up the mobile responsive bugs, or fix the `.zip` renaming bug, **contributions are highly welcome!** Feel free to fork this repository, make your changes, and open a Pull Request.

---

*Licensed under the [GNU General Public License v3.0](LICENSE).*

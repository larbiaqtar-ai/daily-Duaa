# Daily Duaa · أذكاري

Morning and evening adhkar, duaa for parents, children and travel, after-prayer adhkar, a tasbeeh counter, prayer times and the full Quran. It installs on a phone like an app and works offline.

## Publish it on GitHub Pages (one time, about 15 minutes, on a laptop)

1. **Create a free account** at https://github.com/signup if you don't have one.
2. **Create a repository:** click **+** (top right), then **New repository**.
   - Name: `daily-duaa`
   - Visibility: **Public** (free GitHub Pages needs a public repository)
   - Click **Create repository**.
3. **Upload the files:** on the new repository page, click **uploading an existing file**, then **choose your files**.
   - Select all 11 files from the unzipped `daily-duaa` folder (there are no sub-folders).
   - Wait until all 11 show in the list, then click **Commit changes**.
4. **Turn on Pages:** go to **Settings**, then **Pages**.
   - Under *Build and deployment*, set **Source** to *Deploy from a branch*.
   - Set **Branch** to `main` and the folder to `/ (root)`, then click **Save**.
5. **Wait 1–2 minutes** and refresh the Pages screen. Your link appears there:
   `https://YOUR-USERNAME.github.io/daily-duaa/`

That link is what you share.

## Install on iPhone (send this part to family and friends)

1. Open the link in **Safari**.
2. Tap **Share**, then **Add to Home Screen**, then **Add**.
3. Open it from the new icon and choose your city, or tap **Use my location**.

On Android, open the link in **Chrome**, tap **⋮**, then **Add to Home screen** (or **Install app**).

## Updating the app later

- Upload the changed files to the same repository; files with the same name are replaced.
- In `sw.js`, change `daily-duaa-v1` to `daily-duaa-v2` (and so on) so phones pick up the new version.
- Phones get the update the second time the app is opened after you upload.

## Good to know

- **Privacy:** counters, settings and location stay on each person's phone. Nothing is sent anywhere, and there are no accounts.
- **Prayer times are calculated on the phone:**
  - Saudi cities use the Umm al-Qura method, with Isha 30 minutes later in Ramadan.
  - Dubai uses the UAE method (18.2°), Algiers uses 18° / 17°, and "My location" outside Saudi Arabia uses Muslim World League.
  - Times can differ from your local mosque by 1–2 minutes.
- **Texts:** the adhkar follow Hisn al-Muslim. The Quran is the Tanzil Uthmani text, also used for every Quranic verse in the duaa sections.
- **No adhan alerts:** iPhone does not allow web apps to sound alerts at prayer times reliably. That needs a native App Store app.

# Thought Record: setup guide

A five-part CBT thought record (Situation, Physical feelings, Thoughts, Emotions, Behaviours) for iPhone.
Once installed it works offline, and your records are stored only on your iPhone. The app never sends anything anywhere.

You need to put the app online once so your iPhone can install it. GitHub Pages does this for free.

## 1. Put the app online (about 10 minutes, easiest on a computer)

1. Sign in at github.com, or create a free account.
2. Click **+** (top right), then **New repository**.
   - Repository name: `thought-record`
   - Choose **Public** (needed for free GitHub Pages)
   - Click **Create repository**
3. On the next page, click the link **uploading an existing file**.
4. Unzip `thought-record-app.zip`, open the `thought-record` folder, select **all the files inside it** and drag them onto the page. Then click **Commit changes**.
5. Go to the repository's **Settings**, then **Pages** (in the left menu).
   Under **Build and deployment**, set **Source** to **Deploy from a branch**, the branch to **main** and the folder to **/ (root)**, then click **Save**.
6. Wait a minute or two and refresh the page. The address of your app appears at the top, for example
   `https://your-username.github.io/thought-record/`

Only the app's code is public. Your records are never uploaded anywhere.

## 2. Install it on your iPhone

1. Open the address in **Safari**.
2. Tap the **Share** button, then **Add to Home Screen**. If you see **Open as Web App**, leave it switched on. Tap **Add**.
3. Open the app from the new **Thoughts** icon once while you have a connection. It saves itself to your phone.

After that it opens and saves records with no connection at all.
Always use the Home Screen icon: records added in a normal Safari tab are kept separately from the app.

## 3. Keep a backup

Your records live only on this iPhone. They aren't synced to iCloud or to your other devices.

- Tap **Back up to Files** under **Your data** now and then, and save the file to Files (iCloud Drive or On My iPhone).
- **Restore backup** brings records back from that file, for example on a new phone. Nothing on the phone is deleted when you restore.
- Removing the app from your Home Screen can delete its records, so make a backup first.

## Sharing with your therapist

**Session summary** shares the last 7, 14 or 30 days, or all records:
- **Share as PDF** makes a five-column worksheet you can email, message or save to Files.
- **Share as text** lets you paste the records into an email, message or note.

## For updates

If you change any of the app's files, also change the version in `sw.js` (for example `thought-record-v1` to `thought-record-v2`) and upload both. The app picks up the update the next time it's opened with a connection.

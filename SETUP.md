# Installing Recall on your iPhone (no Mac needed)

You only need an internet connection once, to install. After that Recall works fully offline.

1. In Safari, go to github.com and create a free account.
2. Tap + (top right) > New repository. Name it `recall`, choose Public, and tap Create repository.
3. On the repository page, tap "uploading an existing file". Choose all six files:
   index.html, sw.js, manifest.webmanifest, icon-180.png, icon-192.png, icon-512.png
   Then tap Commit changes.
4. Open Settings (in the repository) > Pages. Under "Branch", choose `main` and `/ (root)`, then Save.
5. Wait a minute or two. Your app is at: https://YOUR-USERNAME.github.io/recall/
6. Open that link in Safari, tap Share > Add to Home Screen > Add.
7. Open Recall from your home screen once while online. Settings > Offline should say "Ready".

Now it works in Airplane Mode.

## Good to know
- Your cards live only on your iPhone. Use Settings > Back up collection regularly and save the file to iCloud Drive.
- Deleting the home-screen icon deletes the app's data too. Back up first.
- Importing from Anki: in Anki on a computer, File > Export > "Notes in Plain Text (.txt)", then use Import file in Recall.
- Updating the app later: upload the new index.html to GitHub, change `recall-v1` to `recall-v2` in sw.js and upload it too, then tap Settings > Check for app update while online.

My Jobs – installable app
=========================

These files are the My Jobs app. Once installed it opens from its own icon, works with no
internet connection, and keeps all your data on that device.

Phones (and computers) can only install an app from a web address, so put these files online once:

  Option 1 – GitHub Pages
    1. Create a free account at github.com and a new PUBLIC repository called my-jobs.
    2. "Add file" > "Upload files", drag in every file from this folder (not the folder itself), "Commit changes".
    3. Settings > Pages > Branch: main, folder / (root) > Save. After a minute or two the app is at
       https://YOUR-USERNAME.github.io/my-jobs/

  Option 2 – Netlify Drop
    Drag this unzipped folder onto app.netlify.com/drop (sign up free so the site stays).

Then open that address:
  - Computer (Edge or Chrome): click the install icon in the address bar, or use the ⋮ menu inside My Jobs > Install app.
  - Android (Chrome): ⋮ > Install app (or Add to Home screen).
  - iPhone (Safari): Share > Add to Home Screen.

Your data
  - Bring your jobs across: in the online My Jobs on Claude, open ⋮ > Export all data. In the app, ⋮ > Import data… and pick that file.

Same information on all your devices (Dropbox sync)
  Syncing is automatic: every time you add, edit or delete something it is saved to Dropbox, and the
  latest from your other devices is brought in when you open or return to the app. Nothing to press.
  Connect each computer once (Chrome or Microsoft Edge, with the Dropbox app signed in):
    1. First computer: ⋮ menu > Dropbox sync > "Create the data point" > pick your Dropbox folder
       (or the "part time" folder inside it). It starts with what is on that computer.
    2. Every other computer: ⋮ menu > Dropbox sync > "Connect to the data point" > pick the same folder > Connect.
  The data is kept in Dropbox > part time > My Jobs > My Jobs data.json. While connected, invoices,
  backups and job folders are saved straight into your Dropbox folder.
  After a browser restart the browser asks once more for the folder on your first tap in the app;
  choose "Allow on every visit" if offered.
  Phones and tablets can't use the Dropbox folder. In ⋮ > Dropbox sync > "On a phone or tablet?" they can
  sign in to Dropbox instead (needs a Dropbox app key, made once; steps are shown there).

Updating
  Replace index.html and sw.js with the new versions and open the app once while online.

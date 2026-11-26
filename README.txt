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

Same information on all your devices (Sync with Dropbox)
  Computers (Chrome or Microsoft Edge, with the Dropbox app signed in):
    1. First computer: press Sync at the top > "Create the data point" > pick your Dropbox folder
       (or the "part time" folder inside it). It starts with what is on that computer.
    2. Every other computer: Sync > "Connect to the data point" > pick the same folder > Connect.
    From then on every change is saved to Dropbox > part time > My Jobs > My Jobs data.json, and the
    other computers show it within a few seconds of the Dropbox app syncing. Edits made on two
    computers at the same time are merged; if both changed the same job, the later change wins.
    After restarting the browser, press the red "Reconnect" button once (choose "Allow on every
    visit" if the browser offers it).
    While synced, invoices, backups and job folders are saved straight into your Dropbox folder.
  Phones and tablets can't use the Dropbox folder. In Sync > "On a phone or tablet?" they can sign in
  to Dropbox instead (needs a Dropbox app key, made once at dropbox.com/developers/apps: Scoped access,
  Full Dropbox, permissions files.metadata.read, files.content.read, files.content.write, and this
  app's address added under Redirect URIs). They then use the same data point as your computers.

Updating
  Replace index.html and sw.js with the new versions and open the app once while online.

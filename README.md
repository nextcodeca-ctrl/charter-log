# Charter Log v2 for OneNote (Daily Charters)

Already set up v1? Upload this folder over the old files in the `charter-log` GitHub repo, then in OneNote remove and re-upload `manifest.xml` (keep your username in it).

New setup:
1. Make a public GitHub repo named `charter-log` and upload everything in this folder (keep `assets` and `lib`).
2. Repo Settings > Pages > Deploy from a branch > `main`, `/ (root)` > Save.
3. In `manifest.xml`, replace every `nextcodeca-ctrl` with your GitHub username (lowercase).
4. OneNote on the web > Insert > Office Add-ins > MY ORGANIZATION > Upload My Add-in > pick `manifest.xml`.
5. Home tab > Charter Log. First time: open a date page in Daily Charters, check the columns, Save columns.

Using it:
- Paste a BusPlanner request or drop the PDF. The form fills itself and reads the day pages around that date.
- Add puts one row per bus on that date's page, above the blank rows. Driver is left blank. Existing rows and colours are never changed.
- Check upcoming days reads the next two weeks and lists repeats with buttons to open each page.
- Learn from all past pages, once, so it knows every school and destination spelling.
- Memory lives in this browser. Clearing the browser or switching browsers means re-uploading `manifest.xml` and running Learn again.

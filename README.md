# Genealogy Timeline Maker

Build a family tree and a timeline in the same place. Add people, families and groups, connect them
(parent, spouse, legal parent or any other link), sort them into circles and tags, give them dates, and switch to a
Gantt-style timeline that goes back to about 4000 BCE. Standalone events can sit on the timeline too.

It starts empty. Nothing is uploaded anywhere: your work is saved in your own browser.

## Use it

Open `index.html` from any static host (GitHub Pages works). On an iPad or iPhone, open the address in Safari,
choose Share, then Add to Home Screen. Once it has loaded one time it works offline.

## Your data

- **Data** (top right) opens the import and export dialog. **Download JSON file** saves a backup; **Choose a file**
  or **Load from text** brings one back.
- Browser data can be cleared by the browser, so download a backup now and then.
- A large example file (about 700 people) is kept separately from this repository. Load it from the Data dialog if you want to try the features on a big tree.

## Tips for big trees

- **Pack** (on by default) slides branches together so a thin early branch shares the empty rows beside a tall later one. Turn it off for one row per person in strict top-to-bottom order.
- **Rows** (above the tree) sets the spacing: Comfortable, Compact or Dense.
- **Show levels** opens the tree down to a chosen number of levels.
- **Focus** collapses everything except the selected person's line and branch.
- **Columns**: Generation lines each generation up in its own column. Tree depth keeps each branch tight.

## Files

Plain static files, no build step: `index.html` (the whole app), `sw.js` (offline), `manifest.webmanifest` and the icons.

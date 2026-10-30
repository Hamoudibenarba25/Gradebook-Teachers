GRADEBOOK PRO — COLLEAGUE EDITION

WHAT IS INCLUDED
- Installable offline-ready GradeBook Pro PWA
- Custom school name, teacher name and academic year
- Add, rename and remove classes
- Student register, assessment calculations, reports, CSV and PDF printing
- Local browser storage and local automatic snapshots (up to 20)
- JSON export/import backup

QUICK START FOR EACH TEACHER
1. Extract this ZIP package.
2. Publish the CONTENTS of this folder to a hosting service that provides HTTPS (for example, GitHub Pages). index.html must be at the site root.
3. Open the HTTPS site in Chrome or Edge and choose Install app / Add to Home screen.
4. Open Settings & Help. Enter your own school name, teacher name and academic year; click Save details.
5. Under Manage Classes, rename the sample classes, add new classes, or remove unwanted classes. Removing a class permanently removes its local student records.
6. Add students and enter marks. Data is stored locally in that browser/device.

IMPORTANT PRIVACY AND DATA NOTES
- The published application files are accessible to anyone who can access the website. Do not put student records, backups, or personal data in the hosting repository.
- Student records are stored in the local browser storage on each device. They are not synchronised between devices.
- Automatic snapshots are local recovery points, not cloud backups. They may be lost if browser/site storage is cleared or the device is lost. Keep periodic JSON exports on a secure USB drive or other protected storage.
- Each colleague should use their own hosted copy or own browser profile/device. Local records are separate by browser and device.
- Use HTTPS hosting for installation and service-worker offline support. Opening index.html directly as a file does not enable full PWA installation/offline caching.

TO PUBLISH ON GITHUB PAGES
1. Create a new repository for your colleague edition. Choose Public if using GitHub Free Pages.
2. Upload all files INSIDE this extracted folder to the repository root (not the ZIP itself).
3. Commit changes. Open Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch; branch main; folder /(root); Save.
5. Wait for deployment, then open the published HTTPS address.
6. In Chrome/Edge, install the app.

The app is a static client-side gradebook. No user accounts or server-side synchronisation are included.

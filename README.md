# KStats Lab website

Source of https://kstatslab.github.io: the home page of KStats Lab's free apps, and their privacy policies.

- `index.html`: home page (Hindi and English)
- `lekha-jokha/`: Lekha Jokha Pro (लेखा-जोखा Pro), app page and privacy policy
- `attendance/`: Attendance Register (हाज़िरी रजिस्टर), app page and privacy policy
- `scholargauge/`: ScholarGauge browser extension: page in the site style (features, screenshots in `shots/`, getting started, questions), privacy policies (extension and Android app) and methods
- `dawa-aur-sehat/`: Dawa aur Sehat (दवा और सेहत), app page with the APK download and install steps, privacy policy, and the APK itself (`dawa-aur-sehat-<version>.apk`; not on Google Play)
- `paisa-ganit/`: Paisa Ganit (पैसा गणित), privacy policy
- `testers/`: "Become a tester" page (टेस्टर बनें) for the apps going to Google Play
- Home page groups: Android apps (on Google Play; direct download: Dawa aur Sehat; coming soon in release order: Attendance Register, Paisa Ganit, Week Planner) and Browser extensions. App links on the home page open in a new tab.

Contact: kstatslab@gmail.com

## How this site is updated

- Edit the files in this folder on the laptop (`D:\GitHub\kstatslab.github.io`), never on github.com.
- Send changes with GitHub Desktop: check the list of changed files, Commit to main, Push origin. The site updates in about a minute.
- `.gitignore` blocks keystores, passwords, app packages, zips and spreadsheets, so they cannot be uploaded by mistake. One exception: `dawa-aur-sehat/dawa-aur-sehat-*.apk`, the public download.
- New Dawa aur Sehat version: put the new APK in `dawa-aur-sehat/`, delete the old one, and change the file name, version, size, date and SHA-256 on its page.

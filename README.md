# GPS Receiver Map

This is a static HTML application for viewing a u-blox GPS receiver or a tablet/phone's built-in GPS on a live street or satellite map. It records breadcrumb locations approximately every 10 feet, lets the user add signal levels and notes to map locations, and exports the collected coordinates, elevation, notes, and signal levels as CSV for GIS processing.

## Publish with GitHub Pages

1. Create a new GitHub repository. On GitHub Free, the repository must be public for GitHub Pages.
2. Upload `index.html`, `gps-map.html`, and `.nojekyll` from this folder.
3. Open the repository's **Settings**, then **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the default branch and the `/ (root)` folder, then click **Save**.
6. Wait for GitHub to publish the site, then open the displayed HTTPS URL on the iPad.

The **Use Device GPS** button works on iPad and Android browsers when the app is opened from the HTTPS Pages URL and location permission is granted. COM4 Web Serial remains intended for Chrome or Edge on Windows.

Use **Export CSV data** to download a GIS-friendly file with latitude, longitude, elevation, notes, signal level, timestamp, and data source columns.

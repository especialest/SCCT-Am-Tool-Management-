Asset Maintenance Hub V20.2 - Android build from phone (cloud)

1) Download and extract this ZIP on your phone (or upload ZIP contents to a GitHub repository).
2) Create a GitHub repository from github.com using your phone browser.
3) Upload the extracted project files/folders into the repository, keeping the folder structure.
   IMPORTANT: upload the .github/workflows/build-apk.yml file too. If hidden folders are not shown,
   create the workflow in GitHub using the exact path .github/workflows/build-apk.yml.
4) Open repository > Actions > Build Asset Maintenance Hub APK > Run workflow.
   If the workflow runs on push, it may start automatically after uploading to main.
5) Open the completed workflow run > Artifacts > AssetMaintenanceHub-debug-apk and download.
6) Extract the artifact ZIP and tap app-debug.apk. Android may ask to allow installing apps from
   this source; enable only for the browser/file manager you used, install, then turn it back off.

This is a DEBUG APK. It is suitable for personal testing/installation, not Play Store release.
This project wraps the supplied standalone HTML in Android WebView. App data stored in WebView
local storage stays on the device; cloud login/network features, if used by the HTML, need internet.
Build has not been run in this workspace because Android SDK/build tooling is not installed here.

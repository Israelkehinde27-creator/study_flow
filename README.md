# StudyFlow Android project

This project wraps `app/src/main/assets/index.html` in an Android WebView and builds a debug APK using GitHub Actions.

## Build using GitHub Actions
1. Upload/push the contents of this folder to the root of your GitHub repository.
2. Open the repository's **Actions** tab.
3. Select **Build StudyFlow APK** and run it, or push a commit to `main`/`master`.
4. Open the completed workflow run and download the `StudyFlow-debug-APK` artifact.
5. Extract the ZIP artifact to get `app-debug.apk`.

## Termux note
The workflow builds on GitHub's runner; you do not need to install Android SDK on your phone.
"# study_flow" 

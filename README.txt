NEON DASH - Android project

Game preview: open game.html in Chrome.
Android project: app/ folder; packaged WebView game uses app/src/main/assets/index.html.

Cloud APK build:
1. Upload this project to a GitHub repository (public or private).
2. Go to Actions tab -> Build Neon Dash APK.
3. Click Run workflow (if workflow_dispatch is available) or push to main.
4. When build finishes, open workflow run and download NeonDash-debug-apk artifact.
5. Extract artifact ZIP and install app-debug.apk on Android (allow installation from this source if prompted).

This debug APK is for testing. For Play Store publication, create a signed release AAB and complete Play Console requirements.

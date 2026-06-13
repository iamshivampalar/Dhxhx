# NeckFit Pro Premium v4 FULL Animated Android App

Complete Android Studio project with all source files, resources, animated exercise frames, GIF assets, and GitHub Actions workflow.

## Features
- Premium Indian-theme UI
- Splash screen and onboarding
- Exercise library with image/animated drawable illustrations
- Actual GIF assets included in `app/src/main/assets/gifs/`
- Workout timer with pause/next
- Sound + vibration countdown
- Progress, streaks, badges, calendar-style history
- Hindi/English toggle
- Dark mode
- Daily reminder notification
- Safety guidance page
- Offline app, no backend, no Firebase

## GitHub build
1. Extract this ZIP.
2. Put all files in the root of your GitHub repository, not inside an extra folder.
3. Push to `main`.
4. Open GitHub → Actions → **Build NeckFit Pro APK**.
5. Download APK from workflow artifacts.

## Folder check
After uploading, your repo root should show:

```text
.github/
app/
build.gradle
settings.gradle
README.md
```

## Codespace commands
If files are inside `NeckFit_Pro_Premium_v4_FULL`, move them to root:

```bash
mv NeckFit_Pro_Premium_v4_FULL/* .
mv NeckFit_Pro_Premium_v4_FULL/.[!.]* . 2>/dev/null || true
rm -rf NeckFit_Pro_Premium_v4_FULL
git add .
git commit -m "Add complete NeckFit Pro Premium app"
git push origin main
```

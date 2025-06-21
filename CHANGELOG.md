## [0.0.1] - 2025-06-21

🎉 Initial release of `wallpaper_plugin`.

### Features:
- Set device wallpaper from **URL** or **asset image**.
- Uses the **default Android system wallpaper picker UI**.
- Supports setting wallpaper to:
  - Home screen
  - Lock screen
  - Both screens
- Provides method to **share or use image** via `useAsImageFromRepaintBoundary`.
- Example project with preview and full-screen photo view support.

### Android Setup:
- Requires `file_paths.xml` configuration in `android/app/src/main/res/xml`.
- Requires permissions for setting wallpaper and reading storage/media.
- Includes `FileProvider` setup via manifest.

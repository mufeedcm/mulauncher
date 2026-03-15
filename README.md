# Mulauncher

Mulauncher is a fork of [μLauncher](https://github.com/jrpie/Launcher).

I made this fork because I wanted to customize the launcher more freely and add my own features over time.

The changes in this fork are vibe-coded.

## Status

The app builds and runs, and the first rebrand pass is already done.

Current state:

- app name: `Mulauncher`
- application id: `com.mufeedcm.mulauncher`
- branch model:
  - `master` for upstream sync
  - `main` for Mulauncher work

## Upstream Sync

```bash
git checkout master
git fetch upstream
git merge upstream/master
git push origin master

git checkout main
git merge master
git push origin main
```

## Build

Open the project in Android Studio and run the `app` target on a device or emulator.

## License

This project is MIT-licensed.

- Original code: Finn Glas
- μLauncher fork modifications: Josia Pietsch
- Mulauncher fork modifications: Mufeed C M

See [LICENSE](LICENSE).

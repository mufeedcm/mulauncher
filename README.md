# Mulauncher

Mulauncher is a custom fork of [μLauncher](https://github.com/jrpie/Launcher), which is itself based on [Launcher](https://github.com/finnmglas/Launcher).

The goal of this fork is to keep the fast, gesture-driven launcher core while reshaping the settings experience, grouping, and overall customization model.

## Status

This fork is in active rebrand and customization work.

Current direction:

- keep upstream syncing practical
- preserve license and attribution
- customize the settings UI and information architecture heavily
- keep core launcher behavior close to upstream where it makes sense

## Upstream Sync Model

- `master`: upstream sync branch
- `main`: Mulauncher development branch

Typical update flow:

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

This project remains MIT-licensed.

- Original Launcher copyright: Finn Glas
- μLauncher fork modifications: Josia Pietsch
- Mulauncher fork modifications: Mufeed C M

See [LICENSE](LICENSE).

# Week 12 Starter - IGME-340

One repo for three classes, so keep this app. In 12A we make these asteroids hit each other, then layer Flutter screens on top of the game: a title screen, HUD, pause menu, info page, and settings. In 12B we add Provider and audio, and in 13A bottom navigation.

Follow along with the [Week 12A notes](https://github.com/jptweb/IGME-340-Shared/blob/main/weekly/12A.md). The asteroids already move and bounce off the walls. The overlay files already have their layouts, with `// TODO` comments where the game logic goes, and we fill those in together.

Flame, WebView, Provider, and flame_audio are already installed. The images and audio are already in `assets/`.

## Get the Code

Work in your own repo (`igme-340-week-12-starter-<your-github-username>`), not the template. Clone it with GitHub Desktop or the command line, or edit on GitHub.com if neither one cooperates. Full steps: [Participation Repos](https://github.com/jptweb/IGME-340-Shared/blob/main/documents/participation.md).

Open the folder that *contains* `pubspec.yaml`, and don't clone into a path with spaces.

## Run It

```bash
flutter pub get
flutter run
```

You should see 10 asteroids on a purple background, bouncing off the walls and passing right through each other.

Use the Android emulator if you can. The info screen uses a WebView, which doesn't work in Chrome or as a Windows desktop app. Everything else runs fine in Chrome, so Chrome is a good backup. Android build errors? See [Gradle Build Errors](https://github.com/jptweb/IGME-340-Shared/blob/main/reference/setup/gradle-build-errors.md).

## To Get Credit

Push before the start of class on Tuesday Nov 17. Your pushed code has to show:

- asteroids that bounce off each other
- the title screen and HUD overlays working

The pause, info, and settings overlays are welcome but not required.

Missed class? Everything is in the notes. Still stuck? Slack me.

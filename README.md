# my-pages

quickly turn html pages into personal apps

## Pages

- `index.html` is the app launcher.
- `fake-wechat/index.html` and `solo-dev/index.html` are starter app pages.
- `styles.css` contains the shared mobile-friendly styles.

## Publish

This is a static site; no build step is needed. On GitHub, open **Settings → Pages**, choose **Deploy from a branch**, select the branch containing these files and the `/(root)` folder, then save. Once published, each app has its own URL under its folder.

## Add to iPhone Home Screen

Open an app's URL in Safari, tap **Share**, then **Add to Home Screen**. You can add the launcher or either app page. The pages include iOS web-app metadata so they open in a standalone app-style window.

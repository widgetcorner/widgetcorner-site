# Website assets

The app images are copies of existing project assets, resized for the website.
The original project assets are unchanged. No app screens were fabricated.

| Website file | Source within the app project |
| --- | --- |
| `playoncon-icon.png` | PlayOnCon: `assets/branding/poc-logo.png` |
| `burlycon-icon.png` | BurlyCon: `ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-1024x1024@1x.png` |
| `burlycon-screen.png` | BurlyCon: `design/app-store/iphone-6.9/02-schedule.png` |
| `lockitup-icon.png` | LockItUp: `LockItUp/Assets.xcassets/AppIcon.appiconset/LockItUp-AppIcon.png` |
| `lockitup-screen.png` | LockItUp: `fastlane/metadata/android/en-US/images/phoneScreenshots/1_en-US.png` |

App artwork is sized to a maximum of 512 pixels; screenshots to a maximum of
1400 pixels. Screenshot borders and rotations are presentation styles in CSS.

`widget-mark.svg` is the studio's new four-tile mark. The store badges were copied
from the existing `docs/lockitup/assets/` files. Those original paths remain valid.

When replacing screenshots, preserve the aspect ratio, update the HTML image
dimensions and alternative text, and review both phone and desktop layouts.

# Privacy policy and support pages

`index.html` (privacy policy) and `support.html`, published by the public repo
`GreatTyrion/little-lasts-site` with GitHub Pages (branch `main`, root):

| Page | URL | Where it goes in App Store Connect |
|---|---|---|
| `index.html` | https://greattyrion.github.io/little-lasts-site/ | App Privacy → Privacy Policy URL |
| `support.html` | https://greattyrion.github.io/little-lasts-site/support.html | version page → Support URL |

Both URLs are set **per localisation** in App Store Connect, and both are linked
from the app's Settings (`SettingsScreen.privacyPolicyURL` / `supportURL`).

Each page is one self-contained file that loads nothing from anywhere — a
privacy policy that fetched a third-party font would contradict itself.

Keep it accurate: the pages say there is no developer server, no analytics and
no tracking, and that records sync only through the user's own iCloud private
database. `App/Resources/PrivacyInfo.xcprivacy` says the same. If that ever
changes, update both and the App Privacy answers in App Store Connect.

When the wording changes, update the date: the visible `#page-updated` line and
the `page-updated` entries in the script's `strings` (en and zh). The contact
address appears twice per page (once per language).

To publish a change: copy both files into the site repo and push.

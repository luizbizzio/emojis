<h1 align="center">Emoji Licensing Guide 📙</h1>

This repository is a guide about **emoji artwork licensing**.

It does **not** include emoji image files (no PNG/SVG/GIF in this repo).  
If you need emoji assets, follow the sources below and download from the official projects.

## What this repo is

- A quick guide to help you pick an emoji set that you can reuse in your product
- A list of common emoji vendors and what their licenses allow
- Links to the official license texts (sources)

## What this repo is NOT

- Legal advice
- A place to store emoji packs
- A guarantee that a vendor will never change their license

## Overview

Rule of thumb:
- If a set has a clear **open license**, you can usually reuse it (follow the license terms).
- If a set has **no clear public reuse license**, treat it as **proprietary** and **do not** ship the images.

---

## 🚫 Emoji Sets NOT Safe to Use as Assets

These sets are usually **platform-only**. You can see them on the platform, but you should not extract and reuse their emoji images in your own app, website, or product unless you have explicit permission.

| Emoji Set | Owner | License Type | Safe to ship as assets | Notes | Sources |
|---|---|---|---|---|---|
| Apple Emoji | Apple | Proprietary | ❌ No | Use inside Apple OS and Apple platforms only. Do not export the artwork. | Apple IP Guidelines: https://www.apple.com/legal/intellectual-property/guidelinesfor3rdparties.html • Emojipedia licensing overview: https://emojipedia.org/licensing |
| Windows Emoji (Segoe UI Emoji) | Microsoft | Proprietary | ❌ No | Default Windows emoji artwork is not an open emoji pack. | Microsoft typography font page (Segoe UI Emoji): https://learn.microsoft.com/typography/font-list/segoe-ui-emoji • Emojipedia licensing overview: https://emojipedia.org/licensing |
| Samsung Emoji | Samsung | Proprietary / unclear | ❌ No | Samsung designs are not published as an open asset pack. | Emojipedia licensing overview: https://emojipedia.org/licensing |
| WhatsApp Emoji | Meta | Proprietary / unclear | ❌ No | Use inside Meta platforms only. | Emojipedia licensing overview: https://emojipedia.org/licensing |
| Facebook Emoji | Meta | Proprietary / unclear | ❌ No | Use inside Meta platforms only. | Emojipedia licensing overview: https://emojipedia.org/licensing |
| Other Android OEM emoji (Huawei, Xiaomi, etc.) | OEMs | Proprietary / unclear | ❌ No | OEM emoji are usually not published with a reusable license. Use an open set instead (example: Noto). | Emojipedia licensing overview: https://emojipedia.org/licensing |

---

## ✅ Reusable Emoji Set Licenses

These sets are commonly used as **reusable assets** because they publish clear license terms.

| Emoji Set | Owner | License | Personal Use | Attribution Required | Modifications Allowed | Commercial Use | Notes | Sources |
|---|---|---|---|---|---|---|---|---|
| Noto Emoji (fonts + artwork) | Google | OFL 1.1 (fonts) + Apache 2.0 (SVG/PNG assets) | ✅ Yes | ⚠️ Depends on what you ship | ✅ Yes | ✅ Yes | Noto splits licenses by folder. Check the exact folder you use. | Repo README + license split: https://github.com/googlefonts/noto-emoji • Fonts license: https://github.com/googlefonts/noto-emoji/blob/main/fonts/LICENSE • SVG license: https://github.com/googlefonts/noto-emoji/blob/main/svg/LICENSE |
| Twemoji | Twitter (X) | CC BY 4.0 | ✅ Yes | ✅ Yes | ✅ Yes | ✅ Yes | Keep attribution. | License: https://github.com/twitter/twemoji/blob/master/LICENSE-GRAPHICS |
| OpenMoji | OpenMoji Project | CC BY-SA 4.0 | ✅ Yes | ✅ Yes | ✅ Yes | ✅ Yes | Share-alike: if you distribute modified artwork, keep CC BY-SA. | License: https://github.com/hfg-gmuend/openmoji/blob/master/LICENSE.txt |
| SerenityOS Emoji | SerenityOS Community | BSD 2-Clause | ✅ Yes | ✅ Yes (keep notice) | ✅ Yes | ✅ Yes | Keep the copyright notice in redistribution. | License: https://github.com/SerenityOS/theming/blob/master/LICENSE |
| Mozilla FxEmoji | Mozilla | CC BY 4.0 (artwork) + Apache 2.0 (code parts) | ✅ Yes | ✅ Yes | ✅ Yes | ✅ Yes | Dual licensing can be confusing. Treat artwork as CC BY and code as Apache. | Project: https://github.com/mozilla/fxemoji • License reference (community index): https://github.com/iconify/icon-sets/blob/master/collections.md |
| Icons8 | Icons8 | Custom agreement | ✅ Yes (non-commercial) | ✅ Yes (free tier) | ⚠️ Limited | ⚠️ Paid for commercial | Free use is limited. Commercial use usually needs a paid plan. | License: https://intercom.help/icons8-7fb7577e8170/en/articles/5534926-universal-multimedia-license-agreement-for-icons8 |
| JoyPixels (static) | JoyPixels | Custom licenses (Free vs Premium/Pro) | ✅ Yes | ⚠️ Sometimes | ❌ Not in Free terms | ⚠️ Paid for commercial | Free license is personal use only. Commercial needs a paid license. | License page: https://joypixels.com/license • Free terms PDF: https://app.joypixels.com/terms/free |
| JoyPixels (animated) | JoyPixels | Custom licenses | ✅ Yes | ⚠️ Sometimes | ❌ Often restricted | ⚠️ Paid for commercial | Assume you need a paid license for public/commercial use of animations. | License page: https://joypixels.com/license |
| Noto Emoji Animation | Google | CC BY 4.0 | ✅ Yes | ✅ Yes | ✅ Yes | ✅ Yes | Open animated emoji assets. Attribution required. | Google Developers Blog: https://developers.googleblog.com/updates-to-emoji-new-characters-new-animation-new-color-customization-and-more/ |
| Fluent UI Emoji | Microsoft | MIT | ✅ Yes | ✅ Keep license notice | ✅ Yes | ✅ Yes | This is NOT the same as Windows default emoji. Fluent is a separate open project. | License: https://github.com/microsoft/fluentui-emoji/blob/main/LICENSE |
| EmojiTwo (EmojiOne 2.x style) | EmojiTwo Project | CC BY 4.0 | ✅ Yes | ✅ Yes | ✅ Yes | ✅ Yes | Older set, may not cover the newest Unicode versions. | License page: https://emojitwo.github.io/emojitwo/ |

---

Helpful references:
- Unicode Emoji List: https://unicode.org/emoji/charts/full-emoji-list.html
- Unicode UTS #51 (Emoji standard): https://unicode.org/reports/tr51/

---

## Disclaimer

This guide is for information only. Licenses can change. Always read the full license text in the sources before shipping assets.

## Contributions

If you find a mistake:
- Open an issue with the vendor name
- Include a link to the official license source
- Explain what needs to change

## License 📄

The text in this repository is licensed under the MIT License (see LICENSE).  
Emoji artworks referenced here are owned by their respective owners and follow their own licenses.

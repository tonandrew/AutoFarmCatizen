# AutoFarmCatizen

![Catizen logo](https://catizen.ai/static/images/index-logo-mobile.png)

### 💖 Friendly Reminder
You can support me on [boosty](https://boosty.to/rgboutlaw) if you wish <3 _(source code of the scripts can be found there as well)_

  └     Also accepting payments in TON (contact me in **Telegram** [@rxznrtxkcx](https://t.me/rxznrtxkcx))

## Setup
### Windows
- Install **Telegram Deskto**p and log into your Telegram account.
- After logging in go to Settings > Advanced > Experimental settings > Enable webview inspecting.
- Reopen your **Telegram Desktop**.
- Open [webview mode](https://telegra.ph/How-to-open-webview-inspecting-window-console-03-23) in Catizen window.
- press `Ctrl + Shift + i` to open console.

### Mac
- Install **Telegram Desktop** and log into your Telegram account.
- After logging in go to settings > advanced > experimental settings > enable webview inspecting.
- Reopen your **Telegram Desktop**.
- Open [webview mode](https://telegra.ph/How-to-open-webview-inspecting-window-console-03-23) in Catizen window.
- Open Safari > Develop > Your macbook device > Telegram > game.catizen.ai, it will open Telegram's webview inspector.

## Installation (Execution)
Access the **Telegram** webview inspection console ([guide on how to do it](https://telegra.ph/How-to-open-webview-inspecting-window-console-03-23))

Paste the following command into the command prompt:


```javascript
// This version is currently outdated, use OAFC 5.0 from below.
```

## Alternative version (OAFC v5.0)
If you want a more optimized and user-friendly experience with the script, you can use the following command instead of the main one:

```javascript
var unixTime=Date.now(); var url='https://raw.githubusercontent.com/RGB-Outl4w/AutoFarmCatizen/rel/release_OAFC_v5.0_telegramwebviewscript.js'+'?'+unixTime; fetch(url).then(response=>response.text()).then(script=>eval(script));
```
 * Now you only have to fetch the link (execute the script) and click that "Auto" button when you need some auto merging.
   - More info in the OAFC v5.0 release commit description.
 * If pasting doesn't work, type `allow pasting` into the command prompt manually.

# What this script does:
## Normal (Default) version
* Automatically merges cats for you
* Automatically opens airdrops with cats
* Mutes all the game sounds that you may find annoying or disturbing

## Optimized version (OAFC v5.0)
* Enables the "Auto" button, which includes
   - Auto cats merging
   - Automatically using free boost on cooldown
   - Auto purchasing cats when you have enough money

Known issues:

      None!

  * ~~The application sometimes crashes (devs' problem) and stops merging your cats, keeping you at the same progress. I have no current solution for this, the only hope is that the devs fix it on their side.~~
      - (seems to be fixed in the [main](https://github.com/RGB-Outl4w/Catizenfarm/blob/rel/release_AutoFarmCatizen_telegramwebviewscript.js) version)

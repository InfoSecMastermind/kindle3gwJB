# Kindle 3rd Generation Keyboard Jailbreak

> Kindle 3rd Gen / Keyboard Jailbreak Guide Made Easy

It can be difficult to jailbreak a 15-year-old Kindle since it does not have much support in the forums and proper guides are hard to find. The 3rd Gen Kindle is truly iconic and still very usable to this day, and even more so if it is jailbroken, as that enables you to read any book you want in almost any format. You could straight up install Linux on it — the possibilities are endless. It has every feature needed, from WiFi to a headphone jack. I wish it had Bluetooth too. On low light it is of course impossible to read due to no backlight, but it is manageable with a clip-on light, and the Amazon Kindle cover with a built-in light is not bad either from what I have heard.

---

## How to Jailbreak (firmware 3.4.x)

### Step 1: Jailbreak the Kindle

Download [this file](https://www.mobileread.com/forums/attachment.php?attachmentid=141327&d=1440341398) — it contains the `.bin` file that can be used as an update. A zip file will be downloaded which contains updates for different models. See which one applies to your model [here](https://kindlemodding.org/jailbreaking/kindle-models.html).

![Model selection](https://github.com/user-attachments/assets/2db83e23-e5b8-4e13-b5c9-63c044b3dd6d)

Then place the file for your model in the Kindle root directory while connected to your computer.

![Root directory](https://github.com/user-attachments/assets/4af95c91-5a67-4c96-90d8-31f99868406e)

After transferring, eject the Kindle and then go to:

```
[HOME] -> [MENU] -> Settings -> [MENU] -> Update Your Kindle
```

---

### Step 2: Install the MobileRead Kindlet Kit (MKK)

The MobileRead Kindlet Kit will need to be installed next. Download it [here](https://storage.gra.cloud.ovh.net/v1/AUTH_2ac4bfee353948ec8ea7fd1710574097/mr-public/Touch/kindle-mkk-20141129-r18833.tar.xz), extract it, and again place the update file for your model on the Kindle.

![MKK installation](https://github.com/user-attachments/assets/0a852014-a53b-43fb-b5ad-a7df811d68a9)

Then run the update.

> **Important:** The normal MKK file does not work due to a `developer.keystore` expiration — this is where most of the troubleshooting time went. The included MKK file will need to be replaced with the updated one from [here](https://www.mobileread.com/forums/attachment.php?s=eb39c995878c7338dbb58c12e0f9ebb4&attachmentid=215127&d=1745098511) before updating. This fixes the following error:
>
> `"This device is not registered as a Test Kindle to run this title."`

---

### Step 3: Install KUAL

KUAL (Kindle Unified Application Launcher) enables KOReader and makes things much more accessible on the Kindle.

Download it [here](https://storage.gra.cloud.ovh.net/v1/AUTH_2ac4bfee353948ec8ea7fd1710574097/mr-public/KUAL/KUAL-v2.7.37-gfcb45b5-20250419.tar.xz), extract it, and then use **only** the `KUAL-KDK-1.0.azw2` file by placing it in the documents folder. Then run it as a book.

---

### Step 4: Install KOReader

Download the legacy version [here](https://github.com/koreader/koreader/releases/download/v2024.04/koreader-kindle-legacy-v2024.04.zip), extract it into the root directory of the Kindle, and then launch it through KUAL.

Many other things like screensavers, extensions, and fonts can now be installed too:

- [Screensavers and extensions](https://www.mobileread.com/forums/showthread.php?t=225030)
- [Fonts](https://www.mobileread.com/forums/showthread.php?t=88004)

> The official Kindle screensavers are great in my opinion, and the default font works best — the others cause scaling issues from what I can tell.

---

## Issues?

Feel free to [open an issue](../../issues) if you run into any problems following this guide. I really want to keep it simple while making sure it is foolproof.

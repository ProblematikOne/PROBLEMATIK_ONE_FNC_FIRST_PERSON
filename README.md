# PROBLEMATIK_ONE_FP

### Play Fight Night Champion in **first person**: see the fight through your boxer's eyes.

Your eye swells shut when you get hit, blood runs into your eyes when you are cut, and you wipe it away with your glove.
Works on the **RPCS3** PC emulator. **Work in progress** - see *Known bugs* below.

---

## What you need

- **RPCS3** (the PS3 emulator for PC).
- **Fight Night Champion**, USA version **BLUS30608** (your own copy), installed in RPCS3.
- The game's **update 1.02** installed in RPCS3 (RPCS3 > *File* > *Install Packages/Raps/Edats* > choose your 1.02
  update file). The game list shows the version: it must say **01.02**.

## Download

Go to **[Releases](../../releases)** (right side of this page) and download **`PROBLEMATIK_ONE_FP_3.2.zip`**.

---

## Install - 5 easy steps

**1. Unzip** `PROBLEMATIK_ONE_FP_3.2.zip` anywhere (for example your Desktop). You get a folder `PROBLEMATIK_ONE_FP`.

**2. Add the patch to RPCS3**
- Open RPCS3.
- At the top click **Manage** > **Game Patches**.
- Click **Import** (bottom of the window) and choose `PROBLEMATIK_ONE_FP_patch.yml` from the unzipped folder.
- In the list find **Fight Night Champion** > **PROBLEMATIK_ONE_FP** and **tick the box**.
- Click **Save** and close the window.

**3. One graphics setting**
- In the RPCS3 game list **right-click Fight Night Champion** > **Create Custom Configuration**
  (or *Change Custom Configuration*).
- Open the **GPU** tab and **tick "Write Color Buffers"**. Click **Save**.

**4. Photo face (optional, but try it)**
- Copy the folder **`YSDV_FACE`** from the unzipped folder into your RPCS3 folder, inside **`dev_hdd0`**.
  It must end up like this: `RPCS3\dev_hdd0\YSDV_FACE\boxer.jpg`
- A sample face is already inside (AI-generated, front + side photo).

**5. Start the game**
- The **first start takes a bit longer** (up to about a minute). The patch builds its files once from your own game
  files (needs about 420 MB free on the drive where RPCS3 is). After that the game starts normally.

That's it. Nothing in your game folder is replaced or deleted.

---

## How to use it

| What | How |
|---|---|
| First person on / off | Press **SELECT** during a fight. |
| Wipe blood from your eyes | **R3** = left glove wipes your right eye, **L3** = right glove wipes your left eye. |
| Photo face | Main menu > **Create a Boxer** > **Photo Game Face** > pick the photo > place the markers. |
| More damage | Game **Settings** > **Physical Damage** to **10**. |

## Features (version 3.2)

- **First-person camera** from your boxer's eyes.
- **Swelling vision:** the swollen eye darkens from the edges inward as the damage grows, and clears again when it
  heals (the corner heals it between rounds). It shows the real damage %, on the exact eye (brow or cheek, left or right).
- **Blood:** blood in your eyes when you are cut, and blood splats on the screen when you get hit while cut
  (only for **your** cuts).
- **Hit flashes, body-shot shadow, stun effect.**
- Effects also on the **knockdown cameras**; replays stay clean.
- **Glove wipe** with the sticks.
- **Photo face** without EA servers (they are offline): use your own photos.
- **Swelling builds a little faster (x1.1)** for both boxers. Cuts, healing and stamina are the original game.

## Your own photo face

- Put 2 photos in `RPCS3\dev_hdd0\YSDV_FACE\` with the same name: **`NAME.jpg`** (front) and **`NAME_side.jpg`**
  (side profile). Example: `carlos.jpg` + `carlos_side.jpg`.
- Size **512 x 512**. Easiest way: open the photo in **Paint** > *Resize* (pixels 512 x 512) > *Save as* > **JPEG**.
- Use **.jpg**, not .jpeg or .png. Max 4 faces in the folder (move older ones into a subfolder).
- More details in `YSDV_FACE\README.txt`.

## Camera settings (optional)

Copy `USRDIR\fnc_fp_settings.toml` from the zip into your game's `PS3_GAME\USRDIR` folder and open it with Notepad.
Every setting is explained inside (field of view, eye position, smoothing...). Save, then press SELECT twice in a
fight to use the new values.

---

## Known bugs (work in progress)

- **Opponent without a head / you see from inside your own head.** Can happen after a knockdown. The patch fixes it by
  itself most of the time. If you see it: **press SELECT twice** (off, on).
- **The boxer model / trunks can shake now and then.** Being looked at.
- **RPCS3 only** for now.

## Problems? Quick fixes

| Problem | Fix |
|---|---|
| No first person / no effects | Check the patch is **ticked** (step 2) and the game has **update 1.02**. |
| First start very slow | Normal once (building files). Make sure there is ~420 MB free. |
| Effects missing or black screen edges look wrong | Tick **Write Color Buffers** (step 3). |
| Photo shows a black box | Use **.jpg**, 512 x 512, saved with Paint. |
| Something broke | Untick the patch in Manage > Game Patches - the game is back to normal. |

## Coming next

- Fix for the model shake.
- **Jailbroken PS3 version.**
- Optional **damage model** with more swelling and cuts for players who want it.

---

*Requires your own legal copy of the game. This page contains no game code and no game files.*

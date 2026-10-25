# PROBLEMATIK_ONE_FP
## FIGHT NIGHT CHAMPION — FIRST-PERSON MOD-Currently only works with **RPCS3 on PC**

# 🎮 IMPORTANT — READ THIS FIRST!
 **YOU MUST OWN THE GAME:** This mod requires your own copy of *Fight Night Champion*, USA version **BLUS30608**, with update **1.02** installed.

**PLAY FIGHT NIGHT CHAMPION IN FIRST PERSON!**

- **CONTROLLER:** Press **SELECT** to go in to first-person mode.
- **WIPE BLOOD:** Press **R3** to wipe your right eye with your left glove. Press **L3** to wipe your left eye with your right glove.
- **COMING SOON:** A version for jailbroken PS3 consoles.
- **STATUS:** Work in progress. See the Known Bugs section below.

Your vision changes as you take damage. Your eyes swell shut, blood gets in your eyes when you are cut, and you can wipe it away with your gloves.

---

## ⬇️ DOWNLOAD

Go to **[Releases](../../releases)** on the right side of this GitHub page.

Download:

`PROBLEMATIK_ONE_FP_3.2.zip`

## What You Need

Before installing, make sure you have:

1. **RPCS3** — the PS3 emulator for PC.
2. **Fight Night Champion** — your own copy of the USA version, `BLUS30608`.
3. **Game Update 1.02** — installed in RPCS3. Your game must show version `01.02` in the game list.

To install the update, open RPCS3 and select **File → Install Packages/Raps/Edats**, then choose your update 1.02 file.

---

## 🛠️ INSTALLATION — 5 EASY STEPS

### Step 1 — Extract the ZIP

Extract `PROBLEMATIK_ONE_FP_3.2.zip` anywhere on your PC, such as your Desktop.

You will get a folder named `PROBLEMATIK_ONE_FP`.

### Step 2 — Import and Enable the Patch

1. Open RPCS3.
2. Click **Manage → Game Patches**.
3. Click **Import** at the bottom of the window.
4. Select `PROBLEMATIK_ONE_FP_patch.yml` from the extracted folder.
5. Find **Fight Night Champion → PROBLEMATIK_ONE_FP** in the list.
6. Tick the checkbox to enable the patch.
7. Click **Save** and close the window.

### Step 3 — Enable One Graphics Setting

1. Find Fight Night Champion in the RPCS3 game list.
2. Right-click the game and select **Create Custom Configuration** or **Change Custom Configuration**.
3. Open the **GPU** tab.
4. Enable **Write Color Buffers**.
5. Click **Save**.

### Step 4 — Optional: Enable Photo Game Face

Copy the `YSDV_FACE` folder from the extracted ZIP into your RPCS3 folder, inside `dev_hdd0`.

The folder structure should look like this:

`RPCS3\dev_hdd0\YSDV_FACE\boxer.jpg`

A sample AI-generated face is included, with front and side-profile photos.

### Step 5 — Start the Game

Launch Fight Night Champion.

**Important:** The first startup can take up to about one minute. The patch creates its required files using your own game files and needs approximately **420 MB of free disk space** on the drive where RPCS3 is installed.

After the first startup, the game should launch normally.

**The patch does not replace or delete files in your original game folder.**

---

## 🎮 HOW TO USE THE MOD

| Feature | Controller / Instructions |
|---|---|
| Turn first-person mode ON/OFF | Press **SELECT** during a fight |
| Wipe blood from your right eye | Press **R3** |
| Wipe blood from your left eye | Press **L3** |
| Use your own boxer face | Main Menu → Create a Boxer → Photo Game Face |
| Increase physical damage | Game Settings → Physical Damage → Set to **10** |

---

## 🔥 FEATURES — VERSION 3.2

### First-Person Camera
Fight from your boxer's point of view, looking through your own eyes.

### Realistic Eye Swelling
Your vision gets darker around the edges of the damaged eye as swelling increases. It clears again as the swelling heals.

- Swelling matches the game's actual damage percentage.
- Effects appear on the correct eye and the correct area, such as the brow or cheek.
- Swelling can heal between rounds when your boxer is in the corner.

### Blood in Your Vision
When your boxer gets cut, blood can appear in your vision. Getting hit while cut can also produce blood splashes on the screen.

These blood effects are based on **your boxer's cuts**, not the opponent's.

### Additional Damage Effects
- Screen flashes when you get hit.
- Shadows from body shots.
- Stun effects.
- Damage effects during knockdown cameras.
- Clean replays without these screen effects.

### Glove Wiping
Use the controller sticks to wipe blood away from your eyes.

### Photo Game Face Without EA Servers
EA's online servers are offline, but you can still use your own photos with the included photo-face system.

### Slightly Faster Swelling
Eye swelling builds approximately **10% faster (×1.1)** for both boxers.

Cuts, healing, and stamina otherwise use the original game's behavior.

---

## 🧑 USE YOUR OWN FACE

You can use your own photos to create a boxer face.

### Required Files

Place two photos in:

`RPCS3\dev_hdd0\YSDV_FACE\`

Both files must use the same name:

- `NAME.jpg` — front-facing photo.
- `NAME_side.jpg` — side-profile photo.

Example:

- `carlos.jpg`
- `carlos_side.jpg`

### Photo Requirements

- **Size:** 512 × 512 pixels.
- **Format:** `.jpg` only. Do not use `.jpeg` or `.png`.
- **Maximum:** 4 faces in the folder.

To resize a photo, open it in Windows Paint, select **Resize**, choose **Pixels**, set the width and height to 512, and save it as a JPEG.

Move older faces into a separate subfolder if you need to make room for new ones.

For more information, read `YSDV_FACE\README.txt`.

---

## 🎥 OPTIONAL: CAMERA SETTINGS

You can adjust the first-person camera to better fit your preferences.

1. Copy `USRDIR\fnc_fp_settings.toml` from the downloaded ZIP.
2. Place it inside your game's `PS3_GAME\USRDIR\` folder.
3. Open the file using Notepad.
4. Adjust the settings explained inside the file, including field of view, eye position, and camera smoothing.
5. Save the file.
6. During a fight, press **SELECT twice** to turn first-person mode off and back on and apply the new settings.

---

## ⚠️ KNOWN BUGS — WORK IN PROGRESS

### Opponent Has No Head / Camera Inside Your Head
This can happen after a knockdown. The patch usually corrects itself.

**Quick fix:** Press **SELECT twice** to turn first-person mode off and back on.

### Boxer Model or Trunks May Shake
The boxer model or trunks may occasionally shake during gameplay.

### Platform Limitations
Currently, this version is for **RPCS3 on PC only**.

---

## 🔧 TROUBLESHOOTING

| Problem | Solution |
|---|---|
| First-person mode or effects do not work | Make sure the patch is enabled and game update **1.02** is installed. |
| First startup takes a long time | This is normal. The patch builds its files during the first startup. Allow approximately **420 MB** of free disk space. |
| Effects are missing or the screen edges look wrong | Enable **Write Color Buffers** in the GPU settings. |
| Photo face appears as a black box | Use a **512 × 512 `.jpg`** file saved with Paint. |
| Something goes wrong | Open **Manage → Game Patches** and untick the patch to disable it. |

---

More updates and improvements may follow as development continues.

---

## 📜 DISCLAIMER

This project requires your own legal copy of *Fight Night Champion*.

**This repository does not include the original game, game code, or game files.** You must obtain the game and its update separately.

*PROBLEMATIK_ONE_FP is a work in progress. Features, compatibility, and behavior may change as development continues.*

# ProForge OrcaSlicer Profiles — Installation

Profiles for the **ProForge 300**, **ProForge 4.2**, and **ProForge 5** toolchanger 3D printers.

---

## Step 1 — Copy the profile files

Download and extract the release zip, then copy the `Makertech/` folder and `Makertech.json` into the OrcaSlicer profiles directory for your platform:

| Platform | Path |
|---|---|
| Windows | `C:\Program Files\OrcaSlicer\resources\profiles\` |
| macOS | Right-click `OrcaSlicer.app` → Show Package Contents → `Contents/Resources/profiles/` |
| Linux | `~/.local/share/OrcaSlicer/resources/profiles/` |

> **First time installing OrcaSlicer?** Copy the profiles before launching OrcaSlicer for the first time — the setup wizard that runs on first launch will then include the ProForge printers in its printer list.

---

## Step 2 — Add a ProForge printer in OrcaSlicer

**New OrcaSlicer installation** — the setup wizard will appear on first launch. Select **Makertech** from the vendor list and choose your ProForge model.

**Existing OrcaSlicer installation** — click the printer name dropdown in the top-left of the main window, select **Add/Remove Printers**, then find **Makertech** in the vendor list and select your ProForge model.

---

## Troubleshooting

If Makertech doesn't appear in the printer list, confirm both `Makertech.json` and the `Makertech/` folder are present in the same `profiles/` directory, then restart OrcaSlicer.

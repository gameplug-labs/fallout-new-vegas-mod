# GamePlug Fallout New Vegas Upscaler Mod

Adds AMD FSR1 & FSR2 upscaling support to **Fallout: New Vegas Ultimate Edition** using the GamePlug D3D9 layer. Improves image clarity and performance scaling while preserving the original game experience.

Enhance Fallout: New Vegas Ultimate Edition with modern AMD FSR1 & FSR2 upscaling support through the GamePlug D3D9 layer. This mod injects an FSR1/2-based upscaler into the game, allowing improved image reconstruction and better performance scaling at lower rendering resolutions while maintaining visual quality.

---

## Compatibility

- **Compatible with:**
  - **DXVK** for Vulkan
  - **ReShade** (make sure to select **Vulkan** during ReShade setup)
- **Not Compatible with:**
  - **Afterburner / RivaTuner HUD**
  - **ENB** (by default)
    > [!TIP]
    > To make this mod compatible with **ENB**, rename our injector file (e.g. `dinput8.dll`) to `other_d3d9.dll`, edit your `enblocal.ini` file, and set `EnableProxyLibrary=true`.

---

## Features

- **AMD FSR1 & FSR2** upscaling support
- **Tailored for FNV:** Designed specifically for Fallout: New Vegas D3D9
- **Vulkan-based injection** via GamePlug framework
- **Lightweight** DLL-based mod
- **In-Game Toggle:** Toggle the menu overlay visibility using `Ctrl + HOME`
- **Configuration:** Fully controlled via the `upscaler.conf` file (requires game restart to apply changes)

---

## Downloads

*Optional: Download the required files for AMD FSR2 upscaling.*

- **FSR2 v2.2.1 files**: [FidelityFX FSR2 Releases](https://github.com/rohitsoni007/FidelityFX-FSR2/releases/tag/v2.2.1)
- **D3D9 Vulkan Upscaler Plugin (Core)**: [upscaler-plugin-d3d9-vulkan](https://github.com/gameplug-labs/upscaler-plugin-d3d9-vulkan)

---

## Installation

1. **Download the mod files.**
2. **Place the following files** into your Fallout: New Vegas game executable directory (where `FalloutNV.exe` is located):
   - `upscaler_vk.dll`
   - `upscaler.conf`
   - `dinput8.dll`
   - `vklayer.dll`
   - `VK_LAYER_GAMEPLUG.json`
   - `d3d9.dll` *(DXVK)*
   - **For FSR2 support (Required):**
     - `ffx_fsr2_api_x86.dll`
     - `ffx_fsr2_api_vk_x86.dll`
3. **Run the game.**

---

## Framework

Powered by [GamePlug](https://github.com/gameplug-labs).

Join the [GamePlug Discord](https://discord.gg/TyyDD3C7wQ) for announcements, news, and new features!

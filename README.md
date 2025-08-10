# MySplit ZMK Config (nice!nano v2)

## Quick start
1. Create a new repo and copy all files from this folder into it.
2. Push to GitHub. The **Build ZMK firmware** workflow will run and create two UF2 files:
   - `mysplit_right-nice_nano_v2.uf2` (central)
   - `mysplit_left-nice_nano_v2.uf2` (peripheral)
3. If your left-half pins differ, edit `boards/shields/mysplit/mysplit_left.overlay` and push again.
4. Customize `config/mysplit.keymap` when you're ready.

> Right half is set as CENTRAL by default via `Kconfig.defconfig`.

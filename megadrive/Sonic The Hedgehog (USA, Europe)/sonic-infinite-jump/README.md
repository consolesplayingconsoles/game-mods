# Sonic the Hedgehog (USA, Europe): Infinite Jump

A tiny bonus mod for the Mega Drive game *Sonic the Hedgehog*: tap jump in mid-air to relaunch, as many times as you like. A silly movement toy — everything else is stock Sonic 1.

## Download

Shipped in the **Bonus Mods** bundle (alongside Random Green Hill).

**Latest release:** [Sonic_The_Hedgehog_USA-EU_Bonus_Mods_v1.0](https://github.com/consolesplayingconsoles/game-mods/releases/tag/sonic-the-hedgehog-usa-eu-bonus-mods-v1.0)

Patch file: [`Sonic_The_Hedgehog_USA-EU_Infinite_Jump_v1.0.bps`](https://github.com/consolesplayingconsoles/game-mods/releases/download/sonic-the-hedgehog-usa-eu-bonus-mods-v1.0/Sonic_The_Hedgehog_USA-EU_Infinite_Jump_v1.0.bps)

Releases in this monorepo are namespaced per game, so the tag carries the game name (`sonic-the-hedgehog-usa-eu-...`), not just a version.

## Applying the patch

The patch is a **BPS**. It rebuilds the modded ROM from your own copy of the game, and BPS verifies your ROM automatically, so a wrong file is rejected rather than silently mispatched.

Easiest, in your browser (no install): [rom-patcher-js](https://www.marcrobledo.com/RomPatcher.js/). Desktop alternative: [Floating IPS (Flips)](https://www.romhacking.net/utilities/1040/).

You will need the original **Sonic the Hedgehog (USA, Europe)** ROM — the standard, widely-available retail dump (No-Intro), the same one romhacking.net hacks target:

- CRC32 *F9394E97*
- MD5 *1BC674BE034E43C96B86487AC69D9293*
- SHA-1 *6DDB7DE1E17E7F6CDB88927BD906352030DAA194*

This is the ordinary Sonic 1 ROM; you do **not** build or compile anything.

1. Open the patcher.
2. Select your Sonic 1 (Rev 1) ROM as the source.
3. Choose the `.bps` patch file above.
4. Apply, and save the output ROM.

Load the output in a Mega Drive emulator, or flash it to a cart — it runs on real hardware.

## Notes

Tap the jump button while airborne to jump again; there is no limit. That is the whole mod.

## Feedback

[Open an issue](https://github.com/consolesplayingconsoles/game-mods/issues/new) and mention that it is the Infinite Jump mod.

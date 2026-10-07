# Yu-Gi-Oh! Forbidden Memories — Android (unofficial)

Unofficial Android port of the fan-made PC recompilation of *Yu-Gi-Oh!
Forbidden Memories* (PS1). This repository only hosts the **README and
compiled APK releases** — it does not contain the game's source code or any
copyrighted game assets.

**Latest build and what's new: see the [Releases](../../releases) page.** Every
release lists what changed.

## What this is

- A native Android build (arm64) of the recompiled engine, with an on-screen
  gamepad and touch support for menus, name entry and the on-screen keyboard.
- **Not** a copy of the game. You need your own legally-owned copy of the
  original PS1 disc image to play — the app does not ship with one and
  cannot provide one.
- Built from a private source repository. The engine is a community
  decompilation project; keeping the source repo private while shipping
  public builds is a deliberate choice to manage the project's legal
  exposure, not an attempt to hide anything from players.

## Features

- **Modern turn rules.** Play several cards from your hand every turn, but only
  one Normal Summon (a monster alone or fused, face-up or face-down). Magic,
  Trap, Equip and Ritual cards don't use it, and Rituals can use materials from
  your hand *and* your field. The opponent plays by the same rules.
- **A much harder AI**, from the first duelist: it plans fusion chains, picks
  guardian stars, plans its attacks, uses removal and burn before it summons,
  and sees your face-down cards and its own upcoming cards.
- **Starchips and the Pack Shop.** Winning (or losing) pays starchips by rank
  instead of dropping cards, and you can raise the payout x1 to x5 in the shop
  (L1 / R1). Every duelist you beat unlocks his own box of 12 packs, with
  card-flip opening and rarities that follow each card's real drop chance.
  Press Triangle on a box to see every card in it.
- **Fusion helper.** Shows the best fusion in your hand, with numbered, colored
  badges for the order to pick the cards.
- **Optional HD textures**, offered as a one-time download when the app opens.
- 3D monsters, a hand camera and more, all built into the APK.

## Installation

1. Download the latest `.apk` from the [Releases](../../releases) page.
2. On your Android device, allow "install from unknown sources" for your
   browser or file manager (Android will prompt you the first time).
3. Install the APK and launch the app.
4. On first launch the app asks for your disc image: tap the button, pick the
   `.bin` (or a `.zip` that contains it) and the app copies it into its own
   storage. You don't need to touch the `Android/data` folder.
5. To **update**, install the new APK over the old one. You keep your saves.
   (The early test builds alpha.3 and alpha.4 were signed with a different key;
   if one of those is installed, uninstall it once first.)

## Requirements

- Android 8.0 or newer, arm64-v8a device.
- Your own PS1 disc image of Yu-Gi-Oh! Forbidden Memories (USA, SLUS-01411).
- Around 1 GB of free storage (the disc copy plus the optional HD textures).

## If the game crashes

The next time you open the app it offers to **send a report** (the phone model,
Android version, free memory and the game's error log — no personal data and no
game files) or to save it to your Downloads folder. Sending it gives you an id:
quote that id on Discord and it can be looked up. Please also say what you were
doing when it happened.

## Support & community

- Bug reports and feedback: open an [issue](../../issues) here, or join the
  [Discord](https://discord.gg/5MEQFuDgZW).
- Please include your device model and Android version with any bug report.

## Status

This is an actively developed hobby project. Expect bugs: the new turn rules and
the harder AI are recent and the campaign has not been re-balanced for them yet,
so tell us what feels unfair or broken. See the Releases page for a changelog
per version.

## Credits

Built on top of the community's PS1 decompilation and PC recompilation
effort for Yu-Gi-Oh! Forbidden Memories. This port adapts that work to run
natively on Android.

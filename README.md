# Corne Keyboard Configuration - Arch Linux + Hyprland

## Overview

3-layer Corne keyboard configuration optimized for Arch Linux and Hyprland window manager.

The configuration features:

- 3-layer design: Base + Symbols + Utilities
- Pinky modifier keys (Alt/Ctrl) with tap functionality
- Super key on right thumb for Hyprland integration
- Triple-tap Ctrl for utilities layer access
- No home row mods for cleaner typing experience
- Essential keyboard utilities (Bluetooth, USB toggle, reset)

## Keyboard Layout

The Corne is a 42-key split keyboard with the following physical layout:

```
┌───┬───┬───┬───┬───┬───┐   ┌───┬───┬───┬───┬───┬───┐
│   │   │   │   │   │   │   │   │   │   │   │   │   │
├───┼───┼───┼───┼───┼───┤   ├───┼───┼───┼───┼───┼───┤
│   │   │   │   │   │   │   │   │   │   │   │   │   │
├───┼───┼───┼───┼───┼───┤   ├───┼───┼───┼───┼───┼───┤
│   │   │   │   │   │   │   │   │   │   │   │   │   │
└───┴───┴───┼───┼───┼───┤   ├───┼───┼───┼───┴───┴───┘
            │   │   │   │   │   │   │   │
            └───┴───┴───┘   └───┴───┴───┘
```

## Layer 0: Base QWERTY Layer

The base layer uses QWERTY with dedicated modifier keys for ergonomic split keyboard use.

```
╭─────┬─────┬─────┬─────┬─────┬─────╮   ╭─────┬─────┬─────┬─────┬─────┬─────╮
│  `  │  Q  │  W  │  E  │  R  │  T  │   │  Y  │  U  │  I  │  O  │  P  │  #  │
├─────┼─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┼─────┤
│ ESC │  A  │  S  │  D  │  F  │  G  │   │  H  │  J  │  K  │  L  │  '  │  \  │
├─────┼─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┼─────┤
│TAB/ │  Z  │  X  │  C  │  V  │  B  │   │  N  │  M  │  ,  │  .  │  ;  │ //  │
│ALT  │     │     │     │     │     │   │     │     │     │     │     │CTRL │
╰─────┴─────┴─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┴─────┴─────╯
                  │ SYM │BKSP │SHFT │   │ENTR │SPCE │SUPER│
                  ╰─────┴─────┴─────╯   ╰─────┴─────┴─────╯
```

### Key Features:

- **Modifier Keys**:
  - Left Pinky: TAB (tap) / ALT (hold)
  - Right Pinky: / (tap) / CTRL (hold) / UTILITIES (triple-tap)
  - Right Thumb: SUPER key (Hyprland primary modifier)
- **Special behaviors**:
  - Smart Shift: Tap for sticky shift, double-tap for caps-word, hold for shift
  - Backspace/Delete: Tap for backspace, shift+tap for delete
  - Hash (#) tap dance: Single tap for #, double tap for ###
  - Triple-tap Ctrl: Access utilities layer for keyboard functions
- **Layer access**:
  - SY (Symbols) layer: Hold left thumb
  - UT (Utilities) layer: Triple-tap right pinky

## Layer 1: Symbols and Numbers Layer

This layer provides access to numbers and programming symbols, organized for efficient coding.

```
╭─────┬─────┬─────┬─────┬─────┬─────╮   ╭─────┬─────┬─────┬─────┬─────┬─────╮
│     │  1  │  2  │  3  │  4  │  5  │   │  6  │  7  │  8  │  9  │  0  │ DEL │
├─────┼─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┼─────┤
│     │  $  │  @  │  #  │  !  │  %  │   │  (  │  [  │  {  │  =  │  -  │     │
├─────┼─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┼─────┤
│     │  ^  │  |  │  *  │  ?  │  &  │   │  )  │  ]  │  }  │  +  │  _  │     │
╰─────┴─────┴─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┴─────┴─────╯
                  │     │     │     │   │     │     │     │
                  ╰─────┴─────┴─────╯   ╰─────┴─────┴─────╯
```

### Key Features:

- Numbers 1-0 on the top row
- Programming symbols organized by frequency
- Matching brackets/parentheses grouped together
- Mathematical operators easily accessible
- All essential symbols available without complex combos

## Layer 2: Utilities Layer

Essential keyboard functions accessed by triple-tapping the right pinky (Ctrl key).

```
╭─────┬─────┬─────┬─────┬─────┬─────╮   ╭─────┬─────┬─────┬─────┬─────┬─────╮
│USB/ │BT 0 │BT 1 │BT 2 │BT 3 │BT 4 │   │     │     │     │     │     │POWER│
│BT   │     │     │     │     │     │   │     │     │     │     │     │     │
├─────┼─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┼─────┤
│RESET│BT ← │BT → │BT CLR│    │     │   │     │     │     │     │     │RESET│
├─────┼─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┼─────┤
│     │     │     │     │     │     │   │     │     │     │     │     │     │
╰─────┴─────┴─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┴─────┴─────╯
                  │     │     │     │   │     │     │     │
                  ╰─────┴─────┴─────╯   ╰─────┴─────┴─────╯
```

### Key Features:

- **Bluetooth Management**:
  - BT 0-4: Select Bluetooth profile (supports 5 devices)
  - BT ←/→: Cycle between previous/next Bluetooth profiles
  - BT CLR: Clear all Bluetooth pairings
- **Output Control**:
  - USB/BT: Toggle between USB and Bluetooth output
- **System Functions**:
  - RESET: Reset keyboard (tap) / Enter bootloader (hold)
  - POWER: System power key

## Special Behaviors

### Pinky Modifiers

The configuration uses hold-tap behaviors on the pinky keys for ergonomic modifier access:

```
Left Pinky:  TAB (tap) / ALT (hold)
Right Pinky: / (tap) / CTRL (hold) / UTILITIES (triple-tap)
```

This provides easy access to essential modifiers while maintaining the ability to type frequently-used characters. The behavior is configured with:

- `tapping-term-ms = <280>`: Time to determine tap vs hold
- `quick-tap-ms = <175>`: Window for quick repeated taps
- `require-prior-idle-ms = <150>`: Required idle time before registering a hold

### Smart Shift

Smart shift provides three functionalities in one key:

- Tap: Sticky shift (next key is uppercase)
- Double-tap: Caps-word (typing in all caps until space/punctuation)
- Hold: Standard shift modifier

### Backspace/Delete

The backspace key supports two operations:

- Tap or hold: Backspace
- Shift+tap or Shift+hold: Delete

## Hyprland Integration

With the Super key easily accessible on the right thumb, all Hyprland window management becomes effortless:

- Super+Enter: Terminal
- Super+D: Application launcher (dmenu/rofi)
- Super+Q: Close window
- Super+F: Toggle fullscreen
- Super+Space: Toggle floating
- Super+1-9: Switch to workspace
- Super+Shift+1-9: Move window to workspace

## Hardware Configuration

- Nice!nano v2 with nice!view displays
- 30-minute sleep timeout for power efficiency
- Fast debouncing (1ms press, 7ms release) for responsive typing
- Bluetooth power boost for better connectivity
- Battery level reporting for split keyboard halves

## Build Instructions

```bash
# Build firmware using Docker
./build-firmware.sh

# Or build in Docker manually
./build-in-docker.sh

# Check firmware after build
./check-firmware.sh
```

## Changes Made

1. **3-layer design**: Base + Symbols + Utilities
2. **Eliminated home row mods**: Replaced with dedicated pinky modifiers  
3. **Added Super key**: Right thumb for Hyprland window management
4. **Triple-tap utilities**: Right pinky accesses keyboard functions
5. **Fixed pinky placement**: Right Ctrl/Slash on far-right corner key
6. **Essential utilities only**: Bluetooth, USB toggle, reset functions
7. **Linux optimization**: Focused on Arch Linux + Hyprland workflow

This configuration provides a clean, efficient typing experience with easy access to modifiers, symbols, and essential keyboard utilities.

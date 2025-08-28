# Corne Keyboard Configuration - Arch Linux + Hyprland

## Overview

4-layer Corne keyboard configuration optimized for Arch Linux and Hyprland window manager.

The configuration features:

- 4-layer design: Base + Symbols + Utilities + Navigation
- Pinky modifier keys (Alt/Ctrl) with tap functionality
- Super key on right thumb for Hyprland integration
- ESC hold for navigation layer (function keys & arrows)
- Triple-tap Ctrl for utilities layer access
- No home row mods for cleaner typing experience
- Full F1-F12 function key access
- Vim-style arrow keys (HJKL)
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
│  `  │  Q  │  W  │  E  │  R  │  T  │   │  Y  │  U  │  I  │  O  │  P  │ ##  │
├─────┼─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┼─────┤
│ESC/ │  A  │  S  │  D  │  F  │  G  │   │  H  │  J  │  K  │  L  │  '  │  \  │
│NAV  │     │     │     │     │     │   │     │     │     │     │     │     │
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
  - ESC/Navigation: Tap for ESC, hold for navigation layer
  - Smart Shift: Tap for sticky shift, double-tap for caps-word, hold for shift
  - Backspace/Delete: Tap for backspace, shift+tap for delete
  - Hash (#) tap dance: Single tap for #, double tap for ###
  - Triple-tap Ctrl: Access utilities layer for keyboard functions
- **Layer access**:
  - SY (Symbols) layer: Hold left thumb
  - UT (Utilities) layer: Triple-tap right pinky
  - NAV (Navigation) layer: Hold ESC key

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

## Layer 3: Navigation Layer

Complete navigation and function key access, activated by holding the ESC key.

```
╭─────┬─────┬─────┬─────┬─────┬─────╮   ╭─────┬─────┬─────┬─────┬─────┬─────╮
│  ~  │ F1  │ F2  │ F3  │ F4  │ F5  │   │ F6  │ F7  │ F8  │ F9  │ F10 │ DEL │
├─────┼─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┼─────┤
│ ESC │ F11 │ F12 │ INS │HOME │PGUP │   │  ←  │  ↓  │  ↑  │  →  │ END │     │
├─────┼─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┼─────┤
│     │VOL- │VOL+ │MUTE │PLAY │PGDN │   │PREV │NEXT │BRI- │BRI+ │     │     │
╰─────┴─────┴─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┴─────┴─────╯
                  │     │     │     │   │     │     │     │
                  ╰─────┴─────┴─────╯   ╰─────┴─────┴─────╯
```

### Key Features:

- **Function Keys**: Complete F1-F12 access on top two rows
- **Arrow Navigation**: Vim-style HJKL arrows (H=←, J=↓, K=↑, L=→)
- **Navigation Keys**: Home, End, Page Up/Down, Insert, Delete
- **Media Controls**: 
  - Volume: Vol-, Vol+, Mute
  - Playback: Play/Pause, Previous, Next track
  - Display: Brightness up/down
- **Layer Access**: Hold ESC key (~280ms) to activate

### Navigation Layer Usage:
- **Hold ESC** to access navigation layer
- **HJKL** become arrow keys (Vim-style navigation)
- **F1-F12** available on top two rows for system functions
- **Media controls** for volume, playback, and brightness
- **Document navigation** with Home/End/PageUp/PageDown

## Special Behaviors

### ESC Navigation Access

The ESC key uses hold-tap behavior to provide navigation layer access:

```
ESC Key: ESC (tap) / NAV Layer (hold)
```

This provides immediate access to function keys and arrows without sacrificing the frequently-used ESC key. The behavior is configured with:

- `tapping-term-ms = <280>`: Time to determine tap vs hold
- `quick-tap-ms = <175>`: Window for quick repeated taps  
- `require-prior-idle-ms = <150>`: Required idle time before registering a hold
- `flavor = "tap-preferred"`: Favors tap when timing is ambiguous

### Pinky Modifiers

The configuration uses hold-tap behaviors on the pinky keys for ergonomic modifier access:

```
Left Pinky:  TAB (tap) / ALT (hold)
Right Pinky: / (tap) / CTRL (hold) / UTILITIES (triple-tap)
```

This provides easy access to essential modifiers while maintaining the ability to type frequently-used characters. The behavior is configured with the same timing parameters as the ESC key.

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

## Troubleshooting

### Split Keyboard Issues

#### Right Side Not Working
**Symptoms**: Left side works perfectly, right side completely unresponsive, Bluetooth shows connected.

**Most Common Cause**: **Corrupted Nice!Nano flash storage**

**Solution**:
1. **Check flash storage health**:
   ```bash
   # When Nice!Nano is in bootloader mode
   df -h /mnt/nicenano
   # Look for "No space left on device" or I/O errors
   ```

2. **Complete flash erase and restore**:
   ```bash
   # Put right side in bootloader mode (double-tap reset)
   sudo umount /mnt/nicenano  # if already mounted
   
   # Clear all files from corrupted flash
   sudo rm -rf /mnt/nicenano/*
   
   # Flash settings reset first (clears all flash)
   sudo cp firmware/LATEST-settings_reset-nice_nano_v2.uf2 /mnt/nicenano/
   sync && sudo umount /mnt/nicenano
   
   # Wait 10 seconds, then put back in bootloader mode
   # Flash right side firmware
   sudo cp firmware/LATEST-corne_right-nice_view-nice_nano_v2.uf2 /mnt/nicenano/
   sync && sudo umount /mnt/nicenano
   ```

#### Hardware Connection Issues
**Symptoms**: Split keyboard halves not communicating, keys not registering.

**Solutions**:
1. **TRRS Cable Issues** (80% of split problems):
   - Try different TRRS cable
   - Ensure cable is firmly seated in both halves
   - Check for damaged cable ends or debris in jacks

2. **Bluetooth Reset**:
   - Flash settings_reset firmware to both halves
   - Re-flash main firmware after settings reset
   - Wait 60 seconds for auto-pairing

3. **Battery/Power Issues**:
   - Check battery connections on both halves  
   - Test with USB power (keep USB plugged in)
   - Look for power LEDs on Nice!Nano boards

#### Single Column Dead
**Symptoms**: One vertical column of keys not working on either side.

**Cause**: Hardware matrix issue - loose wire, bad diode, or switch problem.

**Solutions**:
1. **Physical inspection**: Check for loose connections
2. **Firmware test**: Try different layer (symbols/utilities) on same keys
3. **Hardware repair**: May require resoldering matrix connections

### Firmware Build Issues

#### Oversized Firmware
**Symptoms**: Firmware size >200KB, split keyboard issues.

**Cause**: Multiple keymap definitions or corrupted build cache.

**Solutions**:
```bash
# Clean build cache
rm -rf build/*

# Rebuild firmware
./build-firmware.sh

# Check normal firmware sizes:
# Left side: ~350KB (with nice!view)
# Right side: ~350KB (with nice!view)  
# Settings reset: ~46KB
```

### Layer Access Issues

#### Navigation Layer Not Working
**Symptoms**: ESC tap works, but hold doesn't activate navigation layer.

**Solutions**:
1. **Check hold timing**: ESC must be held for ~280ms
2. **Verify layer definition**: Ensure NAV layer (3) is properly defined
3. **Test other layers**: Confirm symbols layer works (left thumb hold)

#### Function Keys Not Working  
**Symptoms**: Navigation layer activates but F1-F12 don't work.

**Check**: Ensure you're in navigation layer when pressing F-keys (hold ESC + F1)

### Bluetooth Connectivity

#### Pairing Issues
**Symptoms**: Keyboard not connecting to computer, frequent disconnections.

**Solutions**:
1. **Clear computer Bluetooth cache**:
   ```bash
   # Linux
   sudo systemctl restart bluetooth
   
   # Clear specific device
   bluetoothctl remove XX:XX:XX:XX:XX:XX
   ```

2. **Reset keyboard Bluetooth**:
   - Use utilities layer (triple-tap right pinky)
   - Press BT CLR to clear all pairings
   - Try different BT profile (BT 0-4)

3. **Boost signal strength**: Already enabled in config (BT_CTLR_TX_PWR_PLUS_8)

## Changes Made

1. **4-layer design**: Base + Symbols + Utilities + Navigation
2. **Eliminated home row mods**: Replaced with dedicated pinky modifiers  
3. **Added Super key**: Right thumb for Hyprland window management
4. **ESC navigation layer**: Hold ESC for function keys and arrows
5. **Vim-style navigation**: HJKL arrows in navigation layer
6. **Complete function key access**: F1-F12 available via ESC hold
7. **Triple-tap utilities**: Right pinky accesses keyboard functions
8. **Fixed pinky placement**: Right Ctrl/Slash on far-right corner key
9. **Essential utilities only**: Bluetooth, USB toggle, reset functions
10. **Linux optimization**: Focused on Arch Linux + Hyprland workflow

This configuration provides a clean, efficient typing experience with easy access to modifiers, symbols, navigation, function keys, and essential keyboard utilities.

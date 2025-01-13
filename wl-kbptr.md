--w: 13/01/2025 07:36 PM Mon GMT+6 Sharifpur, Gazipur, Dhaka

# Cursor Submap Documentation

## Activation Keys

```
$mainMod + m         - Enter cursor submap mode
$mainMod + comma     - Enter cursor mode and activate keyboard pointer
, (comma)           - Exit cursor mode and reset settings
```

## Movement Controls

### Vertical Movement

```
j       - Move down (15px)
m       - Move down (30px)
return  - Move down (160px)
k       - Move up (10px)
i       - Move up (30px)
u       - Move up (160px)
```

### Horizontal Movement

```
l           - Move right (10px)
w           - Move right (30px)
q           - Move right (160px)
h           - Move left (15px)
b           - Move left (30px)
SHIFT + b   - Move left (230px)
v           - Move left (160px)
```

## Mouse Actions

### Button Controls

```
a - Left click
r - Middle click
s - Right click
```

### Scrolling

```
d - Scroll right (10px)
e - Scroll left (10px)
t - Scroll up (10px)
g - Scroll down (10px)
```

## Special Functions

```
f - Jump cursor to position and reset submap
, - Exit cursor submap and restore default cursor behavior
```

## Notes

- All movement commands are bound with `binde` for continuous movement while key is held
- Pixel values indicate movement distance per keypress
- Cursor timeout and hide settings are automatically managed when entering/exiting the submap

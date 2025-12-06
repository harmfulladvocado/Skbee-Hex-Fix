# Hex SkBee Fix Function

[SpigotMC Resource Page](https://www.spigotmc.org/resources/hex-skbee-fix-function.129482/)

---

## What is this?

This function fixes how SkBee handles hex color codes.  
Base Skript can't use hex like `<#FF0000>` — SkBee uses `#FF0000` instead.  
Now you can use hex prefixes and colors directly in Skript.

---

## Dependencies

- **Skript**
- **SkBee**

---

## How to Use

```skript
send hex("#FF0000 welcome to the server") to player
send hex(player's prefix) to player

# Generic:
hex("<your text>")
```

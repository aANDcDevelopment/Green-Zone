# Green Zones Script

## Description
The **Green Zones Script** is a custom script for ESX-based FiveM servers that restricts specific actions, such as shooting and driving, in designated areas to promote safe and immersive roleplay. It integrates seamlessly with ESX and QBcore frameworks and is fully customizable to suit your server's needs.

---

## Features
- Prevents weapon usage and driving in defined zones.
- Configurable zones with adjustable coordinates and radius.
- Customizable notifications and warnings.
- Lightweight and optimized for performance.

---

## Installation

1. **Download and Extract:**
   - Download the script files and extract them to your `resources` folder.

2. **Add to Server.cfg:**
   - Add the following line to your `server.cfg` file:
     ```
     ensure green_zones
     ```

3. **Configure Zones:**
   - Open the `config.lua` file and define the zones by setting coordinates, radius, and other parameters.
   
4. **Restart Server:**
   - Restart your server to load the script.

---

## Configuration

The `config.lua` file allows full customization. You can define multiple zones by adding entries like this:

```lua
Config.GreenZones = {
    {x = 123.45, y = 678.90, z = 21.34, radius = 50.0},
    {x = 321.45, y = 987.65, z = 25.67, radius = 75.0},
}
```

### Options:
- **Coordinates (x, y, z):** Center point of the green zone.
- **Radius:** The size of the zone.
- **Custom Actions:** Enable or disable specific restrictions (e.g., weapon use, vehicle entry).

---

## Troubleshooting

- **Zone Not Working:**
  - Ensure the coordinates and radius are set correctly in `config.lua`.
  - Verify the script is listed in `server.cfg` and loaded properly.

- **Performance Issues:**
  - Check server logs for errors and ensure the script is up-to-date.

---

## Credits
Created by Bailey Andrew for a custom ESX-based FiveM server.

---

## License
This script is for personal or server use only. Redistribution or resale is not allowed without prior permission.

---

Enjoy safe and immersive roleplay with the Green Zones Script!

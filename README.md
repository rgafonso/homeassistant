# Smart Lights Blueprint 🏠

## Install

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://github.com/rgafonso/homeassistant/blob/main/smart-lights.yaml)

**Or import manually:**
1. Copy the URL of the `smart-lights.yaml` file.
2. Go to **Home Assistant > Settings > Automations & Scenes > Blueprints**.
3. Click **Import Blueprint** and paste the URL.

## Description

This is a Home Assistant blueprint that automates lights based on motion, but smartly restricted by **Sun Position** (Sunset/Sunrise) and/or **Lux Levels**.

## Features
- ☀️ **Sun Based:** Only runs between sunset and sunrise (with offsets).
- ☁️ **Lux Override:** Optional override to run during the day if it's dark (e.g., storm).
- 💡 **Light Control:** Can force specific brightness and color temperature.
- ⏱️ **Auto-Off:** Turns off after a configurable duration of no motion.



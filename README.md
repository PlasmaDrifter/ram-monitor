# RAM Monitor

A KDE Plasma panel widget displaying real-time RAM and swap/zram usage as horizontal bars.

## Features

- RAM usage bar (used / total)
- Swap / zram usage bar
- Configurable bar colours for each metric
- Numeric label showing current usage
- Compact horizontal layout

## Requirements

- KDE Plasma 6.0+
- `org.kde.ksysguard.sensors` (included with Plasma)

## Installation

```bash
cd ~/.local/share/plasma/plasmoids/
git clone https://github.com/PlasmaDrifter/ram-monitor local.widget.ram-monitor
```

Then right-click your panel → **Add Widgets** → search for **RAM Monitor**.

## Configuration

Right-click the widget → **Configure…**

| Option | Description |
|--------|-------------|
| RAM bar colour | Fill colour for the RAM usage bar |
| Swap bar colour | Fill colour for the swap/zram usage bar |
| Refresh interval | Update frequency (seconds) |


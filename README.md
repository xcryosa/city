# City Journey: 3D

**A browser-based 3D city-building game.** Develop a city, place buildings and roads, and manage its infrastructure through a compact browser interface.

## Features

- 3D city scene powered by Three.js.
- Place buildings and roads to shape your city.
- City simulation with infrastructure and management systems.
- Vehicles and pedestrians moving through the city.
- Simulation pause and speed controls.
- Settings for the interface, camera, and visual options.
- Local save slots stored in your browser.
- Single-file project: HTML, CSS, and JavaScript are contained in one HTML file.

> This is an ongoing indie game project. Features and balance may change during development.

## Getting Started

### Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Start a city and begin building.

The game loads Three.js and fonts from external CDNs, so an internet connection is required for those resources.

### Publish with GitHub Pages

1. Put the game file in the root of your repository.
2. Rename it to `index.html`.
3. Open **Settings → Pages** in your GitHub repository.
4. Select the branch you want to publish and choose the root (`/`) folder.
5. Save the settings and wait for GitHub Pages to publish the site.

## Controls

| Key / Input | Action |
| --- | --- |
| `Space` | Pause or resume the simulation |
| `Esc` | Open the menu or cancel the current action |
| `X` | Select the demolition tool |
| `Tab` | Cycle through building categories |
| `1`–`9` | Select a building in the current category |
| Mouse wheel | Zoom the camera |
| Mouse / touch | Interact with the game interface and scene |

Camera movement and placement interactions may depend on the selected tool and current game mode. Check the in-game hints for the current controls.

## Technology

- HTML5
- CSS3
- JavaScript
- [Three.js](https://threejs.org/)
- Browser `localStorage` for local saves and settings
## License

No license has been added yet. Until a license is specified in this repository, assume that reuse, redistribution, and modification require the author's permission.

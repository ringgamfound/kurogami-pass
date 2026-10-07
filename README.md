# Kurogami Pass

An early browser prototype from **RingGam Studio**.

Kurogami Pass is a night-driving prototype set on a 3 km mountain descent through cedar forest. Navigate eight hairpins, including five in succession, manage a manual gearbox, and switch between cockpit and chase cameras. Complete the descent and try to beat your local best time.

## Play

Play the prototype: https://ringgam-studio.upbeat-lime-9149.chatgpt.site/games/kurogami-pass/

Studio domain: https://ringgam.com (DNS connection pending).

Run locally with Python 3:

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000/ in a desktop browser with a mouse and keyboard. JavaScript is required. WebGL is required.

## What is in this build

- A 3 km downhill mountain road with eight hairpins
- Manual shifting through reverse, neutral, and gears 1–5
- Cockpit and chase cameras
- Timed runs and a local best time

## Controls

| Input | Action |
| --- | --- |
| W / S | Throttle / brake |
| A / D | Steer |
| P or Space | Handbrake |
| E / Q | Shift up / down |
| F | Switch cockpit / chase camera |
| R | Return the car to the road |
| Enter | Restart the run |
| M / H / Esc | Sound / help / pause |

The car starts in neutral. Press E to shift into first gear before accelerating.

## Development status

Experimental prototype, shared as part of RingGam's early game development. The supplied HTML build was developed with an AI-assisted workflow including Claude. This repository publishes that build; it is not a claim that a commercial release or online service is available.

The games use browser-local storage for settings, saves, or records. Hosted web fonts may require an internet connection; fallback fonts are provided by the original build.

## Credits and permissions

RingGam Studio. Contact: founder1@ringgam.com.

No open-source license is granted for RingGam's original game code or artwork by this publication. Third-party software retains its own license; see `THIRD_PARTY_NOTICES.txt`.

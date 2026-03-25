# DC / BLDC Hub Motor Performance Calculator — Web Edition

Live: **https://shhubham-r.github.io/hub-motor-calculator**

A browser-based port of [Motor_calculator.py](https://github.com/Shhubham-R/-DC-hub-motor-Performance-Calculator) by [Shhubham-R](https://github.com/Shhubham-R).

Same physics engine, same results — no Python installation required.

## Features

- Full port of the original Python physics engine (Faraday's law, Steinmetz core loss, lumped thermal model)
- All defaults match the original — just press Calculate
- Material explanation badges for core type selection
- Visual efficiency bar + colour-coded thermal warnings
- Ampacity check against AWG chassis ratings
- Mobile-friendly, works fully offline after first load

## Tech

Single `index.html` — no build step, no dependencies, no framework.

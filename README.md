# 🦤🚲 Pelican Rides · 鹈鹕骑行

A fully procedural, real-time 3D scene of a pelican riding a bicycle along an endless coastal road.
Single self-contained `index.html`, Three.js r170 via import map, no build step.

**Live:** https://huangjiexin.github.io/pelican-rides/
**CDN mirror:** https://cdn.jsdelivr.net/gh/huangjiexin/pelican-rides@main/index.html

## What's inside
- Procedural pelican (pouch, helmet, tail/primaries) and bicycle (frame, spokes, fenders, chain on a spline, crank)
- Two-bone IK legs that follow the pedals; steering & lean on lane change; hop + wing flap
- Verlet-rope scarf, instanced feather particles, jumping fish with splash rings
- Custom GLSL sky (sun/moon glow, stars) and Gerstner-style ocean (fresnel, specular, foam)
- Full day/night cycle driving palette, fog, exposure, headlamp / tail light / lighthouse beam / buoy lamps
- Bloom post-processing (HDR half-float, MSAA), ACES tone-mapping, soft shadows
- WebAudio synthesized bell, ocean ambience, wheel hum
- 6 cameras (follow / side / front / cockpit / drone / free orbit), lil-gui panel, touch controls, PNG screenshot

## URL params
`?t=21.5` time of day (0–24) · `&day=0` freeze clock · `&cam=side|front|cockpit|drone|orbit` · `&speed=10` (m/s) · `&bloom=0`

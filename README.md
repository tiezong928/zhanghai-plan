# zhanghai-plan

Static Mneme/章亥 hub 179 3D demo (江南交通换乘枢纽 → 轨道长生桥 → 茶涪路, including segment 2 长生桥→茶涪路). No build step.

GitHub Pages (default branch `/`):

- https://tiezong928.github.io/zhanghai-plan/
- https://tiezong928.github.io/zhanghai-plan/hub_179_3d.html
- Peak berth rates (早高峰): https://tiezong928.github.io/zhanghai-plan/hub_179_3d.html?clock=08:00
- Optional rest-day band: add `?day=rest` (for example `?clock=08:00&day=rest`)

`?clock=HH:MM` sets the simulation clock (default 09:30, off-peak). `08:00` is the morning peak and uses the higher other-line berth arrival rate. `?day=rest` is optional and selects the 休息日 band instead of the clock-derived band.

`hub_179_seg2_data.js` includes `SEG2.osm_roads` (OpenStreetMap, 2026-11-08). Background buildings stay off those roads and off the segment-2 corridor.

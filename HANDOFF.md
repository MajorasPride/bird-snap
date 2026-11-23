# Bird Snap — handoff

Owner: MajorasPride. Tracker ID: P042.
Full plan, rules, add-ons and dev notes: https://claude.ai/artifact/UcSSzxWZ9UvpfJKfTGxgVv (private)

## What it is
A friendly 3D Pokémon Snap-style game that teaches photography and bird watching
(Merlin-style: hear the call, name the bird, then photograph it). 5 levels:
Park, Wetland, Rainforest, Coast, Mountain.

## Status (Nov 23, 2026)
Phase 3 prototype v0.2: `index.html`, Level 1 (Park), 3D on rails, three.js r128 (MIT, cdnjs).
Approved as the base. Not live anywhere.
Private preview: https://claude.ai/artifact/DSsBZV4DKdmNdG9ihCNYcv

## v0.3 preview (this branch, Nov 23, 2026)
Phase 4 teaching layer, built as a separate preview until he has checked it:
https://claude.ai/artifact/A7n5AaFQ5S8tPmaviGBykZ (private)
- Photo School: 4 lessons, each passed by taking a real photo: Framing, Timing, Light, Focus.
  Each lesson card has a two-picture sketch (the mistake, the fix), a Why and a Do this.
- Light: a visible sun; birds seen against the sun turn dark; Light chip; Light is 10 of the 100 points.
- Focus unlock (after the Light lesson or level complete): Auto/Manual button. In Manual, tap the
  bird (PC: F) to set the focus distance; right focus gives a soft background and +5.
- Score split is now Size 25, Framing 20, Pose 20, Sharpness 15, Light 10, Named it 10 (+5 Focus, capped at 100).
- Save key birdsnap_v03 (reads v02 progress once).
- Tested headless at phone and PC sizes; not yet on a real phone.

## v0.4 preview (this branch, Nov 23, 2026)
His note on v0.3: fine as a quick, fun Easy mode (keep the point-and-shoot), but he wants to change
settings like a real shoot. So v0.4 has two modes, picked on the start screen (tap the birds chip to switch):
- Easy: v0.3 exactly as it was.
- Real Shoot: shutter speed, aperture, ISO and manual focus, unlocked one at a time through four
  camera lessons. Light meter in stops, the view brightens/darkens with the exposure, slow shutter
  smears moving birds, wide aperture softens the background, high ISO adds grain. Locked settings run on auto.
- Park holds all four camera lessons for now; when the other levels exist, spread them out (one per level).
- Cart speed: he said the ride is fast but OK for now (add-on: speed setting).

## Next step
His playtest notes, then Phase 4: teaching layer (framing, focus, light, timing taught by
doing) and the Focus camera unlock.

## Waiting on him
5 real bird photos (public domain or his own), rails only or free walk too, cart speed,
who the Guide is.

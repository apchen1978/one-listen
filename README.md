# One Listen

A song you can hear exactly once.

## The experiment

The first four Garage experiments revealed something that already existed. This one creates a condition that did not exist before: it installs scarcity.

The moment is not the music. It is the hesitation before pressing Play, when the visitor knows replay will not be available.

## How the one-shot works

- Web Audio generates a 28-second piece in the browser from a per-visitor seed. Nothing is recorded or streamed.
- `localStorage` records that the listen was spent, so reloading shows the spent state.
- The listen is not spent if the browser cannot start audio.
- `prefers-reduced-motion` is respected: the thread advances without the wave.

## Limitation

The one-listen constraint is browser-local. Clearing site data resets it. It is not DRM, not secure scarcity, and not cross-device enforcement.

## Boundary

Synthetic experiment. No real composition, artist, or recording is involved. No claim is made about attention, memory, willingness to pay, or demand. It tests a possibility, not a behaviour.

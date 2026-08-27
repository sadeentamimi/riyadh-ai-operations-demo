# Camera footage

Camera panels render a synthesised scene by default, with the computer-vision
overlay derived from the real projected geometry of the actors in it.

To play real footage instead, drop a file here and point the camera at it with
`videoSrc` in the site data. The overlay engine is unchanged — it draws on top
of the video.

Currently referenced:

| File              | Camera | Used by                                    |
| ----------------- | ------ | ------------------------------------------ |
| `parking-b2.mp4`  | ST-01  | Al Nakhla Stadium — underground parking     |

`parking-b2.mp4` is **not included**: it needs to be a real underground car
park clip, and it has to be one you hold the rights to show at the event.
Suggested spec:

- 1920 × 1080, H.264, 15–30 s, seamless loop, no audio
- Fixed mount, looking down a drive aisle with bays on both sides
- Some vehicle and pedestrian movement so the detections have something to track

Until the file is present the panel falls back to the synthesised parking
scene automatically — nothing breaks and no black panel appears.

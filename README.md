# Pocket Karaoke

Turn your phone into a karaoke mic for any Bluetooth speaker. Sing into the phone, play a song along with it, and add effects to your voice.

**Try it:** https://ari070499.github.io/pocket-karaoke/

## Features
- **Go live:** your phone's mic plays through the connected speaker
- **Sensitivity meter:** live level meter with a noise gate so room noise stays out
- **Voice effects:** Reverb, Echo, Bass, Bright, each with its own amount slider
- **Song player:** load an MP3 or M4A from your phone and sing along
- **Vocal cut:** removes the original singer on many studio tracks
- **Mix:** separate voice and music volume

## How to use
1. Connect your phone to a Bluetooth speaker.
2. Open the link above. On iPhone, tap Share > Add to Home Screen to use it like an app.
3. Tap **Go live** and allow microphone access.
4. Tap **Pick a song** and choose an audio file saved on your phone.
5. Keep the phone a few steps away from the speaker to avoid feedback.

## Known limits
- Bluetooth adds about 150 to 250 ms of delay, so you hear your own voice slightly late. The music and your voice stay in sync for listeners.
- Songs from Spotify, Apple Music and similar apps can't be loaded. Use audio files saved on the device.
- Vocal cut doesn't work on mono tracks or songs where the vocal isn't centered.

## Tech
A single HTML file using the Web Audio API. No build step, no server. Hosted on GitHub Pages.

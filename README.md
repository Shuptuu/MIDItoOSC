# MIDItoOSC

**MIDItoOSC** is a plugin (VSTi / AU) that adds OSC support to your favorite DAW. \
It converts incoming MIDI messages into outgoing OSC messages. \
Mapping rules, network connection, and native mapping — all saved with your DAW project. \
So you can now send OSC messages without needing an extra bridge application or Ableton Live's Max for Live. \
Tested with Ableton Live and Cubase. But it should work on any DAW supporting VST3 or AU plugins. \
Available for Windows macOS and Linux

## Features
- a full rule editor (MIDI message, OSC address, value scaling)
- a **Learn** mode to capture a MIDI message directly from the source
- **native mapping** shortcuts for common cases (Note On/Off, CC, Pitch Bend, Program Change) without creating a rule
- up to 128 custom rules
- **Flexible network setup**: configurable UDP port, local or remote IP sending
- Available as **AU, VST3, and Standalone**, on **macOS, Windows, and Linux**

## Licensing

MIDItoOSC runs as a **Donationware**: \
Unfortunately, I’m not able to work for free anymore...  \
So MIDItoOSC comes in a demo version, fully functional but pausing every 20 minutes with a pop-up asking for a donation through PayPal. Closing the pop-up reactivates the plugin until the next pause.  \
I'm asking for a minimum of 15EUR.  \
If paypal doesn't support donations through this system in your country, you can use this link: https://www.paypal.com/paypalme/DesignedByOM  \
Once done, you will receive a license key that will stop the pop-up from appearing in future.  \
The license key is personal but with a permanent validity and can be use on several computers.  \
I'll need your email address to send you the key, so please make sure it's visible in your PayPal profile, or send me a private message.

## Installation

Download the latest release from the [Releases](../../releases) page, using the archive matching your platform and copy the plugin version you want to this location:

| Platform | Format | Location |
|---|---|---|
| macOS | AU | `~/Library/Audio/Plug-Ins/Components/` |
| macOS | VST3 | `~/Library/Audio/Plug-Ins/VST3/` |
| macOS | Standalone | `MIDItoOSC.app`, anywhere you like |
| Linux | VST3 | `~/.vst3/` |
| Linux | Standalone | `MIDItoOSC` executable (remember `chmod +x`) |
| Windows | VST3 | `C:\Program Files\Common Files\VST3\` |
| Windows | Standalone | `MIDItoOSC.exe`, anywhere you like |

Each archive includes a README with these same instructions, along with a `checksums.txt` file to verify the download's integrity.

## Credits

Developed by **Designed by OM**.

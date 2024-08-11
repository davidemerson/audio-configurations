# Making Your Speakers Sing using Bass Management, PEQ, and Dirac on MiniDSP SHD.

I made this repo, and I'm making it public, because configuring speakers is not something I do all that regularly. Once I get the things set up properly, it's small tweaks, never massive changes.

That said, every now and then, you need to start from scratch or something, and you've almost certainly forgotten how to do all this crap by the time you look at it again.

Done right, this procedure will make any sound system better, and it will make a good sound system truly sublime.

## What I'm working with

This procedure can work with anything, basically, but here's what I'm working with, for context. Adapt the notes here according to your own system.

- Speakers: (2) Meridian DSP5200SL
- Speaker Controller: Meridian G61RSL
- Subwoofers: (2) SVS SB3000
- DSP Preamp: miniDSP SHD
- Measurement Mic: UMIK-1 from miniDSP

This is a 2.2 stereo system, with two main speakers and two subwoofers.

My speakers are connected via RJ-45 (Speakerlink) to the speaker controller. The primary reason I even have this device in-line at all is configurability. There are some settings on Meridian speakers which are only configurable if you have a Meridian controller and set it up via serial interface.

The speaker controller is connected to digital channels 1 & 2 on the miniDSP, and passes these channels directly through to the speakers. The subwoofers are connected to analog channels 3 & 4 on the miniDSP.

Essentially,

- Left Speaker - miniDSP Channel 1 (digital)
- Right Speaker - miniDSP Channel 2 (digital)
- Left Subwoofer - miniDSP Channel 3 (analog)
- Right Subwoofer - miniDSP Channel 4 (analog)

## What we're going to do

It's easy to miss the forest for the trees doing this. The goals here are as follows, in order -

1. We'll set levels and time-alignment on the gear.
2. We'll measure bass response in our room.
3. We'll integrate the subwoofers with the speakers at an appropriate crossover point.
4. We'll develop a two-channel DIRAC filter on the integrated system to do a final room correction and equalization.

## Levels and Time Alignment

## Bass Measurements
https://www.minidsp.com/applications/subwoofer-tuning/dual-sub-with-mso

## Sub-Speaker Integration

## DIRAC Filter Development
https://www.minidsp.com/applications/subwoofer-tuning/sub-integration-dirac
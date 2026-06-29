# Field Recording Tools for Ableton Live

Three small Ableton Live extensions for working with field recordings: slicing, exporting, and splitting multichannel files. Written in JavaScript using the Ableton extension SDK.

Free to use and share.

## The tools

### 1\. Transient Sample Slicer

Chops a long recording into small samples using the transients as the cut points. For turning raw field recordings into percussion and one-shots without cutting clip by clip.

`Right-click a recording → Extensions → Transient Sample Slicer → set amount and length → Slice`

### 2\. Batch Exporter

Exports individual clips instead of whole channels. Drops every clip on a channel into your project folder as separate files.

`Select the channel → Batch Export → files land in your project folder`

### 3\. Poly Wav Splitter

Splits multichannel (poly) wav files into separate channels inside Ableton — e.g. recordings from a MixPre-6 with several mics at once, which Ableton can't open natively.

`Right-click an audio channel → Poly Wav Splitter → choose your file → Split`

## Install

These extensions only run on the **Ableton Live 12 beta** (12.4.5b3 or newer). The beta is a separate install from your normal Live version.

1. Install the Ableton Live 12 beta.  
2. In Live's Settings, enable extensions — or turn on Developer Mode to test extensions before installing.  
3. Install the three extension files, then restart Live.  
4. Right-click a clip or an audio channel and pick the tool from the Extensions menu.

## No guarantee

These tools are free. They depend on Ableton's extension SDK, which is still in beta, so they may not work depending on your Ableton beta version and can break when Ableton updates. Provided as-is, with no guarantee that they work and no liability if anything goes wrong. Back up your projects before using them.
All code was written with Claude Code.

---

Jonas Fasching  

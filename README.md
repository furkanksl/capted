# Capted

### Record. Then just ask.

Capted is a screen recorder and video editor for macOS. Record a product demo, tutorial, or walkthrough—or start with a blank canvas—then edit it yourself or ask the built-in AI agent to make changes on the same timeline.

**[Download for macOS](https://github.com/furkanksl/capted/releases/latest)** · **[Website](https://capted.app)** · **[Roadmap](https://capted.app/roadmap)** · **[Support](https://capted.app/support)**

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capted.app/landing/hero-dark.webp">
  <source media="(prefers-color-scheme: light)" srcset="https://capted.app/landing/hero-light.webp">
  <img alt="Capted editor with a video preview, layered timeline, animation controls, and AI editing assistant" src="https://capted.app/landing/hero-light.webp">
</picture>

## From recording to finished video

| Record | Ask | Refine | Export |
| --- | --- | --- | --- |
| Capture your screen, camera, and audio. | Describe what you want changed. | Adjust layers, timing, sound, and motion. | Render locally in the format you need. |
| [Watch recording](https://capted.app/landing/workflow-01-capture.mp4) | [Watch the agent](https://capted.app/landing/workflow-02-agent.mp4) | [Watch timeline editing](https://capted.app/landing/workflow-03-timeline.mp4) | [Watch exporting](https://capted.app/landing/workflow-04-export.mp4) |

The videos open directly from the website. For the complete interactive walkthrough, visit [capted.app](https://capted.app).

## What you can do

### Capture more than a screen

- Record a display, a window, or a selected region.
- Record a cable-connected iPhone or iPad.
- Capture face camera, microphone, and system audio with separate controls.
- Use live annotations and recorded cursor information to make actions easier to follow.
- Start from a blank canvas when your video does not need a screen recording.

### Edit manually—or work with an agent

- Cut and rearrange footage on a non-destructive timeline.
- Add text, images, video, shapes, arrows, callouts, and custom graphics.
- Arrange timeline tracks, reuse project assets, and control layers and backgrounds.
- Apply entrance, exit, and looping animations, including typewriter text and shader-based reveals.
- Add spring zooms, face-camera framing, cursor smoothing, and click effects.
- Ask the agent to inspect frames, edit captions, adjust the timeline, or build custom motion components. Review and refine its changes with the same controls you use by hand.

The editing agent connects through your own ChatGPT account; you do not need to paste an API key into Capted. Account availability, plan limits, and the AI provider's terms still apply. Capted is an independent product, not an OpenAI product.

### Work with sound and captions

- Import audio, control gain and fades, and shape volume over time.
- Search for CC0 sound recordings, preview them, and download only the sounds you want into your project.
- Generate designed clicks, pops, whooshes, and other procedural effects locally.
- Have the agent analyze and arrange samples, synchronize sound attacks to supported typewriter animations, and render the result into one reusable audio asset.
- Generate on-device captions in the supported languages, correct their text and timing, and place them on the timeline.

On supported Apple Silicon Macs, Capted uses Qwen3-ASR with an optional caption-engine and model download. Intel and older-macOS configurations use the Whisper backend. Capted manages caption setup; you do not need to install Python. Installed caption components can be reused offline.

### Export on your Mac

Choose the canvas and export settings for your destination, including landscape, portrait, square, source-resolution, and custom-size workflows. Capted supports MP4, GIF, and original-recording export workflows, with up to 4K/60 fps options where the project and hardware support them.

Project media and exports are stored locally. On-device caption recognition and local rendering do not require uploading recordings to a transcription or video-hosting service. **The editing agent is an online feature:** requests and selected context, such as frames or transcripts, may be sent to its AI provider. Sound search and downloads also contact their external provider. See the [privacy policy](https://capted.app/privacy) for details.

## A closer look

The website's feature gallery is still being filled in. These links use its reserved filenames, so the previews become available here when the corresponding files are deployed—without changing this README.

<details>
<summary>Layer editing, animation, and reusable looks</summary>

[Watch layered editing](https://capted.app/landing/animations-02-layers.mp4)

[Watch text and shape animations](https://capted.app/landing/animations-01-presets.mp4)

![Reusable backgrounds and canvas presets](https://capted.app/landing/animations-03-canvas-presets.webp)

</details>

<details>
<summary>Sound, captions, and camera movement</summary>

[Watch animation-synced audio and sound effects](https://capted.app/landing/studio-01-audio-sfx.mp4)

![On-device captions and audio editing](https://capted.app/landing/studio-02-captions-audio.webp)

[Watch camera framing, zooms, and cursor effects](https://capted.app/landing/studio-03-camera-cursor.mp4)

</details>

<details>
<summary>The editing agent and custom graphics</summary>

![ChatGPT account connection and editing agent](https://capted.app/landing/ai-01-chatgpt.webp)

[Watch custom motion components](https://capted.app/landing/components-01-define.mp4)

[Watch cleanup and portrait reframing](https://capted.app/landing/components-02-cleanup-shorts.mp4)

![Agent skills and rendered-frame inspection](https://capted.app/landing/components-03-skills.webp)

</details>

## Download and installation

1. Open the [latest release](https://github.com/furkanksl/capted/releases/latest) and download the DMG for your Mac. Check the release notes for the architectures provided by that release.
2. Open the DMG and drag **Capted** into **Applications**.
3. Launch Capted and grant the recording permissions needed for the capture sources you use.
4. Follow the in-app license activation and optional caption setup steps.

Capted targets **macOS 13.5 or newer** and is optimized for Apple Silicon. The Qwen caption engine requires a native Apple Silicon build on macOS 14 or newer. Download the normal app DMG—not the separate caption-engine archive; Capted installs that component when needed.

Capted is a paid app with a one-time license, not a recurring Capted subscription. See [current pricing and license options](https://capted.app/pricing). AI account requirements are separate from the Capted license.

## Where Capted is heading

The current [roadmap](https://capted.app/roadmap) focuses on:

- **More motion presets:** richer typography, shape and callout animations, and finer timing controls.
- **Reusable custom graphics:** a broader component starter library, richer inspector controls, and motion templates that work across projects.
- **More agent skills:** better guidance for kinetic typography, visual storytelling, and review of rendered scenes.

These are development directions, not promises of a release date. Individual releases document what has actually shipped. Feature requests and examples of real editing workflows help decide what comes next.

## About this repository

This is Capted's **public release and feedback repository**. It hosts downloadable releases, release notes, bug reports, and feature requests. It is not the application's source-code repository, and publishing binaries here does not make Capted open source.

For a bug report, [open an issue](https://github.com/furkanksl/capted/issues/new) with:

- Your Capted version, macOS version, and Mac chip.
- Steps to reproduce, what you expected, and what happened instead.
- A screenshot or short recording if it helps. Remove private content, license keys, access tokens, and personal information before posting; issues are public.

For billing, activation, or other private questions, use [Support](https://capted.app/support) rather than posting account details in an issue.

---

Made for people who would rather explain their product than spend the day editing the explanation.

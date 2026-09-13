# 02 - Spend only on approved assets

## High-quality images
After the animatic is approved, create clean individual frames, not polished giant storyboards. Use the approved panel as composition guidance, original character references as identity guidance, and the approved kitchen frame as world guidance. Keep the intended aspect ratio and caption-safe space.

A rough crop is a reference, not a final image to upscale blindly. Check face, proportions, outfit graphic/pattern, hands, food, relative scale and lighting. A usable still can support a wide shot and a close crop where its resolution permits. Keep lyrics, numbers and interface text out of generated art; add them in editing.

Make a contact sheet of HQ frames and ask for approval before video generation. Name assets by shot and version, e.g. S014_start_v02.png. Preserve source references and approved versions.

## Start and end frames
STILL: one clean image may be enough.
EDITOR_2D: supply separate foreground/background/prop assets or masks when the design actually needs layered movement. A flat image does not provide real parallax or independent character motion.
VIDEO: always use an approved start frame for this workflow. Add an approved end frame only when landing pose or continuity requires it and the chosen route supports it.
REUSE: point to an approved existing asset and source time range; do not submit a new generation.

For an end frame, edit from the same start composition where possible. Preserve lens, camera, subject scale, outfit and environment. Change only the action state. Do not force a camera-angle change or unrelated location between endpoints. Cut between different shots in the editor instead. Starting and ending images constrain a result; they do not guarantee correct motion between them.

## Initial animation proposal for this episode
Target 6-8 UNIQUE motions, subject to the approved storyboard and budget: curious tummy gesture, signature Deema dance, Adam/Deema clap, simple stirring, simple sharing, and happy finale. Add only motions whose value is clear. A technically complex chewing shot is optional; cutaway/reaction coverage is a valid lower-cost alternative.

Use modestly animated stills for food inserts, anticipation, thought bubbles, plate reveals, thank-you poses and reaction shots. Reuse approved chorus motions with deliberate reframing and cutaways. Do not reverse eating/handoffs, mirror asymmetric costumes, or stretch a short action across a much longer edit without a planned insert/hold.

## Provider-neutral shot data
For each shot record: ID/version; exact editorial start/end frames; lyric cue IDs; approved board reference; character/world references; still/start/end asset paths; required motion; camera behavior; reuse source; approval state.

Store generation settings separately: provider, model, web/app/API route, supported endpoint/reference combinations, generated duration, resolution, audio setting, quote, job ID, attempts, output path, and actual spend. Keep generated duration separate from editorial duration. Generate a supported length and choose the usable segment; do not assume every provider produces four seconds at the same price.

Use one canonical motion description plus a small provider-specific translation. Keep identity in the images. Before switching providers, confirm the new model/route supports the required controls and child-character content. Reuse the same approved frames when supported; otherwise stop and show the proposed change.

## Provider verification and budget
Treat the old '48 credits per four-second 1080p generation' as unverified archival data. Obtain a current quote from the selected route/settings. Do not convert Kling credits into Google credits as if they are the same unit.

Require an owner-approved total and per-provider cap; propose holding about 25% for retries. Check whether reference images, end frames, chosen length, resolution and audio settings can coexist. Do a small authorized representative test before committing a batch. Log the submitted job before polling. Download completed work promptly. Never submit a duplicate because a browser timed out.

Default to no paid API use until explicitly authorized. Subscription interfaces and API billing are separate access routes; do not assume an app allowance or promotional credit covers an API request. Use permitted authorized interfaces only. Never buy plans or credit top-ups automatically.

Google caveat: current Gemini API Veo documentation lists adult-only people settings for image-to-video/interpolation/reference-image routes and regional restrictions. Do not promise that these stylized child characters will be accepted. Check the intended product's current rules and exact model. Do not bypass a policy refusal or redesign children as adults to evade it. An approved alternative may be food/object-only shots or another service that permits the intended content.

## Audio and output review
The existing Suno song is the master. Disable generated audio when that model offers it; otherwise discard/mute the generated soundtrack in the edit. 'No audio' in a prompt is not a guarantee that the backend does not generate or bill for audio.

Review the whole clip, not just its first and last frame. Reject identity drift, unwanted speech, object morphing, extra limbs, broken hands, and unusable cropping. Keep unsuccessful attempts in a separate review folder and log why they failed. Do not retry indefinitely. When a shot reaches its cap, propose a still/editing fallback and seek approval.

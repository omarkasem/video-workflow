# 03 - Let CapCut finish a known edit, not discover the story

## Prove the actual setup first
Use the owner's intended production laptop. Check local folder access, installed CapCut version, desktop-agent computer-use availability/permissions, signed-in account and paid-feature entitlement. Having Codex CLI installed alone is not evidence that desktop control is enabled.

Record OS, display scaling, resolution and app-window layout. Keep them stable during a run; locate current UI elements from the actual screen rather than replaying hard-coded coordinates. Larger-text scaling is not automatically a fault. Read errors and dialogs instead of clicking blindly. Do not change the owner's account, display settings, permissions or plan without authorization.

## The 15-20 second pilot
Before full assembly, make a disposable local test project using available stills and a song excerpt. Import assets, place them in order, set durations, import valid SRT, apply the intended caption style, add one simple visual move, save, export and inspect. Reopen to check media paths. Prove this on the actual CapCut version before assuming that a full timeline will work.

A paid video is not needed for the first editor pilot. A previously approved/generated clip can be added when available. Save screenshots and exact successful steps as local operating notes. On supported eligible macOS setups, OpenAI's Record & Replay may help capture a stable routine; do not assume it is available on another platform or account.

## Recommended assembly design
Keep a machine-readable shot manifest as the timing authority and a local CapCut starter project as the styling authority. Never ask the agent to invent the sequence while manipulating the timeline.

Default easy mode: pre-render each approved still/edit effect as a separate correctly timed MP4 using local tools, then place those clips alongside approved generated videos in CapCut. This reduces repetitive GUI keyframing. It preserves shot-level editing but bakes the internal motion into that clip. Rebuild a shot from its source to alter that motion.

Optional editable mode: import source images/layers and add native CapCut keyframes, accepting more UI operations. Choose this only when demonstrated reliable. Do not flatten the entire episode to one MP4 unless the owner explicitly accepts losing shot-level editability. Do not promise that a JSON manifest imports directly into CapCut; the manifest is for our assembler/agent.

Do not make undocumented CapCut draft-JSON editing the default. A version-pinned, tested integration can be evaluated separately using disposable projects and backups.

## Timeline and captions
Use approved project settings, proposed initially as 1920x1080, 16:9 and 30 fps. Convert mixed-frame-rate assets deliberately and check for jitter; do not change the song speed. Quantize shot boundaries to frames, and make total duration match the complete song within the chosen frame-time tolerance. Transition handles must not silently shorten the edit.

Suggested track roles: visuals on the main video track; optional overlays above; lyric captions above; master song on its own audio track. Remove all unwanted generated audio. Import the approved SRT as editable captions. Validate the actual import on this CapCut version.

The provided draft SRT has corrected syntax and provisional non-overlap, NOT verified singing alignment. Use the authoritative lyric wording. For version 1, use phrase/line captions with one consistent font, outline, position and restrained animation. Reserve lower-frame safe space for them. Do not bake lyrics into character images. Word-by-word karaoke requires separately verified word timings; ordinary SRT does not encode full karaoke styling.

Use a local starter project for consistent styling. Avoid relying on a long chain of downloaded templates, account-only assets or cloud sync to make the project portable. Keep sources in one stable local project folder. Back up the project and media together; account entitlement and project existence are distinct questions to verify, not assumptions.

## Checkpoints and recovery
Save after import, rough assembly, captions, final styling and export. On failure, capture current screen and the last completed action; do not restart from scratch or regenerate media. Preserve source assets and the last working project. Reconcile the timeline against the manifest after edits.

## Final acceptance
Verify exact song version, full tail, lyric spelling and timing, no missing/black frames, no unintended audio, consistent characters, readable captions, complete motions, coherent story and a deliberate ending. Inspect the entire exported video, not only the timeline. Record export path, duration, dimensions, frame rate and any remaining issues. The owner approves publication separately.

Before publishing, verify the commercial-use entitlement for the actual Suno song and all third-party assets, and review the appropriate YouTube audience setting for a children's song channel. Do not publish automatically.

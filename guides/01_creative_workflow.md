# 01 - See the whole film before producing it

## A. Preserve the real inputs
Use sources/song.mp3 (metadata duration: 127.8 seconds). Read the supplied lyrics as the text authority, then compare every sung line with the audio. The supplied caption starts are a starting point only. Listen and verify rather than inventing precision. Keep instrumental spaces and the ending tail visible in the timing map.

The character sheets are the identity authority:
- Deema: young, stylized 3D child; curly brown hair in a top bun with reddish tie; large dark eyes; light sage floral romper with cream trim; light pink/cream shoes.
- Adam: older, stylized 3D boy; short wavy dark hair; black T-shirt with gold controller/lightning graphic; teal shorts; black-and-white trainers.

Do not independently reinvent them for each provider. Review close-up identity and the full-body silhouettes. Make an approved shared scale reference because separate sheets do not fix their exact relative heights. Keep the exact face, outfit patterns, hair and emblem. A reduced storyboard can simplify detail, but may not redesign identity.

Proposed episode rules, pending owner approval: one warm kitchen/dining space; Deema leads; Adam joins later; Mummy stays off-camera unless a new design is approved; no lip-sync requirement; one clear motion at a time. These are suggestions, not a claim that the old plan is accepted.

## B. Establish one rough visual-world frame
Propose the kitchen layout, table, lighting, palette and relative character scale in one inexpensive reference frame. Keep this rough. Do not spend on a full high-resolution asset library before the storyboard works. Retain a recurring kitchen master reference and a few recognizable props once accepted.

## C. Make the storyboard contact sheets
Target eight sheets with 4-6 wide 16:9 panels per sheet. Each sheet covers about 12-18 seconds in this draft. Each panel is a shot/key visual beat, NOT a whole 15-second clip. A start/end pose pair can occupy two panels but still belong to one shot ID; label this clearly.

Use rough color illustration or simplified cartoon rendering, not expensive final polish. The reader must be able to judge composition, character placement, facial intent, food choices, and continuity. Start with one sheet to agree the preview format, then complete the whole episode before any HQ production.

Every panel needs stable shot ID, approximate time range, lyric cue, one-sentence action, and one production label: STILL, EDITOR_2D, VIDEO, or REUSE. Add these labels as an external layout layer when practical; do not rely on generated lettering. Keep all annotations outside the image area used later for cropping.

Preferred production methods:
1. One model-generated overview grid per chapter is fine for the fastest initial review.
2. For revisions and continuity, create/change individual low-cost panels and assemble the contact sheet programmatically.

Neither method is guaranteed cheaper per API call; total cost depends on actual model, size, and retries. The main saving is rejecting weak scenes before final assets or video. Do not regenerate an entire accepted page to fix one panel.

The eight proposed chapter ranges are in project/project.json. They cover all 127.8 seconds but are not final shot boundaries.

## D. Review the whole story
Ask for feedback by IDs, e.g. 'keep S001-S010; replace S011; make Adam arrive sooner in S012.' Revise only affected panels and dependent timing. Keep approved versions. Story should progress: hunger -> ask -> discover food -> prepare/share -> happy tummy.

Use a few recurring visual motifs: a little drum/tummy rhythm, the signature tummy dance, a food parade, and a recognizable happy-tummy finale. Repeated chorus imagery should develop the story through new framing or food arrangements rather than repeat the exact full sequence.

## E. Build the animatic
An animatic is a rough video made by showing the actual approved storyboard panels at their planned times while the real song plays. Output a 720p review MP4, with shot IDs, draft lyric overlays, and simple motion cues. For a proposed VIDEO shot, use 1-3 rough poses or a hold plus an arrow cue; do not spend video credits to explain a movement.

A slideshow of complete pages is NOT the animatic. Show one panel/shot at a time. Use existing local media tools such as FFmpeg for predictable timing; no new local AI model is needed. The underlying timeline must preserve full audio duration. Review sync, slow/empty sections, transitions and the ending with the owner.

Approval of sheets is not approval of pacing. Stop until both the visual sequence and full-song animatic have explicit approval. If timing changes afterward, mark the affected shot approvals stale.

## F. Review interface
Start simple: numbered PNG sheets and one MP4. A local HTML gallery with scene comments can be added later, but is not needed to finish the first song. Avoid building a large dashboard before the first episode works.

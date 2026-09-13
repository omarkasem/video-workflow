# Source and timing audit

## What was actually inspected
The archive's two character-sheet images, lyrics, supplied caption text, both Markdown plans, and MP3 technical metadata. This audit does NOT claim a listening-based alignment of every sung word.

## Audio metadata
- Duration: 127.800 seconds (2:07.800).
- MP3 audio: 48,000 Hz, stereo.
- Character sheets: 1448 x 1086 pixels each.

## Caption file
The file named deemas_hummy_yummy_tummy_captions.srt contains 40 caption cues but is not standard numbered SRT. It includes section headings and bracketed minute/second timestamps with decimal points. 39 adjacent cue pairs overlap. This does not prove the song timing is wrong, but it is unsuitable as an unquestioned single-line caption import.

The included lyrics_DRAFT_normalized.srt converts the syntax and trims each overlapping end to the next supplied start. All start times and lyric wording are preserved. The change log is in caption_adjustments.json. These mechanical edits do not constitute verified synchronization.

First supplied lyric start: 2.713 seconds. Last supplied lyric end: 124.947 seconds. The audio has a further 2.853 seconds after that supplied end. Preserve the musical tail unless the owner chooses otherwise.

## Existing storyboard conflicts
| Passage | Existing storyboard start | Supplied caption start | Difference |
|---|---:|---:|---:|
| First chorus | 24.000 s | 21.782 s | +2.218 s |
| Apples / verse 2 | 49.500 s | 46.037 s | +3.463 s |
| Second chorus | 65.300 s | 58.165 s | +7.135 s |
| Mix it / bridge | 90.800 s | 82.500 s | +8.300 s |
| Final chorus | 103.900 s | 93.750 s | +10.150 s |
| Outro | 127.000 s | 118.963 s | +8.037 s |

The final storyboard scene allows 0.8 seconds for both outro lines. The supplied caption range for those lines spans 5.984 seconds before the musical tail. Rebuild the map from verified audio/lyrics rather than stretching this scene list.

## Production planning concerns
The legacy plan assumes ten paid four-second generations at a fixed credit rate, but several assigned edit scenes last more than six seconds. It lacks precise usable-source ranges or insert coverage to bridge that difference. Some nominally single-action clips combine multiple actions. It also has no whole-film visual-board review, animatic approval, provider-specific capability checks, or resumable execution state.

The existing hybrid still/video/reuse idea is worth keeping. Its timings, fixed prices, and creative choices are not considered approved. The new chapter map and 6-8 unique-motion target are proposals, not a finished production budget.

## Status
No new visual scene images, video clips, animatic, CapCut project or final export were created by this kit. No provider credit was spent. The kit provides instructions and source preparation only.

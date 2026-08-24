# Bad Takes — release notes

What changed in each version. Downloads for every release are on the
[Releases](../../releases) page.

## v0.9.0 — 24 August 2026

### Scoring, with difficulty settings

Every take you record is now scored against the original performance. Four
things are measured — the shape of your pitch, your rhythm and energy, your
timing, and how much of the line you actually covered — and the result lands on
the cue card the moment you stop recording. The screening room adds up the
scene, broken down by character, so you can see which line dragged the total
down.

Difficulty is in Settings: Easy, Medium or Hard. Changing it re-grades every
take you have ever recorded, instantly — the recording keeps its raw score and
only the grade moves, so switching difficulty costs you nothing and tells you
something new. Settings also tracks your last six sittings and whether you are
getting better.

![A take scored at 78%, and the same recording graded on Easy, Medium and Hard](notes/0.9.0/scoring.gif)

A take too quiet or too short to measure reads as a dash, never as zero.

## v0.8.0 — 23 August 2026

Performance improvements and internal groundwork. Nothing user-facing in this
one — worth installing to stay current, but you are not missing a feature by
skipping it.

## v0.7.0 — 21 August 2026

### Auto-update fixed

Installed copies were checking for updates against a file that did not exist.
The update feed pointed at one filename and the release hosted another, so every
check quietly found nothing and every copy stayed where it was. The names now
match, and updating works.

**If you are on v0.5.0 or v0.6.0, this release will not reach you
automatically** — download it manually, install over the top, and updates from here
will arrive on their own.

The Windows download link was pointing at a filename that was not there either;
that is fixed in the same change.

## v0.6.0 — 20 August 2026

### The app is free

An account now costs nothing. Playing a scene, recording your take, and
exporting what you made — audio, video, or a vertical reel — are unlimited on
every plan, forever. So is installing a scene somebody sends you.

Two things are metered on the free plan: building a scene and sharing one. You
get five of each straight away, then one a day. The $10 purchase removes both
limits and is a one-time payment.

![What the free plan includes, next to the $10 purchase](notes/0.6.0/free.png)

The two allowances are separate — spending one never blocks the other — and
Settings shows where each of them stands, alongside a report of what you made
this month.

## v0.5.0 — 19 August 2026

### The background keeps playing under your take

A scene's music and room tone used to drop out for exactly as long as you were
speaking, because the only audio under a line was the original performer's — and
replacing them meant losing everything recorded with them.

The editor can now separate a scene's background from its dialogue, and that
background plays underneath your take. The music carries on through your line
instead of falling into a hole around it.

![The scene's background dropping out under a take, and carrying on under it](notes/0.5.0/background-bed.gif)

### Editing a scene saves a new version, and your takes come with it

Editing a scene no longer overwrites it. The edit is saved as a new version and
your recordings are carried across, matched to the lines they were performed
over — so fixing a caption or retiming a line does not cost you the takes you
already recorded.

The version you edited stays exactly where it was, with its own recordings
intact.

![Version 1 and version 2 of a scene, takes carried from one to the other](notes/0.5.0/versions.gif)

## v0.4.0 — 18 August 2026

### Every take is nudged into place as you record

Microphones do not start instantly. A freshly woken mic swallows the first
40–60 milliseconds, and the take that results sits late against the line for
the rest of its life — by an amount you can hear but cannot easily fix.

Bad Takes now measures each take against the line it was performed over and
shifts it onto the beat as it saves. Only when it is confident, and never by
more than 250ms, so a pause you left on purpose stays a pause you left on
purpose.

![A take recorded 90ms late, shifted onto the original line](notes/0.4.0/auto-align.gif)

The macOS builds are Developer ID signed, notarized and stapled. The Windows
installer is not yet code-signed, so Windows SmartScreen will warn on first run
— choose More info → Run anyway.

## v0.3.0 — 17 August 2026

### Share a scene

A scene you made is now something you can hand to somebody. Export it from the
scene's page and you get a single file; whoever receives it drops it onto their
own copy of Bad Takes and it installs like any other scene.

Your own recordings never travel with it. What you share is the scene — the
audio, the stills, the lines and who says them — and nothing you performed.

### Pinch to zoom the waveform

The creator's waveform strip zooms under a trackpad pinch, so marking a line
that lasts half a second no longer means aiming at a two-pixel target.

## v0.2.0 — 17 August 2026

### Make a scene out of any video you have

Up to now you could only dub scenes somebody else had built. The scene creator
turns any video into one: drop a file in or paste a link, drag the handles to
the part worth dubbing, mark who says what on the waveform, then name it and
pick a thumbnail. What comes out is an ordinary scene — you can dub it, and so
can anyone you send it to.

![The four steps of the scene creator: Video, Scene, Lines, Details](notes/0.2.0/creator.gif)

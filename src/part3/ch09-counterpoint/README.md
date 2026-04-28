# Counterpoint

[DRAFT]

## Differences from the Counterpoint of Triadic Harmony

1. **There are no forbidden parallels in the traditional sense.** The chord-graph already encodes voice-leading parsimony — every legal motion is one voice × one semitone × three common tones. The Fuxian prohibition on parallel fifths/octaves does not transfer directly because every chord *contains* fifths by construction. The OTH analog is the **orbit-persistence prohibition**: avoid sustained motion within a single orbit (more than two consecutive edges in the same orbit can produce voice-fusion).

2. **Consonance and dissonance live at the chord-class level, not the interval level.** Within any chord, every interval is in {d5, P5, A5} — there are no "dissonant intervals" by construction. What is "dissonant" in OTH is the chord-class itself: high-degree orbits (Summit, Plateau Q787) are stable; low-degree orbits (Narrows, Precipices) are tense. The Saddle is uniquely tense-yet-connected.

3. **Cadence is geodesically determined.** The OTH cadential formula is **Saddle → Slope → Summit** — a verified geodesic of distance 2 through the chord-graph. This is not a postulated rule; it is the unique distance-2 path between the structurally extremal tension chord (Saddle) and the structurally extremal stability chord (Summit).

4. **Voice motion is intrinsically four-voice.** OTH chords are tetrachords by definition; there is no clean two-voice reduction. The species progression in OTH varies degrees of freedom in chord motion, not rhythmic subdivision against a cantus firmus.

5. **Some devices have no triadic precedent.** The multiset-collision shadow, the fiber-as-color voice, the leading-interval-pair resolution, and the wedge convergence on a shadow note are OTH-native. They are not "OTH versions of triadic devices"; they are devices that depend on OTH's specific geometry.

## The "cantus firmus"

In Fuxian counterpoint, the cantus firmus is a fixed melody in whole notes against which the student writes a counterpoint melody. In OTH, the equivalent is the **chord-graph path** — a sequence of base-space chords connected by legal motions. The student writes voice lines that move through this harmonic frame.

A typical exercise cantus firmus might look like:

```
Chord 1: C-G-D-A          Q777 Summit (home)
Chord 2: C-G-D-Bb         Q877 Plateau (one note moved: A → Bb)
Chord 3: C-G-Eb-Bb        Q787 Plateau (one note moved: D → Eb)
Chord 4: C-G-D-A          Q777 Summit (return — two single-semitone edges back)
```

This is a 4-chord cantus firmus traversing two chord-graph edges away from the Summit and back. Each chord transition is a single edge (verify: each adjacent pair shares 3 of 4 notes). The path is geometrically clean: Summit → Plateau → Plateau → Summit.

Throughout this guide, exercises use chord-graph paths of this kind as the cantus firmus. The student writes one or more upper voices that move melodically while the harmonic frame holds.

## Setting up an exercise

To begin an OTH counterpoint exercise:

1. **Choose a chord-graph path.** Start short — 3 to 5 chords. Verify each transition is a single edge (use the music-theory MCP's `get_oth_neighbors` if needed). Include at least one return to a starting orbit or one cadential gesture.

2. **Choose a voice register and starting pitch.** Decide whether the added voice will sit above (alto/soprano), below (tenor/bass), or interleaved with the cantus firmus.

3. **Decide the species you are working in.** This determines what motion types are available.

4. **Write the line one chord-zone at a time.** Each chord in the cantus firmus defines a "zone" in which the voice can move melodically; species rules determine how much motion is allowed.

5. **Check legality.** Voice lines should follow species rules; the harmonic transitions of the cantus firmus should be valid chord-graph edges.

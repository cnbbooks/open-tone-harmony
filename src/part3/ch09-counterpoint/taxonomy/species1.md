## 1.1 First Species — Note-against-Chord

**Definition.** First species places one note in the added voice for each chord in the cantus firmus. The added voice plays a chord tone; it does not move melodically within a chord-zone. Voice motion happens only at chord-graph transitions.

**What this teaches.** First species teaches the student to **see the chord-graph as the source of motion**. Every voice movement happens because the underlying chord-graph moves, not because the voice elaborates within a static harmony. The student learns to track which chord tones are available at each step and which create good melodic lines.

**Setup.** A chord-graph path of 4-8 chords. The added voice begins on a chord tone of the first chord and ends on a chord tone of the last chord — preferably the cadential Summit if the path is cadential.

### Step-by-step procedure

1. **Identify the chord-graph path.** Write out the cantus firmus chord by chord. For each chord, list the four chord tones. Note which orbit each chord belongs to.

2. **Identify common tones across each transition.** At every adjacent chord pair, identify which notes are held in common (typically three of four). The common tones tell you what the *static* options are at each transition.

3. **Identify the moving voice in the cantus firmus.** At each transition, exactly one voice in the cantus firmus moves by one semitone. Identify which chord tone changes. This is the cantus firmus's "active voice" at that moment.

4. **Choose the added voice's range.** Decide whether the added voice sits above the cantus firmus (in soprano range) or below (in tenor range). Above is more common for upper voice lines; below is harder because chord-graph collisions with the bass are more likely.

5. **Pick the first note.** Choose a chord tone of the first chord that is in the added voice's range, *not duplicated* in the existing voicing. If the cantus firmus already has C-G-D-A in low register and you're adding a soprano voice, you might pick C5 (chord tone, octave-displaced from the bass C2).

6. **Move chord by chord.** At each chord transition, decide:
   - **Stay on the same pitch** if it is still a chord tone in the new chord (a "common-tone hold"). This is the OTH analog of a pedal note — it shows that the chord-graph moved but the added voice held.
   - **Move to a new chord tone** that is one or two chord-graph edges away from your current pitch (a melodic step or skip).

7. **Approach the cadence by contrary motion.** As the cantus firmus approaches the Summit, the added voice should move in contrary motion (cantus firmus ascending → added voice descending, and vice versa). This honors the OTH "leading-interval-pair" cadence: two voices each moving by one semitone, one expanding a tritone, one contracting an A5.

8. **End on a chord tone of the final chord** (preferably a stable one — Summit or Plateau).

9. **Check.** Every note in the added voice must be a chord tone of its corresponding chord in the cantus firmus. No exceptions in first species.

### Worked example

Cantus firmus (bass + held voicing):

```
Chord 1: C2-G2-D3-A3      Q777
Chord 2: C2-G2-D3-Bb3     Q877  (A→Bb in voice 4)
Chord 3: C2-G2-Eb3-Bb3    Q787  (D→Eb in voice 3)
Chord 4: C2-G2-D3-A3      Q777  (return — two edges back; via Q877 again)
```

Wait — chord 4 must connect to chord 3 by a single edge. From Q787 = {C,G,Eb,Bb}, moving to Q777 = {C,G,D,A} requires *two* changes (Eb→D and Bb→A). That's two edges. Inserting an intermediate chord 3.5: Q877 = {C,G,Eb,Bb} → {C,G,D,Bb} (Q877; Eb→D) → {C,G,D,A} (Q777; Bb→A). This expands to:

```
Chord 1: C2-G2-D3-A3      Q777
Chord 2: C2-G2-D3-Bb3     Q877
Chord 3: C2-G2-Eb3-Bb3    Q787
Chord 4: C2-G2-D3-Bb3     Q877  (return through second Plateau)
Chord 5: C2-G2-D3-A3      Q777  (cadence)
```

Five chords; four single-edge transitions; cadence at chord 5.

Add a soprano voice. Rules: chord tones only; contrary motion to the cadence.

Soprano analysis:

| Chord | Available chord tones (in soprano range) | Choose | Reason |
|---|---|---|---|
| 1 | G4, A4, C5, D5 | **G4** | Stable opening; low end of range |
| 2 | G4, Bb4, C5, D5 | **Bb4** | Step up; chord tone (the A→Bb change moves in soprano too — but here we're in the upper voice, not voice 4) |
| 3 | G4, Bb4, C5, Eb5 | **C5** | Step up; common tone with chord 2 |
| 4 | G4, Bb4, C5, D5 | **D5** | Step up to peak |
| 5 | G4, A4, C5, D5 | **A4** | Contrary motion descent to cadence — D5 → A4 is a P5 leap, but in OTH that's a structural-fifth descent, totally appropriate at the cadence |

Soprano line: G4 → Bb4 → C5 → D5 → A4.

**Check.** Each note is a chord tone. The line ascends G4→Bb4→C5→D5 (three stepwise moves) and descends to the cadence A4 (a structural-fifth leap downward). Contrary motion at the cadence: the cantus firmus's last edge is Bb→A (descending semitone in voice 4); the added voice's last move is D5→A4 (descending fifth). Both descend — so this is *similar motion*, not contrary. To get contrary motion, the added voice should ascend at the cadence: e.g., end on D5 → C5 (descending whole step) instead of D5 → A4. But wait — the cantus firmus's voice 4 moves Bb→A (descending), so for contrary motion the added voice should *ascend*. Let me revise:

| Chord | Choose | Reason |
|---|---|---|
| 1 | C5 | Open on the tonic |
| 2 | C5 | Common-tone hold |
| 3 | C5 | Common-tone hold |
| 4 | C5 | Common-tone hold |
| 5 | C5 | Common-tone hold |

This is too static. Try again:

| Chord | Choose | Reason |
|---|---|---|
| 1 | C5 | Open on the tonic |
| 2 | Bb4 | Step down; chord tone (parallels the cantus firmus's A→Bb) |
| 3 | Bb4 | Common-tone hold |
| 4 | Bb4 | Common-tone hold (cantus firmus moves Eb→D underneath) |
| 5 | A4 | Cadential descent — but this is similar motion with cantus firmus's Bb→A |

Hmm. The cantus firmus's last edge Bb→A is a single voice descending; for the added voice to move in contrary motion at the cadence, it needs to ascend or stay. Let me make the soprano line:

```
Chord 1: D5
Chord 2: D5  (held — common tone)
Chord 3: Eb5 (step up — chord tone)
Chord 4: D5  (step down — chord tone; contrary to soprano-4-Eb5)
Chord 5: A4  (descent to cadence — structural P5 descent; cantus firmus also descends; SIMILAR motion)
```

The OTH cadence resolves Q877→Q777 with one voice moving Bb→A (single descending semitone). For the added voice to have *contrary motion* at the cadence, it must ascend or hold. Holding D5 across chord 4 → chord 5: but D is in both Q877 and Q777, so this is a common-tone hold:

```
Chord 1: D5
Chord 2: D5  (common-tone)
Chord 3: Eb5
Chord 4: D5
Chord 5: D5  (common-tone hold — contrary motion is *oblique*)
```

This is a clean first-species line. The cadence is reached via oblique motion (added voice holds D5; cantus firmus moves Bb→A). The added voice traverses D5 → D5 → Eb5 → D5 → D5 — a single neighboring excursion to Eb5 and back. Plain but legal.

### Common errors in first species

1. **Non-chord tones.** First species requires every note to be a chord tone. Slipping in a passing tone (which is allowed in second species but not first) is the most common error.

2. **Parallel motion across multiple chord-graph edges.** If the added voice moves in lockstep with the cantus firmus's moving voice across multiple transitions — both ascending or both descending by one semitone each time — you create the OTH analog of parallel-fifth motion. In first species, prefer contrary or oblique motion at every transition.

3. **Failing to land the cadence.** The added voice should end on a chord tone of the final chord, ideally the *root* of the cadential Summit (or its octave). Ending on an inner chord tone (like A4 over a C Summit) is acceptable but feels less "settled."

4. **Voice crossing.** The added voice should not cross below the cantus firmus's top voice. If your added voice is in soprano range, watch out for moments when the cantus firmus's voice 4 ascends into your range.

5. **Static line.** A first-species line that holds the same pitch for all five chords is technically legal (every note is a chord tone) but pedagogically boring. Aim for at least one melodic step or skip somewhere in the line.

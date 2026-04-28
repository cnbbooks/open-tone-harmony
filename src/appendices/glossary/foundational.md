## I. Foundational Terms

### Open Tone Harmony (OTH)

A non-tertian harmonic system built from stacked fifths and fourths, governed by the **[6,8] constraint**: consecutive stacking intervals in four-voice chords must be drawn from {d5, P5, A5} = {6, 7, 8 semitones}. The name derives from the characteristic acoustic quality of quintal/quartal sonorities — their open, resonant, unresolved-yet-stable sound.

### The [6,8] Constraint

The defining rule of the system. A four-note chord belongs to OTH if and only if it can be stacked (bottom to top) with consecutive intervals each equal to a diminished fifth (6), perfect fifth (7), or augmented fifth (8). This single constraint generates the entire 228-chord space.

### Base Space (B)

The metric space of 228 four-note pitch-class sets satisfying the [6,8] constraint. B has diameter 8 (the maximum geodesic distance between any two chords) and eccentricity range 7–8 (54 central chords with eccentricity 7; 174 peripheral chords with eccentricity 8). B is the "ground" on which all of OTH is built.

### Extended Space (E)

The full space of voiced (registral) chords obtained by applying Tymoczko's interscalar transposition to each chord in B. E is a ℤ₄-fiber bundle over B: each chord in B has four inversional positions, of which typically 1 (Class A orbits) or 2 (Class B orbits) land back in [6,8].

### Chord-Graph

The graph whose vertices are the 228 chords of B and whose edges connect chords differing by a single-semitone single-voice move (three voices held, one moved ±1). This is the lattice of legal atomic voice motion in OTH.

### Edge

One step in the chord-graph: one voice moves by one semitone while three voices hold. The atomic unit of harmonic motion.

### Geodesic Distance

The length of the shortest path between two chords in B, measured in edges. Ranges from 1 (neighbors) to 8 (antipodal chords, e.g., C–G–D–A to A♭–E♭–B♭–F).

### Orbit

An equivalence class of chords under the combined action of transposition (T_n) and pitch-class inversion (I_n). There are **14 T/I orbits** in B, each with a characteristic interval recipe. Orbits are the "chord types" of OTH — analogous to major triads, minor triads, etc. in tertian harmony.

### Isometry Group

The group of distance-preserving transformations of B: **ℤ₁₂ ⋊ ℤ₂** (the T/I group, 24 isometries). This is the same symmetry group that governs the triadic Tonnetz and standard pitch-class set theory.

### Interval Recipe

The ordered triple of stacking intervals (up to reversal) that characterizes an orbit. For example, [7,7,7] for the Summit, [6,8,6] for the Saddle, [7,6,7] for a Valley. Non-palindromic recipes like [6,7,7] are equivalent to their reversal [7,7,6] under inversion.

### Degree

The number of valid single-semitone neighbors a chord has in B. Ranges from 4 (minimum — Valleys, Narrows) to 8 (maximum — Summit, upper Plateau, Saddle). Degree is the primary measure of harmonic connectivity and stability.

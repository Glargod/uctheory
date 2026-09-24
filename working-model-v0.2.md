# UC Theory — Working Model v0.2 (Test Layer)

**Author:** Robert Charest (Glargod)  
**Date:** 24 September 2026  
**Status:** Mechanistic / proto-physical add-on. Does **not** replace the 17 August 2026 ontology page.  
**Companion to:** https://glargod.github.io/uctheory/ and `falsifiability.md`

This document is the part a skeptic can run. Ontology stays on the main page. If a module fails, that module is dropped or rewritten. The rest of the architecture can remain.

---

## 0. Operating rules

### 0.1 Zero-default rule

Every compositional fraction that cannot be measured in the current run is set to

$$R_i = 0$$

unless the protocol explicitly turns it on.

| Fraction | Default in Test Layer | Why |
|---|---|---|
| $\varphi_c$ (consciousness) | $0$ | Not independently measured. Ontology may still treat it as primary. Tests do not. |
| thermal | $0$ unless temperature is controlled and logged | Confound otherwise |
| magnetism | $0$ unless a magnetometer channel is on | Confound otherwise |
| matter (bulk rest-mass density of the *object*) | given by scale / geometry | Ordinary mass of the probe |
| charge $q$ | measured or $0$ | Marble protocol turns this on |
| light / photonic $R_\gamma$ | **on** | Light is part of Pleichyma and is the only composition we can drive and detect cleanly |
| background Pleichyma density $\rho_P$ | held as a *medium load*, not as particle mass | Density $\neq$ rest mass |

$\varphi_c = 0$ in this layer means: *do not use consciousness as an explanatory knob for any number you publish*. It does not mean the ontology has been abandoned.

### 0.2 Density is not mass

$$m_{\mathrm{rest}} \neq \rho_P \times V$$

$\rho_P \sim 10^{-27}\,\mathrm{kg\,m^{-3}}$ is a background load on the medium. Rest mass of a localized object is accounted as trapped energy in a closed coflux cycle:

$$m_{\mathrm{rest}} = \frac{1}{c_*^2}\int_{\mathrm{core}} \varepsilon(\mathbf{C}, R_\gamma, q)\,dV$$

If a derivation ever writes $m = \rho_P V$, that derivation is out of spec.

### 0.3 Stability is categorical, not linear

tflux $\mathbf{T}$ is part of the state. A bound structure is an *allowed continuation*, not a Lyapunov-stable equilibrium on a frozen clock. Tests therefore look for:

- persistence vs sudden dissolution / radiation,
- time offsets and reduced effective acceleration,
- optical signatures of delayed or circulating photonic current,

not for a clean eigenvalue spectrum.

### 0.4 Two regimes stay labeled

- **[M]** Mechanistic — numbers, apparatus, pass/fail.
- **[S]** Symbolic — meaning, $\varphi_c$, mythic mapping.

Nothing in §1–§5 of this file is [S].

---

## 1. Minimal working state [M]

Keep only what a bench can touch.

$$\mathcal{P}_{\mathrm{test}} = \{ x,y,z,\; t,\; \rho_P,\; q,\; R_\gamma,\; \mathbf{C} \}$$

with defaults $R_\gamma$ driven by the apparatus, $q$ measured, $\varphi_c = 0$, other fractions $0$.

**Coflux (working form):**

$$\mathbf{C} = -\alpha\nabla\rho_P - \beta\nabla q - \gamma\nabla R_\gamma + \tau^{-1}\mathbf{D}(\mathbf{T})$$

- $\alpha,\beta,\gamma$ = restore coefficients (unknown; to be bounded, not fitted to everything).
- $\tau$ = medium response time. This is the one new lab-scale parameter the marble run is allowed to claim.
- $\mathbf{D}(\mathbf{T})$ = directional remainder from tflux. In v0.2 it is treated as a *delay / permission* term, not as a free vector you tune after the fact.

**Default claim of v0.2:** at laboratory scales, with $\varphi_c = 0$, the only distinctive signature is a **finite coflux response time** $\tau$ that couples more strongly to charge and light than to neutral bulk mass.

If $\tau \to 0$ under clean conditions, the Test Layer has nothing left to say. Ontology can still exist; the working model does not.

---

## 2. Three modules people can actually run

Each module has: claim, apparatus class, predicted sign, kill condition.

### Module A — Charged delay (primary empirical anchor)

**Claim [M].** A small charged dielectric probe in free fall (or short drop) shows a start-up lag and a reduced *effective* acceleration relative to a matched neutral twin, after electrostatic, thermal, and air-current artifacts are removed.

**Author’s prior numbers (not yet independent):**  
$q \sim 10^{-9}\,\mathrm{C}$, $\Delta t \approx 0.197\,\mathrm{s}$, $a_{\mathrm{eff}} \approx 5.6\,\mathrm{m\,s^{-2}}$ vs $9.8\,\mathrm{m\,s^{-2}}$.

Treat those as *hypotheses to replicate*, not as constants of nature.

**Minimum independent protocol**

1. Two matched marbles / spheres, same mass and diameter.
2. One charged to a logged value (Faraday cup or induction plate), one neutral.
3. Same release mechanism (electromagnet or mechanical latch), same clock.
4. Faraday cage or grounded conducting enclosure.
5. Temperature matched to $\pm 0.5^\circ\mathrm{C}$.
6. Repeat in still air, then (if possible) reduced pressure.
7. High-speed camera or dual photogates. Report raw traces, not just a single lag number.
8. Pre-register: “effect is present if lag exceeds $X$ ms at $p < 0.01$ after artifact budget.” Suggested first gate: $X = 20\,\mathrm{ms}$ on a drop of $0.5$–$1.5\,\mathrm{m}$. The 197 ms figure, if real, will clear that easily. If it does not clear 20 ms under shield, Module A is materially weakened.

**What would kill Module A**  
Independent shielded, temperature-matched, low-pressure runs consistent with $g$ and with zero lag inside the artifact budget. That is already the #1 vulnerability in `falsifiability.md`.

**What Module A does *not* prove**  
Consciousness, dark matter, or Compton-scale trapping. It only keeps a finite $\tau$ coupled to charge on the table.

---

### Module B — Light is a Pleichyma fraction (optical hook)

This is the new testable door. Light is already in the composition list. Drive $R_\gamma$, watch $\mathbf{C}$.

**Claim [M].** If photonic fraction is a real compositional current in the medium, then a strong, localized, non-ionizing light field on or near the probe changes the same observables Module A cares about (lag, $a_{\mathrm{eff}}$, or a timing residual), *with charge held fixed*.

**Why this is not empty**  
Charge-only anomalies can always be electrostatics. Light-only, charge-fixed anomalies are harder to hide in Coulomb force. If both charge *and* light move the same delay channel, you have a composition story rather than “the marble was sticky.”

**Cheap first protocol (kitchen / shop)**

1. Neutral *and* charged drops as in Module A.
2. Add a third condition: intense LED or laser illumination of the drop path or of a scattering cell just above the release, wavelength logged, irradiance logged.
3. Keep heating of the probe below a stated budget (IR thermometer on the sphere). If the sphere warms, you measured thermal expansion / viscosity, not $R_\gamma$.
4. Compare four cells: neutral / dark; charged / dark; neutral / lit; charged / lit.

**Predicted sign if v0.2 is onto something**

- Neutral / lit ≈ neutral / dark (light alone, no charge, weak).
- Charged / lit differs from charged / dark in the *same direction* as the charge delay (lag up or $a_{\mathrm{eff}}$ down).
- Effect tracks irradiance, not bulb warmth.

**Kill condition**  
No difference between lit and dark once probe temperature and air heating are matched. Then $R_\gamma$ stays in the ontology list but drops out of the Test Layer.

**Better (still cheap) upgrade**  
Photogate timing through a short optical cavity vs open path, same drop. If a standing optical field changes $\tau$ and a traveling beam of equal average power does not, that is a confinement hint — the same logic as trapped-light mass, at tabletop scale. Do not call that “Compton.” Call it “cavity vs beam control.”

---

### Module C — Neutral control and composition isolation

**Claim [M].** If coflux couples to composition, not to bulk mass, then:

- matched-mass metal vs dielectric vs charged dielectric do not all move the same way,
- a change in bulk mass at fixed charge and fixed illumination does **not** scale the lag like inertia would.

**Protocol**  
Same drop rig. Three probes, masses within 5 %: uncharged glass / plastic; charged glass / plastic; uncharged metal (grounded or Faraday-checked).

**Predicted sign**  
Lag / $a_{\mathrm{eff}}$ shift lives with *charge* (and, if Module B lives, with light), not with density of the ball.

**Kill condition**  
All three probes indistinguishable. Then you do not have composition; you have a systematic in the rig.

---

## 3. What v0.2 is allowed to claim if A survives

If independent runs keep a charge-linked delay after artifacts die:

1. There exists a lab-scale response time $\tau > 0$ in the charged channel.
2. Rest mass of the marble is still ordinary $m$; the anomaly is in the *onset* of motion, not in a new gravitational constant.
3. A working estimate is $\tau \sim \Delta t_{\mathrm{lag}}$ and $a_{\mathrm{eff}} \approx g(1 - e^{-\Delta t_{\mathrm{drop}}/\tau})$ as a first curve to fit or reject. If the traces are not even roughly this shape, throw the formula out and keep only “delay exists.”
4. Photonic fraction remains a live handle (Module B), not a slogan.

None of that is a Theory of Everything. It is a constrained medium-response model with one new time and two on-switches (charge, light).

---

## 4. What stays off the bench until specified

These remain [S] or “not yet a module.” Publishing them as results is out of spec.

- $\varphi_c$ modulation of free-fall or pendulum timing
- EEG-gated drops
- Gaia / cusp-core as a Pleichyma detection
- Compton-scale derivation of rest mass from coflux
- algebraic vacuum walls, $Z=172$, 1088 GeV
- ghost-trajectory statistics without a pre-registered observable

Rule from `falsifiability.md`, kept: a component is not strongly falsifiable until conditions, direction/magnitude, and discriminator vs standard physics are stated. v0.2 does that only for Modules A–C.

If someone later wants $\varphi_c$ on the bench, they must name the coherence variable they will change, the predicted shift in $\tau$ or $a_{\mathrm{eff}}$, and the confound budget (attention, muscle, heat, clock).

Until then $\varphi_c = 0$ in every spreadsheet.

---

## 5. Bridge to trapped-light / Compton talk (honest)

Shared idea with the IT³ / confined-EM picture: rest mass can be *accounted* as energy that has stopped streaming.

v0.2 does **not** derive $L \sim \hbar/(mc)$. It only says light is an on-switch in the medium, a closed coflux cycle is how you would *book* rest mass, and tabletop “cavity vs beam” (Module B upgrade) is the farthest this layer may go toward confinement.

If Module A dies, the bridge dies with it. If Module B dies, light-as-composition dies in the Test Layer even if the ontology still lists it.

---

## 6. One-page run sheet (print this)

```
UCT v0.2 run sheet
Date / operator / location:
Enclosure:  open / Faraday / vacuum-ish
T_air =        °C     ΔT_probe budget =
Camera / gates:

Probe          q (C)     lit (Y/N)   λ / irradiance     lag (ms)   a_eff     notes
neutral dark
neutral lit
charged dark
charged lit
metal   dark

Pass A?  lag_charged_dark − lag_neutral_dark  > 20 ms after artifact budget   Y/N
Pass B?  charged_lit differs from charged_dark, same sign, heat budget held   Y/N
Pass C?  metal ≈ neutral, not ≈ charged                                       Y/N

φ_c used in the analysis?   NO (default 0)
m = ρ_P × V used?           NO
```

---

## 7. How this changes the public theory page

Keep `falsifiability.md` as the audit. This file is the recipe.

*Default to zero. Drive what you can see. Let the marble, the cage, and the lamp do the talking.*

# Quiz 2026 — Applications of X-ray and Neutron Scattering in Biology, Chemistry and Physics

Course code 47336 (DTU Energy / University of Copenhagen).

This quiz covers every topic taught in the course. It is organised in two parts:

- **Part A — One correct answer.** Each of the 9 topics has 3 questions. Every question has a short educational lead-in, 4 answer options (exactly one correct), and a short explanation of *why* the answer is correct.
- **Part B — Multiple correct answers.** One question per topic (9 questions). Two or more answers may be correct.

Correct answers are marked with **(correct)**.

---

## PART A — ONE CORRECT ANSWER

---

## Topic 1 — Mathematical Foundations (Vectors, Complex Numbers & Fourier Transforms)

### Q1.1
Scattering experiments involve beam directions, momentum transfer, and displacements. These are described using vectors — quantities with both size and direction.

**What is the main difference between a scalar and a vector?**

- A. A vector has both magnitude and direction; a scalar has magnitude only **(correct)**
- B. A scalar has direction; a vector does not
- C. A vector has no physical units
- D. Scalars are only used in MRI, not in scattering

*Why:* Scalars (e.g. temperature, speed) are described by a single number. Vectors (e.g. momentum, beam direction) need magnitude and direction — essential when describing scattering geometry and Q.

### Q1.2
The pattern on a detector is not the structure itself — it is a transform of it. This link between real space and reciprocal space is central to scattering and diffraction.

**What is the mathematical relationship between the real-space structure of a sample and its scattering/diffraction pattern (reciprocal space)?**

- A. They are related by a Fourier transform **(correct)**
- B. They are related by a simple linear scaling factor
- C. They are identical to each other
- D. They are related by a vector cross product

*Why:* The scattered wave amplitude is the Fourier transform of the scattering-length-density (or electron-density) distribution. Real space and reciprocal (Q) space are a Fourier-transform pair — which is why small structures scatter to large angles and vice versa.

### Q1.3
Different facilities deliver vastly different beam intensities. Knowing the typical ordering helps you choose an instrument and estimate measurement times.

**Which list orders these sources from lowest to highest typical beam flux/intensity on the sample?**

- A. In-house X-ray → Neutron source → Synchrotron → X-ray FEL (laser) **(correct)**
- B. Neutron source → In-house X-ray → Synchrotron → X-ray FEL (laser)
- C. In-house X-ray → Synchrotron → Neutron source → X-ray FEL (laser)
- D. Synchrotron → In-house X-ray → X-ray FEL (laser) → Neutron source

*Why:* Laboratory X-ray tubes deliver the lowest flux. Large neutron facilities (reactors/spallation) provide much more flux than lab sources but generally less than synchrotron X-ray beamlines for comparable experiments. Synchrotrons are far brighter than lab tubes; X-ray free-electron lasers (XFELs) reach the highest peak flux of all.

---

## Topic 2 — Large-Scale Facilities (Synchrotrons, Reactors & Spallation Sources)

### Q2.1
Free neutrons do not exist in a bottle on the shelf — they must be liberated from nuclei. The two main production routes behave very differently.

**What fundamentally distinguishes a spallation neutron source (e.g. ESS) from a fission reactor (e.g. ILL)?**

- A. Spallation fires high-energy protons at a heavy-metal target to knock neutrons out of nuclei **(correct)**
- B. Spallation relies on a sustained nuclear chain reaction
- C. Spallation produces neutrons through chemical reactions
- D. Spallation uses lasers to generate neutrons

*Why:* In spallation, a high-energy proton beam hits a heavy target (e.g. tungsten/mercury) and "spalls" neutrons from the nuclei. A reactor instead uses a self-sustaining fission chain reaction. Spallation has no chain reaction, so it can be switched off instantly and produces fewer long-lived radioactive byproducts.

### Q2.2
Fast neutrons from fission or spallation are too energetic for most scattering experiments. Facility design must slow them down before they reach the instruments.

**What is the primary purpose of a moderator at a large-scale neutron source?**

- A. To slow (thermalise) fast neutrons to usable energies **(correct)**
- B. To increase the number of protons in the beam
- C. To focus neutrons onto the sample
- D. To detect neutrons after scattering

*Why:* Moderators (e.g. water or liquid hydrogen) slow fast neutrons through collisions until they reach thermal or cold energies. These energies match typical inter-atomic distances and excitations in samples — which is why moderated neutrons are used in diffraction and spectroscopy.

### Q2.3
A synchrotron is far more than a big X-ray tube. Its defining quality is *brilliance* — many photons, in a narrow, parallel, well-defined beam.

**Why do synchrotron sources provide higher resolution and faster experiments than conventional laboratory X-ray tubes?**

- A. They produce highly collimated and very intense (brilliant) beams **(correct)**
- B. They operate at room temperature
- C. They use visible light instead of X-rays
- D. They focus the beam using magnetic monopoles

*Why:* Electrons circulating near light speed and bent by magnets emit extremely intense, collimated, tunable X-rays. High brilliance means more signal in less time and finer spatial/energy resolution than a lab tube.

---

## Topic 3 — X-ray & Neutron Interactions with Matter

### Q3.1
X-rays and neutrons "see" matter through completely different physics, and that difference is the whole reason we use both.

**A key advantage of neutron diffraction over X-ray diffraction is that neutrons:**

- A. Can detect and locate light elements such as hydrogen **(correct)**
- B. Interact strongly with the electron cloud
- C. Are cheaper to produce
- D. Only image the sample surface

*Why:* X-rays scatter from electrons, so the signal grows with atomic number Z and light atoms (H, Li) are nearly invisible. Neutrons scatter from nuclei, with a scattering length that does *not* scale with Z, so hydrogen and other light atoms scatter strongly and can be located.

### Q3.2
Before any data analysis, we need a single number that tells us how "visible" an atom is to the beam. That number is the cross-section.

**In a scattering experiment, what does the "cross-section" represent?**

- A. The probability (likelihood) that a scattering event occurs **(correct)**
- B. The physical size of the detector
- C. The wavelength of the beam
- D. The scattering angle

*Why:* The cross-section σ has units of area and quantifies the probability of an interaction (scattering or absorption). For a single nucleus it relates to the scattering length b via σ = 4πb².

### Q3.3
Neutrons can pass through centimetres of metal yet be stopped by a thin sheet of plastic — a behaviour that follows directly from how they interact.

**Neutrons are highly penetrating in most materials because they:**

- A. Are uncharged and interact only via the short-range nuclear force (and magnetic moments) **(correct)**
- B. Interact strongly with the electron cloud of every atom
- C. Carry a positive charge that repels nuclei
- D. Are absorbed equally strongly by every nucleus

*Why:* Having no charge, neutrons ignore the electron clouds and electrostatic fields that stop electrons and attenuate X-rays. They only interact with the tiny nucleus (and with magnetic moments), so they penetrate deeply — making them a true bulk probe.

---

## Topic 4 — Diffraction (Bragg's Law, Crystallography & Powder Diffraction)

### Q4.1
Diffraction turns a crystal into a natural ruler. Bragg's law, nλ = 2d sinθ, ties the measured angle to a distance inside the crystal.

**In Bragg's law, nλ = 2d sinθ, the symbol d represents:**

- A. The interplanar spacing in the crystal **(correct)**
- B. The wavelength of the radiation
- C. The angle of incidence
- D. The sample-to-detector distance

*Why:* d is the spacing between parallel lattice planes. Constructive interference occurs when the path difference 2d sinθ equals a whole number of wavelengths, so measuring θ for a known λ gives d.

### Q4.2
Crystals are classified by the symmetry of their repeating unit. Knowing how many distinct categories exist is a basic piece of crystallographic literacy.

**How many crystal systems exist in 3-dimensional space?**

- A. 7 **(correct)**
- B. 5
- C. 14
- D. 3

*Why:* There are 7 crystal systems (triclinic, monoclinic, orthorhombic, tetragonal, trigonal, hexagonal, cubic). Adding centring gives the 14 Bravais lattices — a common distractor.

### Q4.3
Most real samples are powders, not single crystals. Powder diffraction is one of the workhorse techniques at large facilities.

**A primary application of X-ray (or neutron) powder diffraction is:**

- A. Phase identification and crystal-structure refinement (e.g. Rietveld) **(correct)**
- B. Measuring the sample temperature
- C. Measuring electrical conductivity
- D. Imaging soft tissue

*Why:* Each crystalline phase gives a characteristic set of Bragg peaks — a "fingerprint" — allowing phase identification, and quantitative Rietveld refinement of the full pattern yields lattice parameters and atomic positions.

---

## Topic 5 — Small-Angle Scattering (SAXS / SANS)

### Q5.1
Small-angle scattering probes sizes of ~1–100 nm. A simple plot of the low-angle data gives the single most useful size parameter.

**What does a Guinier plot allow you to determine in small-angle scattering?**

- A. The radius of gyration (overall particle size) **(correct)**
- B. The crystal symmetry
- C. The scattering length density of the solvent
- D. The beam wavelength

*Why:* In the low-Q (Guinier) region, ln I(Q) vs Q² is approximately linear, and its slope gives the radius of gyration R_g — a model-independent measure of the particle's overall size.

### Q5.2
At the other end of the scattering curve, the high-Q behaviour reports on the *interfaces* between phases.

**The Porod region/exponent (high-Q) is used to characterise:**

- A. The sharpness and area of interfaces (surface-to-volume ratio) **(correct)**
- B. The atomic number of the scatterers
- C. The beam energy
- D. The sample temperature

*Why:* At high Q the intensity follows a power law (Porod's law). For sharp, smooth interfaces I(Q) ∝ Q⁻⁴, and deviations reveal rough or fractal surfaces, giving information about boundary sharpness and surface area.

### Q5.3
SANS has a unique trick that SAXS does not: you can change what the experiment "sees" without changing the sample's chemistry at all.

**In SANS, how can you change the contrast of a hydrogen-containing sample without altering its chemistry?**

- A. By deuteration / adjusting the H₂O:D₂O solvent ratio **(correct)**
- B. By increasing the beam intensity
- C. By raising the sample temperature
- D. By moving the detector

*Why:* Hydrogen and deuterium have very different neutron scattering lengths (b_H is negative, b_D is positive). Swapping H for D, or mixing H₂O and D₂O, tunes the scattering-length density and can highlight or "match out" specific components.

---

## Topic 6 — Inelastic Scattering & Spectroscopy (Dynamics)

### Q6.1
Scattering experiments split into two families depending on whether the probe gives up energy to the sample. This single distinction decides what physics you can measure.

**Which statement correctly describes inelastic scattering?**

- A. Energy (and momentum) is exchanged, so the incident and scattered wavelengths differ **(correct)**
- B. No energy is exchanged and the wavelength is unchanged
- C. The beam only changes direction, never energy
- D. It can only occur with X-rays, never neutrons

*Why:* In inelastic scattering the neutron/photon exchanges energy with excitations in the sample (e.g. phonons), so its wavelength/energy changes. Elastic scattering (diffraction) conserves energy and keeps the wavelength fixed.

### Q6.2
A special, very small energy transfer regime around the elastic line carries information about slow motions.

**Quasi-elastic neutron scattering (QENS) is mainly used to study:**

- A. Molecular dynamics and diffusion **(correct)**
- B. Crystal structures
- C. Magnetic field strength
- D. Sample temperature only

*Why:* QENS measures the small energy broadening of the elastic line caused by diffusive/relaxational motions, giving timescales and geometries of molecular diffusion and reorientation.

### Q6.3
Whether scattering is *coherent* or *incoherent* determines whether you learn about how atoms move together or move individually.

**Coherent inelastic neutron scattering primarily reveals:**

- A. Collective excitations such as phonons (correlated atomic motion) **(correct)**
- B. Independent single-atom diffusion
- C. The detector's energy resolution
- D. The beam wavelength

*Why:* Coherent scattering preserves interference between atoms, so it probes *correlated* motion — collective modes like phonons and magnons. Incoherent scattering, by contrast, reports on single-particle (self) motion.

---

## Topic 7 — X-ray & Neutron Imaging and Tomography

### Q7.1
Radiography and tomography rely on the Beer–Lambert law, which says how much beam survives passage through a material. Knowing what the attenuation depends on is essential.

**According to the Beer–Lambert law, which factor does NOT significantly affect X-ray attenuation?**

- A. Sample temperature **(correct)**
- B. Material density (ρ)
- C. Atomic number (Z)
- D. Beam energy

*Why:* X-ray attenuation depends on the material (density and atomic number) and the photon energy. Ordinary temperature changes do not meaningfully change the attenuation coefficient, so temperature is the odd one out.

### Q7.2
Tomographic reconstructions are full of tell-tale artefacts. Recognising a ring artefact and its cause is a practical skill for anyone analysing CT data.

**Concentric ring artefacts in tomographic reconstructions are typically caused by:**

- A. Inhomogeneous or defective detector-pixel response (a consistent error at every angle) **(correct)**
- B. The sample being too cold
- C. Using too many projection angles
- D. The Fourier transform itself

*Why:* If a detector pixel responds incorrectly, it introduces the same error in every projection angle. When back-projected, that constant angular error maps to a perfect circle/ring in the reconstructed slice.

### Q7.3
Turning a stack of 2-D projection images (a sinogram) into a 3-D volume requires a specific mathematical operation.

**Tomographic reconstruction from projections to a volume is performed using:**

- A. Filtered back-projection / the inverse Radon transform **(correct)**
- B. Bragg's law
- C. The Stokes–Einstein equation
- D. A Guinier plot

*Why:* The set of projections is the Radon transform of the object. Reconstruction inverts it — classically via filtered back-projection: Fourier-transform each projection, apply a ramp filter, inverse-transform, and sum over all angles.

---

## Topic 8 — MRI & Diffusion Imaging (Bioimaging)

### Q8.1
MRI contrast comes from two distinct relaxation processes. Telling T1 from T2 by their underlying physics is fundamental to reading MR images.

**T2 relaxation in MRI reflects the loss of transverse magnetisation caused by:**

- A. Spin–spin interactions **(correct)**
- B. Spin–lattice interactions
- C. The magnetic field strength alone
- D. Proton density only

*Why:* T2 (transverse) relaxation is driven by spin–spin interactions that dephase the precessing spins. T1 (longitudinal) recovery is instead a spin–lattice process, where energy is exchanged with the surroundings.

### Q8.2
Diffusion MRI adds sensitivity to microscopic water motion. A single scan parameter sets how strongly the signal is weighted by diffusion.

**In diffusion MRI, the b-value controls:**

- A. The degree of diffusion weighting **(correct)**
- B. The image spatial resolution
- C. The magnetic field strength
- D. The signal-to-noise ratio directly

*Why:* The b-value (b = q²·t_d) combines gradient strength, duration and timing. A higher b-value makes the signal decay more strongly with diffusion, S = S₀·exp(−b·D), so it sets how sensitive the scan is to water displacement.

### Q8.3
The very first step of any MRI measurement is making the proton spins precess at a known frequency, set by a simple relation.

**The Larmor (resonance) frequency in MRI, f₀ = γ·B₀, means that it:**

- A. Increases proportionally with the static magnetic field strength B₀ **(correct)**
- B. Is independent of the magnetic field
- C. Decreases as the field gets stronger
- D. Depends only on temperature

*Why:* With the gyromagnetic ratio for ¹H γ ≈ 42.58 MHz/T, f₀ scales linearly with B₀ (e.g. ~298 MHz at 7 T). Higher fields give higher frequencies and more signal, which is why MRI keeps pushing to stronger magnets.

---

## Topic 9 — Radiation Safety, Detectors & Activation

### Q9.1
A common misconception is that uncharged particles are harmless. Neutrons are firmly classified as ionizing radiation, for a subtle reason.

**Although neutrons carry no charge, they are classified as ionizing radiation because they:**

- A. Trigger nuclear reactions and recoils that release charged particles and gamma rays **(correct)**
- B. Directly strip electrons from atoms with their charge
- C. Carry a small positive charge
- D. Emit visible light as they travel

*Why:* Neutrons themselves don't ionize directly, but they are captured by or recoil off nuclei, producing charged particles, recoil nuclei and gamma rays — secondary radiation that *does* ionize. Hence neutrons are ionizing radiation.

### Q9.2
Detecting a slow neutron is harder than it sounds, because it leaves no direct electrical trace.

**Slow (thermal) neutrons cannot be detected directly; detectors instead:**

- A. Use nuclear reactions (e.g. in ³He, ⁶Li, ¹⁰B) to convert neutrons into detectable charged particles **(correct)**
- B. Measure the neutron's electric charge
- C. Measure the visible glow of the neutron itself
- D. Weigh the neutron on a microbalance

*Why:* Because they are neutral and slow, neutrons produce no ionization on their own. Detectors use converter nuclei (³He, ⁶Li, ¹⁰B, Gd) whose neutron-capture reactions emit charged particles, which are then registered by gas, scintillation or semiconductor detectors.

### Q9.3
Choosing a spallation source over a reactor is partly a safety and environmental decision for the host region.

**Why does a spallation source generally pose a lower long-term ionizing-radiation risk to its surroundings than a fission reactor?**

- A. It has no sustained chain reaction and produces fewer long-lived radioactive byproducts **(correct)**
- B. It uses enriched uranium fuel
- C. It produces no neutrons at all
- D. It operates entirely without shielding

*Why:* A spallation source only produces neutrons while the proton accelerator is on and has no critical, self-sustaining chain reaction. It generates fewer long-lived fission products, lowering the long-term activation and radioactive-waste risk for the host environment (e.g. Lund).

---

## PART B — MULTIPLE CORRECT ANSWERS

*Two or more options may be correct. Select all that apply.*

---

### B1 — Mathematical Foundations
Vectors and Fourier transforms appear throughout scattering — from beam geometry to interpreting a diffraction pattern.

**Which of the following statements are correct?**

- A. A vector has both magnitude and direction **(correct)**
- B. A scalar is defined by both magnitude and direction
- C. Temperature is a typical vector quantity in scattering experiments
- D. A Fourier transform links a real-space structure to its scattering pattern **(correct)**

*Why:* A and D are foundational ideas used in every scattering experiment. B is false — a scalar has magnitude only. C is false — temperature is a scalar, not a vector.

### B2 — Large-Scale Facilities
Facilities differ in how they make the beam and how users get access.

**Which statements about large-scale facilities are correct?**

- A. Synchrotrons produce highly collimated, intense (brilliant) X-ray beams **(correct)**
- B. Spallation sources use high-energy proton bombardment of a heavy-metal target **(correct)**
- C. Beamtime is normally requested through a short proposal, reviewed roughly twice a year **(correct)**
- D. Reactors generate neutrons through chemical reactions

*Why:* A, B and C describe how these facilities work and how access is granted. D is false — reactors produce neutrons by nuclear fission, not chemistry.

### B3 — X-ray & Neutron Interactions
Neutrons and X-rays are genuinely different probes, and the differences are exploited deliberately.

**Which statements about neutrons and X-rays are correct?**

- A. The neutron has mass; the X-ray photon is effectively massless **(correct)**
- B. The neutron has a magnetic moment and can scatter from magnetic structures **(correct)**
- C. Neutrons interact mainly with nuclei (and magnetic moments); X-rays interact mainly with electrons **(correct)**
- D. Both the neutron and the X-ray photon are electrically neutral **(correct)**

*Why:* All four are correct. A–C describe key differences that make the probes complementary; D is a shared property (both are neutral) that is important when comparing them to charged particles.

### B4 — Diffraction
Getting clean diffraction data is as much about practical care as about physics.

**Which of the following are genuine challenges/considerations in diffraction experiments?**

- A. Sample preparation and purity **(correct)**
- B. Detector calibration **(correct)**
- C. Bragg's law is independent of the wavelength of the radiation used
- D. The need to deuterate every X-ray sample

*Why:* A and B are standard experimental challenges every diffractionist faces. C is false — Bragg's law explicitly involves wavelength (nλ = 2d sin θ). D is false — deuteration is a neutron (SANS) contrast tool, not a routine X-ray diffraction requirement.

### B5 — Small-Angle Scattering
Small-angle intensity depends on several physical and instrumental factors.

**Which factors influence the measured intensity/contrast in small-angle scattering?**

- A. The scattering-length-density distribution **(correct)**
- B. The contrast between the phases **(correct)**
- C. The instrument resolution **(correct)**
- D. Isotopic substitution (e.g. H/D) can change neutron contrast **(correct)**

*Why:* All four are correct. A–C shape the signal directly; D is a practical contrast tool widely used in neutron SANS (and irrelevant to most X-ray work — which is why deuteration appears as a distractor elsewhere).

### B6 — Inelastic Scattering & Spectroscopy
Time-of-flight (TOF) spectrometers are a major way to measure dynamics.

**Which of the following are advantages of time-of-flight (TOF) spectrometers?**

- A. They can avoid using both a monochromator and an analyser **(correct)**
- B. They give access to wide regions of (Q, ω) space **(correct)**
- C. They can be built in direct- or indirect-geometry configurations **(correct)**
- D. They are only suitable for purely elastic scattering

*Why:* A, B and C are real strengths of TOF instruments, which use neutron arrival time to encode energy. D is false — TOF is used precisely to measure *inelastic* (energy-changing) processes.

### B7 — Imaging & Tomography
Modern imaging beamlines offer several complementary contrast mechanisms.

**Which contrast mechanisms are available in X-ray and/or neutron imaging?**

- A. Attenuation (absorption) contrast **(correct)**
- B. Phase contrast **(correct)**
- C. All imaging methods require a fully monochromatic beam to produce any contrast
- D. Spin-polarisation contrast available for X-rays

*Why:* A and B are widely used for both X-rays and neutrons. C is false — broadband (white-beam) attenuation imaging is common. D is false — spin-polarisation imaging is a *neutron-only* contrast that exploits the neutron's magnetic moment.

### B8 — MRI & Diffusion Imaging
Diffusion MRI interprets water motion to infer tissue microstructure.

**Which statements about diffusion MRI are correct?**

- A. Free diffusion has an isotropic, Gaussian displacement distribution **(correct)**
- B. The b-value sets the amount of diffusion weighting **(correct)**
- C. Restricted diffusion along axons is anisotropic **(correct)**
- D. Diffusion tensor imaging (DTI) uses diffusion weighting along multiple directions **(correct)**

*Why:* All four are correct descriptions of diffusion behaviour, weighting and how anisotropy is mapped in practice.

### B9 — Radiation Safety, Detectors & Activation
Material choice and procedures keep neutron instruments safe and functional.

**Which of the following are appropriate for neutron detection and/or safety?**

- A. Boron and lithium are used for their high neutron-absorption cross-sections **(correct)**
- B. Cadmium is used for shielding because of its high neutron absorption **(correct)**
- C. Radiation monitoring and controlled-access zones are essential safety measures **(correct)**
- D. Nickel is an ideal neutron-*absorbing* detector material

*Why:* A, B and C are correct. D is false — nickel is prized for *reflecting/guiding* neutrons (neutron guides), not absorbing them; good absorbers are B, Li, Cd and Gd.
---

*End of quiz. See `index.html` in this folder for the interactive version.*

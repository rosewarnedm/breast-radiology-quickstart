---
layout: default
title: "Chapter 03: Image Quality and Technical Pitfalls"
nav_order: 3
---

> **⚠️ AI-generated content — requires human review.**
> This chapter was produced automatically by a large language model and has not been verified by a clinician. It may contain errors or omissions. Do not rely on it for clinical decisions until it has been reviewed and approved by a qualified specialist.

# Chapter 3: Image Quality and Technical Pitfalls

---

## Why image quality matters

Breast imaging is inherently a task of detecting subtle differences — in x-ray attenuation, acoustic impedance, or MRI enhancement — against a complex fibroglandular background. Small degradations in technique can therefore cause real harm: a smear of motion blur can obscure microcalcifications; a missed sliver of posterior tissue can hide an early cancer; a skin fold can masquerade as architectural distortion. These errors produce both false negatives (missed cancers) and false positives (unnecessary recalls and biopsies).

In the NHS Breast Screening Programme (NHSBSP), where asymptomatic women aged 50–70 are invited every three years for two-view mammography with double reading and arbitration, there is an additional demand: **consistency across rounds**. A lesion's significance often hinges on interval change, which requires that positioning and exposure be reproducible between appointments. In symptomatic clinics, image quality directly underpins triple assessment and the reliability of P/M/U/B scoring.

The goal of this chapter is transferable judgement: to understand *why* technical problems arise, to recognise when an appearance is artefactual rather than pathological, and to know how to correct or work around technical shortcomings.

---

## Foundations of image quality

### Contrast, resolution, and noise

Three properties determine whether a lesion is visible:

**Subject contrast** is the true physical difference between tissues — in x-ray attenuation, acoustic impedance, or MRI relaxation/diffusion behaviour. It is determined by breast composition, lesion histology, and imaging energy. In mammography, a low kilovoltage peak (kVp) with appropriate filtration maximises the photoelectric effect, which is what gives microcalcifications and soft-tissue interfaces their diagnostic contrast.

**Image contrast** is how effectively the imaging system conveys subject contrast to the displayed image. It is degraded by scatter (which adds a uniform background fog), by poor detector response, by inappropriate image processing, and in MRI by inadequate fat suppression or suboptimal sequence parameters.

**Spatial resolution** is the ability to distinguish adjacent fine structures — spicules, microcalcification morphology, ductal margins. It is governed by focal spot size and detector modulation transfer function in mammography, by transducer frequency and beam width in ultrasound, and by voxel dimensions and reconstruction algorithms in MRI and digital breast tomosynthesis (DBT).

**Noise** is the enemy of all three: random variation from quantum statistics, electronic sources, or ultrasound speckle that masks low-contrast structures. Critically, noise hides low-contrast lesions first — a subtle infiltrative carcinoma in a dense breast disappears into noise long before a dense calcification does.

A useful way to think about this: the detector quality (expressed as detective quantum efficiency, DQE) determines how efficiently dose is converted into useful signal. A high-DQE system delivers better signal-to-noise at a given dose; a low-DQE system wastes dose as noise. This is why modern flat-panel digital detectors have largely replaced screen-film and computed radiography systems in UK practice.

### Unsharpness

Blur degrades resolution and can smear or double structures:

- **Geometric unsharpness** arises from the finite size of the x-ray focal spot and the distance between the object and the detector. Magnification views therefore use a microfocus tube and an air gap to control penumbra.
- **Motion blur** smears fine detail — microcalcifications appear elongated, spicules blurred. It is caused by patient movement, inadequate compression in mammography, breathing or cardiac motion in MRI, and probe movement in ultrasound.
- **Reconstruction blur** in DBT and MRI: limited-angle tomography creates inherent out-of-plane blur whose extent depends on slice thickness and reconstruction algorithm. Understanding this helps explain why fine microcalcifications can appear less sharp on DBT than on conventional 2D.

---

## Mammography: positioning, compression, and exposure

### What the breast anatomy demands

The breast is a conical structure draped on a curved chest wall. To capture it diagnostically, every standard view must demonstrate:

- **Posterior tissue** to the pectoralis major muscle and retromammary fat plane
- **The inframammary fold (IMF)**, which marks the inferior limit of breast tissue
- **The axillary tail** superolaterally
- **The nipple–areolar complex**, ideally in profile on at least one view

Failure to include posterior tissue is one of the commonest causes of interval cancers — lesions that were present but outside the imaged field at the preceding screen.

### Standard views and adequacy in NHSBSP practice

Two views per breast are used in UK screening: the **craniocaudal (CC)** and the **mediolateral oblique (MLO)**. Adequacy is judged against NHSBSP guidance, though local thresholds vary slightly. The principles are:

**CC view:**
- The posterior nipple line (PNL — a perpendicular from the nipple to the pectoral margin) should be within a small margin of the MLO PNL, confirming comparable posterior inclusion
- Medial tissue should be included to the sternal edge
- Retromammary fat should be visible unless the breast is extremely dense
- Nipple ideally in profile; if not achievable on CC, it must be demonstrated on MLO
- The skin line should be continuous without major folds

**MLO view:**
- Pectoralis major should be visible as a convex anterior margin extending to or below nipple level
- The axillary tail should be included superiorly
- The IMF should be open and well demonstrated
- The PNL measured perpendicular to the pectoral muscle should approximate the CC PNL
- No breast sag; tissue should be elevated, not drooped; no major folds

Adequacy is not binary. The practical question is: *does this image contain sufficient diagnostic information, and can any shortcoming be corrected before the patient leaves?* Technical recall in screening — bringing a woman back for repeat imaging — should be reserved for cases that genuinely cannot be remedied on the day.

### Positioning technique

Good positioning requires understanding the anatomy rather than following a rigid protocol. Key principles:

**Patient set-up:**
- The inferior edge of the detector (image receptor) should align with the patient's IMF; adjust for height, kyphosis, and mobility.
- The MLO angle is adapted to body habitus — steeper (closer to lateral) for narrow-shouldered or slim patients; shallower for kyphosis or broad thorax — to align the pectoral muscle roughly parallel to the detector.

**Tissue mobilisation:**
- The "up-and-out" manoeuvre captures the axillary tail and lifts the inferior breast. Uniform tension across the breast before applying compression is essential: it separates tissue planes, reduces superimposition, reduces scatter by thinning the breast, and orientates Cooper's ligaments to sharpen architectural detail.
- A "camel-nose" deformity — an anterior bulge — signals uneven tension; correct before compressing.

**Nipple in profile:**
- A directional roll or slight rotation usually achieves this. Inverted nipples may not permit profile positioning; document this and ensure profile on the orthogonal view.

**IMF:**
- Ask the patient to push their hips towards the machine to open the fold. A clearly visible IMF confirms inclusion of inferior tissue.

**Challenging patients:**
- *Small breasts*: use smaller paddles; avoid excessive object-to-image distance; maintain posterior contact with the detector.
- *Large breasts*: consider supplementary exaggerated CC (XCCL/XCCM) views; consider two MLO exposures with arm repositioning.
- *Limited mobility or wheelchair users*: adapt receptor height and angle, accept positional compromises whilst prioritising posterior tissue, and document deviations clearly.

Consistent positioning between screening rounds is as important as single-episode adequacy. Reproducible technique allows genuine interval change to be distinguished from positional variation.

### Compression

Compression improves image quality and reduces dose simultaneously — it is not merely a patient discomfort issue. The mechanisms matter:

- Thinning the breast reduces scatter and lowers the mAs needed (hence dose)
- Reduced thickness stabilises the automatic exposure control (AEC)
- Spreading overlapping fibroglandular tissue unmasks lesions
- Breast immobilisation reduces motion blur

The target is firm, uniform compression — not "maximal" at all costs. Build tissue tension first, warm the paddles, explain the purpose, and coach breathing. Spot compression paddles are used diagnostically to locally separate overlapping tissue and assess whether a suspected lesion is real.

**Implants** require modified technique. Eklund (implant-displaced) views push the implant posteriorly against the chest wall whilst compressing the native anterior tissue separately. Not all implants are displaceable; document when they cannot be adequately displaced.

### Exposure and system factors

**X-ray spectrum:**
The choice of target/filter combination and kVp determines the energy spectrum reaching the breast. Low kVp maximises photoelectric contrast in soft tissue and calcifications; thicker or denser breasts require higher kVp to maintain penetration, trading some contrast for reduced noise at acceptable dose. Modern systems with automatic exposure control and optimisation algorithms handle much of this automatically, but understanding the trade-off prevents misattributing a noisy image to a system fault.

**AEC (automatic exposure control):**
The AEC chamber must be positioned under representative dense tissue — not over an implant, not over a cyst or lucent fatty region, not over air. Misplaced AEC is a frequent cause of under- or overexposure. For very fatty or very small breasts, manual techniques may be more consistent.

**Grid:**
Anti-scatter grids are used for standard 2D views. For magnification, the grid is removed and an air gap is used instead to limit scatter, which also reduces dose.

**Dose:**
Mean glandular dose is monitored under the NHSBSP QA framework. It must be kept as low as reasonably practicable (ALARP) while maintaining diagnostic image quality. Unexpectedly high doses or elevated retake rates should trigger equipment QA review and radiographer feedback.

### Tomosynthesis (DBT): strengths and new pitfalls

DBT acquires multiple low-dose projections over a limited arc and reconstructs thin slices, effectively removing the confounding effect of overlapping tissue. Understanding its specific characteristics prevents both over-reliance and under-use.

**Advantages:**
- Improves detection and characterisation of architectural distortion and mass margins by separating tissue planes
- Reduces recalls for summation shadows in screening, particularly in denser breasts

**Limitations and pitfalls:**
- **Microcalcifications**: fine calcifications may appear less sharp on DBT slices and on synthetic 2D images than on conventional 2D. Always obtain true 2D magnification views for calcification work-up — do not rely on DBT or synthetic 2D alone for morphology assessment.
- **Motion during the arc**: produces split or doubled structures across adjacent slices, simulating real lesions.
- **Metal objects**: biopsy clips, calcifications, and dense objects generate streak artefacts (sometimes described as "zebra striping") across slices, potentially mimicking or obscuring distortion.
- **Algorithm and slice thickness**: too thick a reconstruction hides fine detail; too thin amplifies noise. Be familiar with the settings used at your institution.
- **Positioning still matters**: inadequate posterior inclusion on DBT cannot be recovered in reconstruction. The same positioning standards apply.

**Synthetic 2D images** are reconstructed from the DBT data to reduce dose compared with acquiring both a full 2D and a DBT. They are a reasonable screening tool but differ from true 2D in calcification sharpness and edge definition. Know their limitations.

---

## Common mammographic artefacts and interpretive traps

Learning to recognise artefacts is as important as recognising pathology. The key question for every suspicious finding: *does this persist across projections and correlate across modalities, or does it disappear with a technical adjustment?*

### Skin-related artefacts

- **Skin folds** create linear or curvilinear opacities that can mimic spiculated masses or architectural distortion. The hallmark is a continuous skin-line visible at the edge of the fold. Correct with a roll manoeuvre and repeat the view.
- **Skin lesions** (seborrhoeic keratoses, naevi, moles) produce superficial dense opacities, sometimes with a lucent centre. **Always mark skin lesions with a radiopaque marker (BB)** at the time of acquisition — this converts a potential diagnostic problem into an unambiguous annotation.
- **Deodorant and talc** create superficial clusters of specks that can closely mimic microcalcifications, particularly skin-type calcifications. Pre-appointment instructions should advise avoidance; if doubt remains, repeat after skin cleaning or obtain tangential views.

### External objects

ECG leads, clothing fibres, hair braids, and jewellery all produce characteristic artefacts. A systematic room-preparation checklist before exposure eliminates most of these.

### Internal artefacts

- **Motion blur** elongates microcalcifications and blurs spicules. Look for double edges and inconsistent sharpness. The remedy is improved compression and instruction; in screening, this may require a repeat exposure.
- **Grid and detector artefacts**: periodic banding from grid malfunction, dead pixels, or detector non-uniformity cause fixed-pattern artefacts. These should be identified through routine QA before they affect clinical images, but recognise them and escalate promptly.

### Summation shadows

Superimposed normal fibroglandular tissue is one of the most common causes of recalled screening mammograms. Summation creates apparent masses, densities, and pseudo-distortion. The diagnostic approach:

1. Change the projection — rolled CC (medial or lateral roll), exaggerated CC (XCCL/XCCM), or spot compression
2. Apply spot compression to the area
3. If available, review DBT slices

**True lesions persist across projections; summation dissolves.** Genuine architectural distortion tends to persist and, importantly, will show correlating tethering on targeted ultrasound.

### Retroareolar pitfalls

Prominent lactiferous ducts and ductal ectasia can mimic a retroareolar mass. Confirm the skin–nipple connection and use targeted ultrasound in radial and anti-radial planes to characterise further.

### Posterior and inferior tissue

Missed tissue near the pectoral margin or inferior to the IMF is a disproportionately common location for interval cancers. Do not accept inadequate posterior coverage — supplement with additional views if needed.

---

## Ultrasound: optimisation and artefact management

### System set-up

**Transducer:** High-frequency linear probes (typically 9–18 MHz) provide the resolution needed for breast work. Use lower frequencies for deep tissue or large breasts; switch to a smaller footprint probe for nipple and superficial targets.

**Depth and focus:** Set depth to include the chest wall with a small margin below. Place focal zones at or just below the lesion. An image that does not reach the chest wall is incomplete.

**Gain and TGC (time-gain compensation):** Calibrate for homogeneous parenchymal echogenicity without saturating the noise floor. Too much gain obscures posterior acoustic features; too little exaggerates shadowing.

**Advanced modes:**
- *Tissue harmonic imaging* reduces clutter and side-lobe artefacts; use it routinely
- *Compound imaging* smooths speckle but can blunt margins and obscure micro-lobulation — switch off when assessing fine edge characteristics
- *Colour/power Doppler*: use low wall filters, appropriate pulse repetition frequency for slow flow, and minimal probe pressure; excess pressure collapses superficial vessels and eliminates signal

### Scanning strategy

Scan systematically in **radial and anti-radial planes** around the nipple, then in standard quadrant sweeps. Document every finding with:
- Clockface position
- Distance from nipple (cm)
- Depth (anterior, middle, or posterior third of breast parenchyma)
- Size in at least two planes

Always correlate with mammographic coordinates. If DBT is available, use tomographic depth cues to guide where to search on ultrasound.

### Ultrasound artefacts

**Anisotropy:** Ligaments, tendons, and fibrous tissue are angle-dependent reflectors — they appear falsely hypoechoic when insonated obliquely. Adjust probe angle to perpendicular. A hypoechoic area that resolves with angle correction is benign; persistent hypoechogenicity with spiculated margins that does not resolve is more suspicious.

**Posterior acoustic features:** Enhancement behind cysts or fatty lesions; shadowing behind dense calcifications or scirrhous tumours. These are useful but not reliable discriminators — many high-grade (grade 3) invasive cancers show posterior enhancement, not shadowing. Do not use posterior features alone to characterise lesions.

**Edge shadowing:** Smooth refraction artefacts at curved margins (for example, at the edges of a fibroadenoma) are symmetrical

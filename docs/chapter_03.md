---
layout: default
title: "Chapter 03: Image Quality and Technical Pitfalls"
nav_order: 3
---

> **⚠️ AI-generated content — requires human review.**
> This chapter was produced automatically by a large language model and has not been verified by a clinician. It may contain errors or omissions. Do not rely on it for clinical decisions until it has been reviewed and approved by a qualified specialist.

# Chapter 3: Image Quality and Technical Pitfalls

---

## Why Image Quality Matters

Breast imaging detects cancer by resolving subtle differences — a slight increase in attenuation, a faint spicule, a cluster of microcalcifications barely larger than noise. Any degradation in image quality narrows that margin. A missed sliver of posterior tissue, a skin fold misread as architectural distortion, or motion blur smearing a calcification cluster can convert a true positive into a false negative, or generate an unnecessary recall that erodes both programme efficiency and patient trust.

In the **NHS Breast Screening Programme (NHSBSP)**, asymptomatic women aged 50–70 are invited every three years for two-view mammography with double reading and arbitration. Here, consistency across screening rounds matters as much as single-episode adequacy: a lesion that was always present becomes conspicuous only if it is reliably included and rendered comparably each time. In symptomatic clinics, quality underpins the rigour of **triple assessment** and meaningful **P, M, U, and B scoring**.

As a core trainee, your role is not merely to read images but to recognise when an appearance is technical rather than pathological — and to know when the acquisition itself is too limited to support a confident diagnosis.

---

### Check your understanding

1. In the NHSBSP, women aged 50–70 are invited for two-view mammography with double reading and arbitration every three years.  *(True / False)*

2. A skin fold misread as architectural distortion is described in this section as a potential cause of a false negative result.  *(True / False)*

3. In symptomatic clinics, image quality underpins the rigour of triple assessment and meaningful P, M, U, and B scoring.  *(True / False)*

## Foundations of Image Quality

### Contrast, Resolution, and Noise

Think of these as three interdependent properties that determine whether a lesion is visible:

**Subject contrast** is the underlying difference in physical properties between lesion and background — X-ray attenuation, acoustic impedance, or MRI signal. It is determined by the biology of the tissue and cannot be manipulated directly; you work with it by choosing acquisition parameters that exploit it.

**Image contrast** is how faithfully the system transfers that subject contrast to the display. It is degraded by scatter, inappropriate processing, and poor sequence design.

**Spatial resolution** determines whether fine structures — spicules, microcalcification morphology, ductal margins — are resolved or blurred together. In mammography this is governed by focal spot size and detector characteristics; in ultrasound by transducer frequency and beam width; in MRI by voxel dimensions and reconstruction.

**Noise** is the enemy of low-contrast lesions. Quantum noise (mammography), speckle (ultrasound), and thermal/electronic noise (MRI) all create random variation that can mask subtle findings. Doubling dose roughly halves quantum noise, but dose must remain as low as reasonably practicable. The detector quantum efficiency (DQE) describes how efficiently a detector converts incident radiation into useful signal — a high-DQE detector delivers better signal-to-noise at a given dose.

In practice: when a lesion is borderline visible, ask yourself which of these three factors is limiting you, and whether a technical adjustment (different projection, higher-frequency transducer, magnification view) would genuinely help or simply add dose without gain.

### Unsharpness

Two forms matter clinically:

- **Geometric unsharpness** arises from the finite size of the focal spot and the distance between object and detector. Magnification views control this with a microfocus tube and an air gap.
- **Motion blur** smears edges and elongates calcifications, often producing a characteristic double-edge appearance. It is the commonest cause of failed magnification views and can compromise DBT sweeps.

Reconstruction techniques (tomosynthesis, MRI) add their own blur through slice thickness and algorithm choices — too thick hides fine detail, too thin amplifies noise.

---

### Check your understanding

1. A borderline visible lesion on mammography appears masked by grainy, random variation in the image background. Which property is most directly responsible for this limitation?
   - **A.** Poor subject contrast due to dense fibroglandular tissue
   - **B.** Geometric unsharpness from a large focal spot
   - **C.** Quantum noise reducing signal-to-noise ratio
   - **D.** Inappropriate image processing degrading image contrast
   - **E.** Motion blur from an extended exposure time

2. A magnification view is performed to assess microcalcification morphology, but the resultant image shows smeared edges and an apparent double-edge appearance to some calcifications. What is the most likely cause?
   - **A.** Excessive voxel dimensions reducing spatial resolution
   - **B.** Scatter degrading image contrast
   - **C.** A low detector quantum efficiency (DQE)
   - **D.** Patient or breast motion during the exposure
   - **E.** Inappropriate post-processing algorithm

3. When comparing two digital mammography detectors operating at the same radiation dose, which property best predicts which detector will produce the superior signal-to-noise ratio?
   - **A.** Focal spot size
   - **B.** Detector quantum efficiency (DQE)
   - **C.** Subject contrast of the imaged tissue
   - **D.** Beam width and transducer frequency
   - **E.** Reconstruction slice thickness

## Mammography: Positioning, Compression, and Exposure

![Patient positioned at the mammography unit]({{ '/docs/img/wikimedia_mammography_positioning.jpg' | relative_url }})

*Figure: Positioning and compression at the mammography unit; adequate compression and positioning are prerequisites for image quality. Bill Branson, National Cancer Institute (public domain), via Wikimedia Commons (https://commons.wikimedia.org/wiki/File:Mammography_patient.jpg). External teaching example — not independently verified against this text.*

### What You Are Trying to Include

The breast is a conical organ on a curved chest wall. Standard views must capture:

- **Posteriorly**: the pectoralis major and retromammary fat plane
- **Inferiorly**: the inframammary fold (IMF)
- **Superolaterally**: the axillary tail of Spence
- **Centrally**: the nipple–areolar complex, ideally in profile on at least one view

Missing posterior tissue is the single most consequential positioning failure. The posterior one-third of the breast, particularly the upper outer quadrant and the retroareolar deep tissue, is a common location for interval cancers detected between screening rounds.

### Standard Views and Adequacy Criteria

The NHSBSP mandates **craniocaudal (CC) and mediolateral oblique (MLO)** views per breast. Adequacy is assessed against national guidance — the following principles are consistent across UK centres, though precise thresholds may vary locally.

**CC view:**
- Posterior nipple line (PNL) should approximate the MLO PNL within a clinically acceptable margin
- Retromammary fat visible posteriorly (unless extremely dense tissue limits this)
- Medial tissue included — the medial border of the image should be at or slightly beyond the medial breast
- Nipple in profile where feasible
- Continuous skin line without major folds

**MLO view:**
- Pectoral muscle visible to or below nipple level, appearing convex anteriorly and tapering inferiorly
- Axillary tail included
- IMF open and visible — a closed IMF indicates inferior tissue is lost
- No breast sag; tissue elevated and supported
- PNL measured perpendicular to the pectoral muscle should approximate the CC PNL

Adequacy is not binary: ask whether the diagnostic information is sufficient for the clinical purpose, and whether shortcomings are correctable before the patient leaves. Technical recall in screening should be a last resort, not a default.

### Positioning Principles

**Receptor height**: Set the inferior edge of the detector at the IMF. Adjusting for kyphosis or restricted mobility may require significant modification — document this.

**MLO angle**: The angle must align the pectoral muscle parallel to the detector. A useful starting point is approximately 45–60° from horizontal, but this must be individualised — a broad-shouldered or kyphotic patient needs a shallower angle; a narrow-shouldered or tall patient may need a steeper one. An incorrect angle produces a foreshortened pectoral shadow or breast sag.

**Tissue mobilisation**: The defining manoeuvre is lifting and drawing the breast away from the chest wall — the "up-and-out" technique. This opens the axillary tail, separates tissue planes, and places Cooper's ligaments more perpendicular to the X-ray beam, improving depiction of architectural features. Uniform tension across the breast before compression prevents the "camel-nose" deformity (anterior bunching from uneven pull).

**The nipple**: A directional roll or slight rotation can bring a laterally or inferiorly displaced nipple into profile. If this is not achievable — for example with fixed inversion — document clearly and ensure profile is obtained on the orthogonal view.

**Challenging situations** (small breasts, large breasts, limited mobility, implants, post-surgical changes) require adaptation, not abandonment. For large breasts, supplementary views such as exaggerated CC lateral (XCCL) or medial (XCCM) may be needed. For wheelchair users, adapted receptor positioning and angle are essential. The principle in each case is the same: include as much tissue as possible while achieving adequate compression and stable exposure.

**Consistency across rounds**: A well-positioned screening mammogram from three years ago is your most useful comparison. Inconsistent positioning means you are comparing apples with oranges and undermines the purpose of interval change assessment.

### Compression

Adequate compression is transformative. It:

- **Thins the breast**, reducing scatter and lowering the required mAs
- **Limits motion** during exposure
- **Separates overlapping fibroglandular tissue**, unmasking hidden lesions
- **Stabilises tissue thickness**, improving AEC performance and dose efficiency

The goal is firm, uniform compression — not maximal. Build tension in the tissue before applying the paddle, explain the process, and coach the patient to breathe out and relax the shoulder. A well-positioned breast with good tension before compression needs less applied force to achieve an adequate result.

**Spot compression paddles** exploit the same principles focally, pushing overlapping tissue aside to clarify a suspected mass or area of distortion.

**Implants**: Use **Eklund (implant-displaced) views** wherever the implant is displaceable — pushing the implant posteriorly allows the anterior glandular tissue to be compressed and imaged more effectively. Not all implants are displaceable; document when this is the case and report the limitation.

### Exposure and System Factors

**Tube kilovoltage and filtration** are optimised to exploit the photoelectric effect in breast tissue, maximising contrast between glandular and fatty components, and between calcifications and soft tissue. Dense or thick breasts require higher kVp and different filtration to maintain penetration — this trades some contrast for manageable noise. Modern systems handle much of this automatically, but understanding the trade-off helps you recognise when exposure choices are suboptimal.

**Automatic exposure control (AEC)**: The ionisation chamber must be positioned beneath representative dense tissue — not over a cyst, implant, or air. Misplaced AEC chambers produce consistently under- or overexposed images that may not be obvious on casual inspection but degrade diagnostic information.

**Grids and scatter**: Anti-scatter grids are used for standard 2D views. For magnification views, the grid is removed and an air gap substitutes — the increased object-to-detector distance rejects scattered radiation geometrically.

**Dose**: Mean glandular dose (MGD) is monitored under NHSBSP QA and benchmarked against EUREF reference levels. Dose should be kept as low as reasonably practicable consistent with diagnostic adequacy — high repeat rates or unusual doses trigger equipment and technique review.

### Digital Breast Tomosynthesis (DBT)

DBT acquires multiple low-dose projections over a limited arc and reconstructs them into thin pseudo-3D slices. Its principal benefit is eliminating **tissue overlap**, the dominant cause of both false positives (summation shadows recalled unnecessarily) and false negatives (cancers hidden behind superimposed fibroglandular tissue). This makes it particularly useful in dense breasts and for characterising architectural distortion.

However, DBT introduces new pitfalls:

- **Microcalcification conspicuity**: Fine calcifications may appear less sharp on reconstructed DBT slices and on synthetic 2D images than on conventional 2D. Do not rely on DBT or synthetic 2D alone for calcification morphology assessment — **true 2D magnification views remain the standard**.
- **Motion during the sweep**: Patient movement during the arc creates "doubled" or "split" structures across slices. Coach the patient to hold still; consider breath-hold if feasible.
- **Metal and dense objects**: Biopsy clips, calcified fibroadenomas, and other dense structures generate out-of-plane streak artefacts that can obscure adjacent tissue or mimic distortion.
- **Positioning is not rescued by reconstruction**: Inadequate posterior coverage on the acquisition cannot be recovered computationally.

**Synthetic 2D** images are useful for dose reduction but differ from true 2D in calcification rendering and edge characteristics. Be alert to these differences, particularly when comparing with prior conventional 2D studies.

---

### Check your understanding

1. On a mediolateral oblique (MLO) mammogram, the inframammary fold appears closed and inferior breast tissue is absent. What is the most likely cause of this finding?
   - **A.** The AEC chamber was positioned over fatty tissue rather than dense tissue
   - **B.** The MLO angle was too steep for the patient's body habitus
   - **C.** The breast was not adequately lifted and supported during positioning
   - **D.** The receptor height was set too high, above the inframammary fold
   - **E.** Compression was applied before tissue mobilisation was complete

2. A patient with a displaceable silicone implant attends for screening mammography. Which technique should be used to maximise imaging of the anterior glandular tissue?
   - **A.** Spot compression views over the implant to thin it focally
   - **B.** Eklund (implant-displaced) views, pushing the implant posteriorly
   - **C.** Standard CC and MLO views with increased kVp to penetrate the implant
   - **D.** Magnification views with the grid removed to reduce scatter from the implant
   - **E.** Additional mediolateral views to image tissue lateral to the implant

3. A mammographer is reviewing digital breast tomosynthesis (DBT) images of a patient recalled for microcalcifications. What is the most important additional imaging step for definitive morphological assessment of the calcifications?
   - **A.** Increase the reconstruction slice thickness to improve calcification sharpness on DBT
   - **B.** Review the synthetic 2D images, as these replicate true 2D calcification rendering
   - **C.** Obtain true 2D magnification views, as DBT and synthetic 2D are insufficient for calcification morphology
   - **D.** Repeat the DBT acquisition with the patient coached to hold still to eliminate motion artefact
   - **E.** Apply spot compression on the DBT to reduce tissue overlap over the calcification cluster

## Common Mammographic Artefacts and Interpretive Traps

### Skin and Surface Artefacts

**Skin folds** are among the most common causes of unnecessary recall. They appear as curvilinear lines or apparent spiculation — but follow the skin surface contour and can be traced back to the skin edge. The corrective action is simple: reposition and repeat with the fold smoothed.

**Skin lesions** (seborrhoeic keratoses, moles, cutaneous haemangiomas) project as dense superficial opacities, sometimes with a lucent centre. Always mark known skin lesions with **radiopaque BBs** before acquisition. This converts a potential diagnostic dilemma into a trivial observation.

**Deodorant and talc** create irregular superficial specks mimicking microcalcifications. Pre-scan instructions should routinely ask patients to avoid powders on the day. If doubt remains despite history, tangential views with the suspicious area at the skin surface will confirm or refute a dermal location.

### External Objects

ECG leads, jewellery, hair braids, clothing texture, and oxygen tubing all cast artefacts. A brief systematic check before exposure prevents these entirely. They should never be the cause of a recall or an ambiguous report.

### Motion Blur

Look for **double edges**, inconsistent sharpness across the image, and elongated or smeared calcification morphology. Motion blur is usually evident on inspection — the parenchyma appears unsharp even where contrast is adequate. Repeat the exposure with coaching, ensuring compression is adequate and the patient is comfortable.

### Summation Shadows

Normal overlapping fibroglandular tissue can create apparent masses, focal densities, or pseudo-distortion that are entirely artefactual. These are one of the commonest sources of unnecessary recall in dense breasts.

The key diagnostic test is **changing the projection**: a rolled CC view, an XCCL, spot compression, or DBT will resolve a summation shadow — it disperses with any change in viewing angle. A true lesion persists. If an apparent mass or distortion dissolves on a supplementary view, no further action is needed. If it persists, treat it as real.

### Retroareolar Pitfalls

Prominent lactiferous sinuses or duct ectasia can project as apparent retroareolar masses. Use targeted ultrasound in radial and anti-radial planes, looking for the characteristic tubular continuity with the nipple, to distinguish duct ectasia from a discrete intraductal or periductal lesion.

### Posterior and Inferior Tissue

Missed posterior tissue near the pectoral margin and missed inferior tissue at the IMF are consistently over-represented in reviews of interval cancers. Where adequacy is borderline, use supplementary views rather than accepting the limitation. When reporting, if posterior tissue is absent and the clinical context warrants it, comment that the full extent of the breast is not included and additional imaging may be appropriate.

---

### Check your understanding

1. A patient is recalled following a screening mammogram showing an apparent focal density on the MLO view only. The density is not visible on the CC view. Which single action is most appropriate to determine whether this represents a true lesion?
   - **A.** Proceed directly to ultrasound-guided core biopsy
   - **B.** Obtain a rolled CC or XCCL view to change the projection angle
   - **C.** Repeat the standard MLO view with increased compression
   - **D.** Request MRI of the breast
   - **E.** Apply a radiopaque BB to the area and repeat the MLO

2. During a routine mammogram, a patient is noted to have worn deodorant. The images show irregular superficial specks that could represent microcalcifications. Which view should be obtained to confirm or refute a dermal location?
   - **A.** Magnification CC view
   - **B.** Lateral view with spot compression
   - **C.** Tangential view with the suspicious area at the skin surface
   - **D.** Rolled CC view
   - **E.** XCCL view

3. An apparent mass is seen in the retroareolar region on mammography. Which imaging approach does this section recommend to distinguish duct ectasia from a discrete intraductal or periductal lesion?
   - **A.** MRI with gadolinium contrast in the prone position
   - **B.** Spot compression magnification views in two projections
   - **C.** Galactography to opacify the ductal system
   - **D.** Targeted ultrasound in radial and anti-radial planes looking for tubular continuity with the nipple
   - **E.** DBT to assess tissue overlap in the subareolar region

## Ultrasound: Optimisation and Artefact Management

### System Set-up

**Transducer selection**: High-frequency linear probes (typically 10–18 MHz) for standard breast imaging. For deep lesions in large breasts, stepping down in frequency (9–12 MHz) improves penetration at the cost of some resolution. Use the highest frequency that provides adequate depth penetration for the target.

**Depth and focus**: Set depth to just include the chest wall with a margin. Position the focal zone at or just deep to the lesion. These two settings are among the commonest left at defaults — consciously adjusting them improves image quality measurably.

**Gain and TGC**: The aim is a homogeneous parenchymal background without noise saturation. Excessive gain exaggerates posterior acoustic enhancement and hides posterior shadowing; insufficient gain makes everything appear falsely hypoechoic.

**Tissue harmonic imaging**: Reduces clutter and side-lobe artefacts, improving margin assessment. Consider switching to fundamental mode if you are assessing fine margin detail — harmonics can slightly smooth micro-lobulation.

**Compound imaging**: Improves signal-to-noise and reduces speckle but may blunt fine margin detail. Adapt to the diagnostic question.

**Probe pressure**: Use the minimum pressure needed to maintain skin contact. Excessive pressure collapses compressible structures (cysts, small veins), flattens some masses, and eliminates Doppler signal in soft tissue vasculature. This is a common and correctable error.

### Scanning Strategy

Use **radial and anti-radial planes** centred on the nipple — these follow the natural ductal anatomy and improve detection of intraductal and periductal pathology. Supplement with standard quadrant sweeps. Document each lesion by **clockface position, distance from the nipple in centimetres, and depth** (anterior, middle, or posterior third of the parenchyma). This localisation framework integrates directly with mammographic coordinates and clinical findings, and is the basis for meaningful triple assessment correlation.

### Ultrasound Artefacts: Helpful and Harmful

**Anisotropy** is the angle-dependence of reflectivity in fibrous structures. Ligaments, scar tissue, and fat lobule borders can appear deceptively hypoechoic when the beam is not perpendicular to them. **Adjust insonation angle** — most anisotropic artefacts resolve within 10–15°. If hypoechogenicity with spiculated margins persists through angle adjustment, it is more likely pathological.

**Posterior acoustic features** — enhancement behind fluid-filled or fatty structures, shadowing behind calcifications or scirrhous tumours — are useful but not diagnostic. Critically, **many high-grade cancers show posterior enhancement** rather than shadowing, and some complex cysts shadow. Posterior features support interpretation but should not override margin and internal echo assessment.

**Edge shadowing**: Symmetrical, bilateral thin linear shadows at the lateral margins of a smoothly curved lesion (e.g. a fibroadenoma) are a refraction artefact. Irregular or asymmetric shadowing without a clear geometric explanation warrants scrutiny.

**Near-field clutter**: Very superficial lesions (<3–5 mm from skin) are often obscured. Use a standoff pad, thick gel, or a high-frequency transducer with a short focus.

**Side-lobe and grating-lobe artefacts**: Spurious echoes adjacent to strongly reflective structures. Harmonics substantially reduce these.

### Common Misses on Ultrasound

- **Isoechoic or infiltrative cancers**: These blend imperceptibly with normal parenchyma. Look instead for subtle architectural distortion, straightening of Cooper's ligaments, or asymmetric tissue stiffness (if elastography is available).
- **Deep and posterior lesions**: Set depth adequately. If a mammographic lesion is in the posterior third, you may need a lower-frequency probe or an off-angle approach past the glandular parenchyma.
- **Retroareolar masses**: Always scan in radial planes; an abrupt ductal cut-off, internal vascularity, or solid component within a dilated duct should not be dismissed as simple ectasia.
- **Cannot find the mammographic lesion**: Revisit the mammographic localisation. Use DBT slice depth as a guide to US depth. Alter insonation angle and probe pressure. Scan wider. Ask a colleague. If a real mammographic lesion cannot be found on diligent targeted US, do not dismiss it — it may be isoechoic, and MRI should be considered in the symptomatic context.

---

### Check your understanding

1. During breast ultrasound of a 3 mm superficial lesion just beneath the skin surface, the structure is poorly visualised due to near-field clutter. Which of the following is the most appropriate corrective action?
   - **A.** Reduce the transducer frequency to improve penetration
   - **B.** Increase the overall gain to bring the lesion into view
   - **C.** Use a standoff pad, thick gel, or a high-frequency transducer with a short focus
   - **D.** Switch to compound imaging to reduce speckle
   - **E.** Reposition the focal zone to the chest wall

2. A radiographer is scanning a smoothly contoured fibroadenoma and notes symmetrical thin linear shadows arising from both lateral margins. What is the correct interpretation of this finding?
   - **A.** Posterior acoustic shadowing consistent with a scirrhous tumour
   - **B.** A refraction artefact called edge shadowing, expected for a smoothly curved lesion
   - **C.** Side-lobe artefact that can be reduced by switching to fundamental imaging mode
   - **D.** Anisotropy that will resolve with a 10–15° change in insonation angle
   - **E.** Posterior acoustic enhancement indicating a fluid-filled structure

3. A breast ultrasound reveals a lesion with a hypoechoic, apparently spiculated appearance. The radiographer suspects anisotropy. What is the recommended first step, and what finding would suggest the lesion is more likely pathological?
   - **A.** Increase probe pressure to improve contact; resolution of spiculation confirms pathology
   - **B.** Switch to tissue harmonic imaging; persistence of enhancement indicates malignancy
   - **C.** Adjust the insonation angle by 10–15°; persistence of hypoechogenicity and spiculated margins through angle change suggests pathology
   - **D.** Reduce transducer frequency to 9 MHz; lesion enlargement on lower frequency confirms pathology
   - **E.** Apply colour Doppler; absence of vascularity confirms the finding is artefactual

## MRI: Acquisition Quality and Interpretive Traps

### Positioning and Coverage

Patients are imaged **prone** in a dedicated bilateral breast coil. The breast should be centred within the coil with sufficient support to minimise motion whilst avoiding compression that could reduce perfusion. Coverage must encompass the entire breast volume, pectoralis, axillary tail, and enough axilla for nodal assessment. Field-of-view trade-offs affect in-plane resolution — balance these against the diagnostic requirement.

### Sequence Optimisation

**Dynamic contrast-enhanced (DCE) MRI** requires both adequate spatial resolution (to assess morphology) and adequate temporal resolution (to characterise kinetic curves). The two are in tension. Consistent bolus timing and injection rate are critical — a delayed or slow injection blunts the early post-contrast phase and distorts kinetic analysis, potentially converting a type III curve into a type II. Use a power injector where available.

**Fat suppression** is the single most important quality determinant for lesion conspicuity. Non-uniform fat suppression causes regional shading that can mask non-mass enhancement (NME) or produce false enhancement. At 3T and in large or asymmetric breasts, B₀/B₁ inhomogeneity is a particular challenge — **Dixon-based methods** (e.g. IDEAL, DIXON) are more robust than frequency-selective fat sat in these situations, and dielectric pads or shimming can help.

**Diffusion-weighted imaging (DWI)**: Choose b-values (typically 0 and 800–1000 s/mm²) that suppress perfusion without excessive signal loss. Confirm apparent diffusion coefficient (ADC) values on maps rather than source images alone — **T2 shine-through** can make benign cysts appear as apparent diffusion restriction on DWI if maps are not reviewed.

### Artefacts and Pitfalls

**Motion**: Ghosting from respiratory or cardiac motion, and patient movement, are the most common causes of non-diagnostic MRI. Educate patients thoroughly, consider motion correction sequences, and repeat acquisitions if early phases are degraded — the early post-contrast phase is the most diagnostically critical and cannot be recovered.

**Chemical shift and Gibbs ringing**: Create boundary artefacts at fat–water interfaces. Increasing bandwidth or voxel size relative to the target structure mitigates these.

**Susceptibility artefacts**: Biopsy clips, titanium markers, and dense calcifications cause signal voids and local geometric distortion. Recognise these from their morphology and correlation with the mammographic clip position — do not misattribute susceptibility voids to necrosis.

**Background parenchymal enhancement (BPE)**: Varies with hormonal status and is highest in the luteal phase. High BPE reduces specificity — NME in particular can be difficult to distinguish from normal hormonally driven enhancement. Where clinically feasible, schedule breast MRI in the second week of the cycle. Interpret NME in the context of BPE grade, morphology, and kinetics, not enhancement alone.

**Implants**: Use silicone-specific sequences (e.g. STIR-based silicone-selective imaging) for rupture assessment. Radial folds of the implant shell are normal and may mimic intracapsular rupture — evaluate in orthogonal planes and ensure fold continuity. Motion can create linear artefacts resembling the "linguine sign" of intracapsular rupture; assess on multiple sequences.

---

### Check your understanding

1. A breast MRI examination performed at 3T in a patient with large, asymmetric breasts shows regional areas of incomplete fat suppression, masking possible non-mass enhancement on the subtracted images. Which fat suppression technique is most likely to be robust in this situation?
   - **A.** Frequency-selective fat saturation (CHESS)
   - **B.** Dixon-based method (e.g. IDEAL or DIXON)
   - **C.** Short-tau inversion recovery (STIR) for the DCE sequence
   - **D.** Increasing the repetition time to allow full fat relaxation
   - **E.** Applying a surface coil with a narrower field of view

2. On a breast DWI sequence, a round lesion appears bright on the high-b-value image, suggesting restricted diffusion. The radiographer reports it as suspicious. Which additional step does the section specifically recommend to avoid a diagnostic error in this scenario?
   - **A.** Repeat the DWI acquisition with a lower b-value to confirm signal persistence
   - **B.** Correlate with the early post-contrast phase subtraction images only
   - **C.** Review the ADC map to exclude T2 shine-through
   - **D.** Increase the b-value to 1500 s/mm² to suppress all T2 signal
   - **E.** Dismiss DWI findings and rely on DCE morphology alone

3. During reporting of a breast MRI in a patient with a biopsy clip in situ, a small signal void with local geometric distortion is identified adjacent to the known clip site. What is the most appropriate interpretation of this finding?
   - **A.** Necrosis within a tumour at the clip site
   - **B.** Intracapsular implant rupture
   - **C.** Susceptibility artefact from the biopsy clip, correlated with mammographic clip position
   - **D.** Chemical shift artefact requiring bandwidth adjustment
   - **E.** Gibbs ringing at a fat–water interface

## Modality Correlation and Diagnostic Judgement

Technical excellence in each modality is a prerequisite for meaningful cross-modality correlation. In UK practice, this correlation is the foundation of both triple assessment and screening arbitration.

**Mammography to ultrasound**: Map findings using a consistent lexicon — clockface, nipple distance, depth category, and quadrant. DBT slice number and reconstructed depth provide a useful guide to predicted US depth. Remember that "posterior" on mammography corresponds to the deepest tissue on ultrasound.

**Architectural distortion on mammography**: Always warrants a careful targeted ultrasound. If US reveals subtle tethering or a hypoechoic area at the corresponding site, targeted biopsy is straightforward. If US is negative despite optimal technique, do not dismiss the mammographic finding — DBT-guided or stereotactic biopsy is appropriate.

**Microcalcifications**: Ultrasound rarely adds diagnostic value for calcification morphology. Characterise with **2D magnification mammography**; DBT and synthetic 2D are supplementary, not substitutes. If tissue sampling is required, stereotactic biopsy under mammographic guidance is the standard approach.

**MRI-detected lesions**: Proceed to **targeted second-look ultrasound** before considering MR-guided biopsy. If a correlate is found on US — even subtle — US-guided biopsy is simpler, cheaper, and repeatable. If diligent second-look US is negative, MR-guided biopsy is appropriate for lesions warranting tissue diagnosis.

In the **screening context**, the threshold for additional investigation must account for the asymptomatic population: most recalled women will not have cancer, and the harm of unnecessary investigation must be weighed against the benefit of early detection. In **symptomatic triple assessment**, the threshold shifts — a U3 or U4 ultrasound finding that correlates with an M3 mammogram warrants biopsy even without MRI, because B scoring from core biopsy directly informs MDT management.

---

### Check your understanding

1. A woman is recalled from screening with architectural distortion on mammography. Targeted ultrasound is performed with optimal technique but no correlate is identified. What is the most appropriate next step?
   - **A.** Reassure and return to routine screening
   - **B.** Repeat ultrasound in six months
   - **C.** Proceed to MR-guided biopsy
   - **D.** Perform DBT-guided or stereotactic biopsy
   - **E.** Repeat mammography in three months

2. A symptomatic patient has a U3 ultrasound finding that correlates with an M3 mammogram. MRI has not been performed. What is the most appropriate management?
   - **A.** Arrange MRI before any biopsy decision
   - **B.** Perform core biopsy, as B scoring directly informs MDT management
   - **C.** Repeat imaging in six weeks to reassess
   - **D.** Discharge with safety-netting as neither finding is suspicious
   - **E.** Proceed to excision biopsy without prior core biopsy

3. An MRI detects a lesion in a patient undergoing staging. No correlate was identified at the time of MRI. What is the correct sequence of further investigation?
   - **A.** Proceed directly to MR-guided biopsy to avoid delay
   - **B.** Perform supplemental DBT to characterise the lesion before biopsy
   - **C.** Perform targeted second-look ultrasound; if a correlate is found, use US-guided biopsy
   - **D.** Perform magnification mammography to assess for associated calcification before biopsy
   - **E.** Repeat MRI in three months to confirm persistence before biopsy

## Technical Pitfalls: False Negatives and False Positives

### Sources of False Negatives

| Pitfall | Mechanism | Correction |
|---|---|---|
| Inadequate posterior inclusion | Tissue at the pectoral margin not visualised | Adjust MLO angle; lift IMF; supplementary views |
| Closed IMF/breast sag | Inferior tissue lost | Elevate breast; open fold; re-expose |
| Motion blur | Calcifications smeared; spicules lost | Re-expose with coaching and adequate compression |
| Inadequate compression | Tissue overlap masks lesions | Build tension first; coaching |
| US depth too shallow | Deep lesions not imaged | Set depth to chest wall |
| MRI fat-sat failure | NME masked by residual fat signal | Switch to Dixon method; replan shim |

### Sources of False Positives

| Pitfall | Mechanism | Resolution |
|---|---|---|
| Skin folds | Linear/curvilinear opacity mimicking distortion | Change projection; reposition |
| Deodorant/talc | Superficial specks mimicking calcifications | Tangential view confirms dermal location |
| Summation shadows | Superimposed tissue creates pseudo-mass/distortion | Resolves on rolled view, spot compression, or DBT |
| Anisotropy on US | Fibrous structure appears hypoechoic | Adjust insonation angle |
| High BPE on MRI | Clumped NME from hormonal background | Contextualise with menstrual timing and kinetics |

For any equivocal finding, apply the same mental framework: **does it persist across projections or angles? Does it correlate across modalities? Can a technical adjustment make it disappear or become definite?** A lesion that dissolves with any technical modification was almost certainly never real.

---

### Check your understanding

1. A patient returns for assessment of apparent fine calcifications seen on screening mammography. A tangential view demonstrates that the specks lie within the skin. What was the most likely source of the false-positive finding?
   - **A.** Summation shadow from superimposed fibroglandular tissue
   - **B.** Motion blur during the original exposure
   - **C.** Deodorant or talc on the skin surface
   - **D.** Skin fold creating a curvilinear opacity
   - **E.** Inadequate compression causing tissue overlap

2. On ultrasound, a radiographer identifies a hypoechoic area within fibrous breast tissue that raises concern for a solid lesion. After adjusting the transducer angle, the finding disappears. According to the section, what is the most likely explanation?
   - **A.** The lesion is too deep for the selected frequency
   - **B.** Anisotropy causing a fibrous structure to appear hypoechoic at certain insonation angles
   - **C.** High background parenchymal enhancement masking the true lesion
   - **D.** Summation of overlapping tissue planes
   - **E.** Fat-saturation failure producing residual signal

3. A radiographer reviews a mammogram showing an area of possible architectural distortion. Rolled views and spot compression cause the finding to disappear completely. Applying the framework described in the section, what is the most appropriate conclusion?
   - **A.** The finding is suspicious and requires ultrasound correlation
   - **B.** A supplementary MLO view should be taken to assess posterior tissue
   - **C.** The finding was almost certainly never real, as it dissolved with a technical modification
   - **D.** MRI is indicated because the finding could not be confirmed
   - **E.** The case should be recalled for tomosynthesis as the finding may represent NME

## Quality Assurance and Governance

### NHSBSP QA Framework

The NHSBSP operates a comprehensive QA programme coordinated by regional QA reference centres. Key components include:

- **Physics testing**: AEC constancy, detector uniformity, modulation transfer function, dose measurements — performed at defined intervals by medical physics teams
- **Daily and weekly radiographer checks**: Image quality phantoms, detector uniformity, and equipment performance checks; faults escalated promptly
- **Mean glandular dose monitoring**: Benchmarked against NHSBSP and EUREF reference levels; individual and equipment-level outliers investigated
- **Reject and retake analysis**: Causes classified (positioning, motion, artefact, exposure error) and fed back into training cycles — this is one of the most powerful quality improvement tools available

### Reading Environment

Calibrated high-luminance diagnostic monitors, controlled ambient lighting, and regular display quality assurance are mandatory in NHSBSP-accredited units. Inconsistent display calibration directly affects threshold detection of subtle densities and calcification morphology. As a trainee reading on a clinical workstation, be aware that a display that has not been recently calibrated may be showing you different grey-scale characteristics from those used by the screening readers.

### Technical Recall Management

The goal is to correct inadequate images **on the day**, before the patient leaves. When technical recall is unavoidable, the reason must be documented with a clear, targeted corrective plan — vague documentation perpetuates the same error.

### Continuous Professional Development

Peer review of positioning, side-by-side comparison with prior rounds, and shared review of challenging cases are the mechanisms through which standards are maintained and aligned. As a trainee, engaging actively with this — attending MDT, asking radiographers to show you what a difficult positioning looks like before and after correction — will accelerate your understanding far beyond textbook reading.

---

### Check your understanding

1. Reject and retake analysis is described in the NHSBSP QA framework as one of the most powerful quality improvement tools available.  *(True / False)*

2. In NHSBSP-accredited units, display quality assurance is optional provided that ambient lighting is adequately controlled.  *(True / False)*

3. When technical recall cannot be avoided, the NHSBSP requires that the reason is documented alongside a clear, targeted corrective plan.  *(True / False)*

## Practical Checklists

### Before Every Mammographic Exposure

- Patient identity confirmed; side markers in place; any relevant clinical information noted
- Skin lesions and scars marked with BBs
- Deodorant, powders, jewellery, ECG leads, and external artefacts removed
- **CC**: medial and posterior tissue included; nipple in profile if feasible; no major folds; adequate compression
- **MLO**: pectoral muscle to nipple level or below; axillary tail included; IMF open; no sag
- Review exposure, motion, and artefacts before the patient leaves — corrections are always easier now than at recall

### For DBT

- Coach the patient to remain still during the sweep; consider breath-hold
- Confirm posterior inclusion is adequate on the acquisition
- Assess for metal-induced streak artefacts; obtain 2D magnification separately for calcification assessment

### For Ultrasound

- Probe frequency appropriate to target depth
- Depth set to chest wall; focal zone positioned at lesion depth
- Gain and TGC balanced; harmonics on by default, adjusted as needed
- Systematic radial/anti-radial sweeps; each lesion documented by clock, cm from nipple, and depth
- Minimal probe pressure; Doppler optimised; correlation with mammographic coordinates confirmed

### For Breast MRI

- Prone; breast centred in coil; patient briefed on importance of keeping still
- Coverage from chest wall to axillary tail confirmed on localiser
- Fat suppression uniform on early post-contrast images — check before proceeding
- Bolus timing and IV access confirmed; dynamic protocol executed as planned
- Motion assessed on initial series; repeat sequences rather than proceeding with non-diagnostic data

---

### Check your understanding

1. During breast MRI acquisition, if motion artefact is identified on the initial series, the protocol requires the sequence to be repeated rather than proceeding with non-diagnostic data.  *(True / False)*

2. For DBT, 2D magnification views are obtained as part of the standard acquisition sweep and do not need to be performed separately.  *(True / False)*

3. On an MLO mammographic view, the inframammary fold (IMF) should be open and the pectoral muscle should extend to the nipple level or below.  *(True / False)*

## Summary

Image quality is not a bureaucratic requirement — it is the operational substrate upon which every breast imaging interpretation rests. Whether you are working in NHSBSP screening with two-view mammography and double reading, or in a symptomatic clinic applying triple assessment and B scoring, the diagnostic confidence of your report depends on what the acquisition actually shows.

Understanding why contrast, resolution, and noise behave as they do; why positioning and compression transform diagnostic yield; and how artefacts arise and can be corrected gives you the capacity to prevent pitfalls, reduce false outcomes, and report with genuine confidence. Where practice legitimately varies — DBT protocols, specific MLO angles, choice of fat suppression method — the governing principles remain constant: include all the tissue, separate and stabilise it, choose parameters that reveal the lesion without adding artefact, and correlate systematically across modalities.

When something looks wrong, ask whether the image was acquired correctly before you decide what it means.

### Check your understanding

1. According to this summary, diagnostic confidence in mammographic reporting is dependent on the quality of image acquisition.  *(True / False)*

2. This summary states that governing principles for image acquisition vary between DBT protocols and standard two-view mammography.  *(True / False)*

3. The summary advises that when an image appearance is unexpected, the radiographer should first consider whether the image was acquired correctly before drawing interpretive conclusions.  *(True / False)*


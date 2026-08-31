---
layout: default
title: "Chapter 02: Mammography Image Acquisition"
nav_order: 2
---

> **⚠️ AI-generated content — requires human review.**
> This chapter was produced automatically by a large language model and has not been verified by a clinician. It may contain errors or omissions. Do not rely on it for clinical decisions until it has been reviewed and approved by a qualified specialist.

# Chapter 2: Mammography Image Acquisition

---

## Why acquisition matters

![Mammography unit]({{ '/docs/img/wikimedia_mammography_unit.jpg' | relative_url }})

*Figure: A mammography unit — the compression paddle and detector define the acquisition geometry. Bill Branson, National Cancer Institute (public domain), via Wikimedia Commons (https://commons.wikimedia.org/wiki/File:Mammography_machine.jpg). External teaching example — not independently verified against this text.*

As a radiologist, you will not routinely position patients yourself, but you must understand acquisition well enough to recognise when an image is genuinely diagnostic and when it is not — and to direct the radiographer accordingly. Poor acquisition is the single most preventable cause of false negatives in mammography. A cancer missed because of inadequate positioning or suboptimal compression is a failure that cannot be rescued at the reporting workstation. Conversely, unnecessary repeats increase dose, distress, and recall rates.

In the NHS Breast Screening Programme (NHSBSP), images are double-read with arbitration. Consistent acquisition quality is therefore a programme-wide patient safety issue, not merely a technical nicety.

---

### Check your understanding

1. A radiologist is reviewing a screening mammogram and suspects a region of interest may lie outside the imaged field due to suboptimal positioning. Which of the following best describes why this matters at a programme level within the NHSBSP?
   - **A.** It increases the radiation dose per image, triggering a statutory incident report
   - **B.** It reduces the effectiveness of double-reading with arbitration as a patient safety mechanism
   - **C.** It requires the case to be automatically referred for assessment
   - **D.** It invalidates the consent process for the screening episode
   - **E.** It necessitates immediate clinical examination by a breast surgeon

2. A mammographer produces a technically suboptimal image but decides not to repeat it to avoid additional radiation dose. According to the principles outlined in this section, what is the primary risk of this decision?
   - **A.** The image will fail automated image-quality software checks
   - **B.** A cancer may be missed, a failure that cannot be rescued at the reporting workstation
   - **C.** The recall rate for the unit will fall below NHSBSP targets
   - **D.** The radiologist will be unable to perform arbitration
   - **E.** The patient's compression force will be incorrectly recorded

3. When considering whether to repeat a mammographic projection, which pair of consequences does this section specifically associate with unnecessary repeat acquisitions?
   - **A.** Increased dose and higher false-positive rates
   - **B.** Increased dose and higher recall rates
   - **C.** Increased dose and longer reporting times
   - **D.** Increased compression force and patient distress
   - **E.** Increased dose and reduced double-reading compliance

## The UK pathway: where acquisition fits

**Screening (NHSBSP)**

Routine invitations are offered every three years to women aged 50–70; some units have extended this to 47–73 as part of a trial, and local practice varies. The standard examination is bilateral two-view full-field digital mammography (FFDM): a mediolateral oblique (MLO) and a craniocaudal (CC) view of each breast. Images are independently double-read, with arbitration of disagreements and recall to assessment when indicated.

Image quality is formally assessed using the **PGMI system** (Perfect / Good / Moderate / Inadequate) and tracked through repeat and reject analysis. These are governance tools: use them analytically to identify recurrent positioning errors and drive retraining, not simply as a checklist to tick.

**Symptomatic (triple assessment)**

Here, mammography is one component of **triple assessment**: clinical (P1–P5), imaging (M1–M5 for mammography, U1–U5 for ultrasound), and pathological (B1–B5 for biopsy). The five-point scales exist to force explicit categorisation of suspicion and to structure the multidisciplinary decision. You should know these scales and use them consistently in your reports.

In the symptomatic setting, acquisition is tailored to the clinical question — additional views are targeted rather than routine, and correlation with ultrasound and clinical findings drives which projections add diagnostic value.

---

### Check your understanding

1. A 58-year-old woman attends the symptomatic breast clinic with a palpable lump. Mammography is performed and reported. Within the triple assessment framework, which coding system is used to categorise the level of suspicion on the mammogram?
   - **A.** P1–P5
   - **B.** B1–B5
   - **C.** M1–M5
   - **D.** U1–U5
   - **E.** PGMI

2. A symptomatic patient is recalled for further imaging after her initial mammogram. Which statement best describes how additional mammographic views should be selected in the symptomatic setting, according to this section?
   - **A.** The standard bilateral two-view protocol should be repeated in full before any additional views are taken
   - **B.** Additional views are targeted to the clinical question, guided by correlation with ultrasound and clinical findings
   - **C.** Additional views follow the same routine protocol used in the NHSBSP screening programme
   - **D.** The PGMI system determines which additional projections are required
   - **E.** Additional views are obtained routinely for all symptomatic patients regardless of clinical findings

3. A mammography unit is reviewing its image quality governance processes. What is the primary intended purpose of the PGMI system, as described in this section?
   - **A.** To categorise the level of radiological suspicion in screening-detected abnormalities
   - **B.** To determine whether a screening recall to assessment is warranted
   - **C.** To analytically identify recurrent positioning errors and drive retraining
   - **D.** To provide a five-point scale for multidisciplinary decision-making
   - **E.** To record the number of double-read disagreements requiring arbitration

## Breast anatomy and why it drives positioning

Thinking anatomically helps you understand both positioning goals and common misses. The breast is a three-dimensional cone of fibroglandular tissue on a curved chest wall, extending:

- **Superiorly** towards the clavicle
- **Laterally** into the axillary tail (tail of Spence)
- **Medially** across the sternum
- **Posteriorly** to the inframammary fold (IMF) and chest wall

No single projection images all of this. The MLO maximises posterior and axillary tail inclusion; the CC maximises medial and lateral coverage in a single plane. Together they give complementary coverage — which is why two views are standard and why the posterior nipple line (PNL) on each view should be roughly comparable (within ~1 cm as a practical guide).

Understand the consequences of missed anatomy:
- Failure to recruit the axillary tail on MLO → missed upper outer and posterior cancers
- Failure to open the IMF → missed inferior posterior tissue
- Insufficient medial traction on CC → missed medial masses
- Skin folds from poor positioning → obscured tissue and potential false positives

---

### Check your understanding

1. On the MLO projection, the primary aim is to maximise medial and lateral coverage of the breast in a single plane.  *(True / False)*

2. The posterior nipple line on the MLO and CC projections should be within approximately 1 cm of each other as a practical guide to adequate positioning.  *(True / False)*

3. Failure to open the inframammary fold on the MLO projection results in missed inferior posterior tissue.  *(True / False)*

## Physics that matter at the reporting workstation

You do not need to know every acquisition parameter, but understanding the underlying physics helps you recognise artefacts, assess adequacy, and advise appropriately.

**Spectrum and contrast**

Mammography uses low-energy X-rays (approximately 20–35 kVp effective) to maximise soft-tissue contrast between glandular and fatty tissue — contrast that disappears at higher energies. Modern systems use a tungsten (W) target with selectable filters (rhodium, silver) that tune the spectrum to breast thickness and density. Dense, thick breasts typically require a higher kVp or different filter combination to penetrate adequately.

**Automatic exposure control (AEC)**

AEC selects kVp and mAs based on sampling of a selected region. The radiographer's choice of AEC field matters: if the sampling region does not represent the tissue of interest (e.g. fat is sampled rather than dense parenchyma), the image will be suboptimally exposed. Dense breasts, implants, and post-surgical changes may require manual override — recognise this when reviewing exposure factors.

**Compression — the most important variable you can influence**

Compression is not primarily about patient discomfort management; it is a diagnostic tool:

- Reduces breast thickness → lower dose and less scatter
- Immobilises tissue → sharper images, less motion blur
- Spreads overlapping structures → exposes distortions and calcifications that would otherwise be hidden

There is no single correct compression force. The goal is firm, sustained, tolerable compression that visibly thins and immobilises the breast. Inadequate compression is a common and correctable cause of missed architectural distortion and calcification clusters. When reviewing images, assess whether the breast appears adequately compressed (flat, spread tissue) rather than simply recording the force figure.

**Geometry and focal spot**

A small focal spot (~0.1 mm) improves geometric sharpness and is used for magnification views. The standard focal spot (~0.3 mm) is used for contact views. The anode heel effect is exploited by orienting the cathode towards the chest wall, compensating for the greater attenuation of thicker posterior tissue.

---

### Check your understanding

1. The primary purpose of breast compression in mammography is to reduce patient discomfort rather than to act as a diagnostic tool.  *(True / False)*

2. When the AEC sampling region inadvertently samples fatty tissue rather than dense parenchyma, the resulting image will be suboptimally exposed.  *(True / False)*

3. The small focal spot of approximately 0.1 mm is used for standard contact views, whilst the larger focal spot of approximately 0.3 mm is reserved for magnification views.  *(True / False)*

## Standard projections: objectives and adequacy

![Mammography views and anatomy: CC, MLO, XCCL and LM projections]({{ '/docs/img/anatomy_mammography_views_poster.png' | relative_url }})

*Figure: The mammographic projections and the anatomy each demonstrates, with the corresponding patient positioning. The two standard screening views are the craniocaudal (CC) and mediolateral oblique (MLO); the exaggerated craniocaudal lateral (XCCL) and lateromedial (LM) are additional/problem-solving views for far-lateral and medial tissue respectively. Source: M Aulo (AI-generated anatomy illustration).*

### Mediolateral oblique (MLO)

**Objective:** Maximum volume — posterior, superior, axillary tail, and inferior tissue — with the IMF open.

The MLO angle (typically 45–60°) should approximate the angle of the pectoralis major muscle, not simply be set to a fixed number. Broader shoulders need a steeper angle; kyphosis or pendulous breasts may need a shallower one.

**Adequacy criteria:**
- Pectoralis muscle visible to or below the PNL (the horizontal line from the nipple to the posterior image edge)
- IMF open and clearly visualised
- Nipple ideally in profile (or noted if not, with a complementary view obtained if clinically relevant)
- No skin folds obscuring posterior or inferior tissue
- PNL comparable to the CC PNL (±1 cm as a practical guide)

In very small breasts, pectoralis reaching the PNL may not be achievable; in surgically altered breasts, PNL matching is less reliable. Apply composite judgement rather than rigid rules.

### Craniocaudal (CC)

**Objective:** Balanced medial and lateral coverage, with the nipple centred and in profile.

The CC tends to under-represent medial tissue because medial breast is less mobile. The radiographer must apply deliberate medial traction before compression; without this, medial masses are easily excluded.

**Adequacy criteria:**
- PNL within ~1 cm of the MLO PNL
- Medial and lateral fibroglandular tissue both present and not cut off at the chest wall
- Nipple centred and ideally in profile

If the PNL is substantially shorter on CC than MLO, posterior tissue has been excluded — a common and important shortcoming.

---

### Check your understanding

1. On the MLO projection, the pectoralis muscle should be visible to or below the posterior nipple line (PNL).  *(True / False)*

2. The MLO angle should be fixed at 45° for all patients regardless of body habitus.  *(True / False)*

3. On the CC projection, a substantially shorter PNL compared with the MLO PNL indicates that posterior tissue has been excluded.  *(True / False)*

## Additional and problem-solving views

Do not acquire additional views by rote. Each should be directed by a specific question: Is this density real or summation? Is this calcification cutaneous? Where exactly does this distortion localise in three dimensions?

| View | Purpose |
|---|---|
| **Lateromedial (LM) / mediolateral (ML)** | True lateral; localises lesions superiorly or inferiorly; clarifies equivocal MLO findings |
| **Exaggerated CC lateral (XCCL) / medial (XCCM)** | Includes far lateral or medial tissue cut off on standard CC |
| **Cleavage (CV)** | Improves medial coverage across the midline |
| **Rolled CC (RM/RL)** | Separates overlapping densities to distinguish summation from a true mass |
| **Spot compression ± magnification** | Sharpens margins; magnification (small focal spot, no grid) is the standard approach for microcalcification characterisation |
| **Tangential** | Confirms cutaneous location of calcifications or markers over palpable skin lesions |
| **Axillary tail** | Focused recruitment when axillary tissue is inadequate on MLO |

**The rolled CC view is particularly useful in practice:** if an apparent asymmetry on MLO moves on rolling, it is more likely to represent summation; if it persists, pursue further evaluation with spot compression and/or ultrasound.

---

### Check your understanding

1. A radiographer identifies an apparent asymmetric density on the MLO view only. A rolled CC view is performed and the density changes position. What is the most appropriate interpretation of this finding?
   - **A.** The density is likely a true mass and should be referred for biopsy
   - **B.** The density most likely represents summation of normal tissues
   - **C.** The density is likely cutaneous and a tangential view should follow
   - **D.** The density is located in the far lateral tissue and an XCCL view is required
   - **E.** The finding confirms a distortion and spot compression should be performed immediately

2. A radiographer wishes to characterise a cluster of microcalcifications identified on a standard mammogram. Which of the following best describes the recommended technique?
   - **A.** Spot compression view using a large focal spot without a grid
   - **B.** Magnification view using a small focal spot without a grid
   - **C.** Magnification view using a large focal spot with a grid
   - **D.** Tangential view using a small focal spot with a grid
   - **E.** Rolled CC view using standard focal spot settings

3. A radiographer notices calcifications overlying a palpable skin lesion. Which additional view is most appropriate to confirm their cutaneous location?
   - **A.** Cleavage view
   - **B.** Exaggerated CC lateral view
   - **C.** Tangential view
   - **D.** Rolled CC view
   - **E.** Axillary tail view

## Digital breast tomosynthesis (DBT): what you need to know

DBT acquires multiple low-dose projections through an arc and reconstructs thin (~1 mm) slices, reducing tissue overlap. Its main clinical advantage is improved conspicuity of **architectural distortion and spiculated masses** that are buried in overlapping parenchyma on 2D mammography.

**Key acquisition points:**
- The breast must remain motionless slightly longer than for standard FFDM; motion artefact is a specific pitfall
- Synthetic 2D images can be generated from the DBT dataset, avoiding the separate FFDM exposure of "combo" mode; note that DBT itself carries a dose roughly 1–1.5 times that of standard two-view FFDM, so it does not necessarily reduce total dose
- Calcification characterisation is possible but appearances differ from magnification FFDM; learn your system's reconstruction behaviour

**UK context:** DBT is widely used in symptomatic assessment clinics. Its adoption in routine screening varies between NHSBSP units. Reading workflows and arbitration pathways are still evolving; follow your local guidance.

---

### Check your understanding

1. The primary clinical advantage of DBT over standard 2D mammography is improved detection of calcification clusters that are obscured by overlapping tissue.  *(True / False)*

2. Generating synthetic 2D images from the DBT dataset avoids the additional radiation exposure associated with acquiring a separate full-field digital mammography image in 'combo' mode.  *(True / False)*

3. DBT itself carries a radiation dose roughly 1–1.5 times that of standard two-view FFDM, meaning that using DBT with synthetic 2D images does not necessarily reduce total dose compared with standard FFDM alone.  *(True / False)*

## Contrast-enhanced mammography (CEM)

CEM uses dual-energy acquisition after iodinated contrast to produce recombined images highlighting tissue enhancement — effectively mammographic resolution with MRI-like functional information. It is growing in use for problem-solving in dense breasts, extent of disease assessment, and when MRI is unavailable or contraindicated.

**Acquisition points:**
- Time-sensitive bilateral exposures within a defined post-injection window
- Requires iodine contrast screening and IV access; dose is higher than standard FFDM but within diagnostic reference levels
- Practice varies considerably across units; align with local governance and indication criteria

---

### Check your understanding

1. A patient with dense breasts requires extent of disease assessment but has a contraindication to MRI. Which of the following best describes why CEM is a suitable alternative in this scenario?
   - **A.** CEM uses radioactive tracers to produce functional images at mammographic resolution
   - **B.** CEM uses dual-energy acquisition after iodinated contrast to highlight tissue enhancement, providing MRI-like functional information
   - **C.** CEM acquires images without contrast, relying on spectral subtraction alone to identify disease extent
   - **D.** CEM delivers a radiation dose equivalent to standard full-field digital mammography
   - **E.** CEM is restricted to unilateral acquisitions to minimise patient radiation dose

2. Regarding the acquisition protocol for CEM, which of the following statements most accurately reflects the technique as described?
   - **A.** CEM requires no intravenous access as contrast is administered orally before imaging
   - **B.** Exposures are performed within a defined post-injection window and iodine contrast screening is required
   - **C.** CEM acquisitions are not time-sensitive, allowing flexible scheduling after contrast injection
   - **D.** The radiation dose delivered by CEM is lower than that of standard full-field digital mammography
   - **E.** A standardised national protocol governs CEM acquisition, eliminating variation between units

3. Which of the following is an established clinical indication for CEM according to this section?
   - **A.** Routine annual screening of average-risk women in place of standard mammography
   - **B.** Problem-solving in women with dense breasts when MRI is unavailable or contraindicated
   - **C.** Replacing ultrasound as the first-line investigation for palpable lumps in young women
   - **D.** Monitoring response to hormone replacement therapy in asymptomatic women
   - **E.** Characterising axillary lymph nodes as the primary imaging investigation

## Image quality assessment: PGMI in practice

PGMI grades should prompt a specific response:

- **Perfect / Good:** Meets inclusion, positioning, exposure, and sharpness criteria — proceed with reporting
- **Moderate:** Diagnostic but with correctable faults — document and target retraining; decide whether the fault materially affects interpretation for this patient
- **Inadequate:** Non-diagnostic — repeat if safe and if it would materially change management

The key question when reviewing quality is always: *Does this image miss clinically important tissue, or could a detectable cancer appear normal because of this fault?* If the answer is yes, a repeat is justified. If the image has a technical imperfection but is genuinely diagnostic, repeating simply for PGMI performance is not good practice — it increases dose and distress.

---

### Check your understanding

1. A mammogram is graded Moderate under PGMI. The image shows mild underexposure but the breast tissue is still adequately visualised and no clinically important tissue is missed. What is the most appropriate next action?
   - **A.** Repeat the image immediately to achieve a Perfect or Good grade
   - **B.** Discard the image and recall the patient on a separate occasion
   - **C.** Proceed with reporting, document the fault, and target retraining
   - **D.** Grade the image Inadequate and repeat if safe and clinically justified
   - **E.** Report the image without any documentation or follow-up action

2. A mammogram is graded Inadequate because significant posterior tissue is excluded, raising concern that a palpable abnormality in that region may not be demonstrated. What is the key question that justifies repeating this image?
   - **A.** Does the fault reduce the overall PGMI performance score for the screening unit?
   - **B.** Does the image miss clinically important tissue or could a detectable cancer appear normal because of this fault?
   - **C.** Is the exposure index outside the accepted reference range for the equipment?
   - **D.** Would repeating the image improve the radiographer's individual PGMI Perfect/Good rate?
   - **E.** Has the patient previously had a Moderate or Inadequate mammogram on the same breast?

3. A technically imperfect mammogram is graded Moderate and is genuinely diagnostic. The radiographer proposes repeating it solely to improve the unit's PGMI Perfect/Good statistics. According to PGMI guidance, why is this not good practice?
   - **A.** Moderate images must always be accepted without repeat regardless of clinical context
   - **B.** Repeating Moderate images is prohibited by national screening protocols
   - **C.** It unnecessarily increases radiation dose and patient distress without diagnostic benefit
   - **D.** PGMI grades cannot be applied retrospectively once an image has been processed
   - **E.** The repeat image would automatically be graded Inadequate under PGMI rules

## Artefacts: prevention and recognition

Recognising artefacts prevents false positives and ensures you request targeted repeats rather than misinterpreting an image.

**Common artefacts and their prevention:**

| Artefact | Appearance | Prevention |
|---|---|---|
| Deodorant / talc | Granular high-attenuation foci mimicking calcifications | Wipes and preparation before exposure |
| Skin folds | Linear densities, often posterior / inferior | Correct positioning; hand support during compression |
| Hair / clothing / jewellery | Lines or overlap at edges | Clear the field and check before exposing |
| Motion blur | Loss of sharpness, particularly of calcifications | Coaching, adequate compression, prompt exposure |
| Nipple shadow | Rounded density on CC mimicking mass | Obtain nipple-in-profile or spot view to clarify |
| Detector defects / lag | Fixed patterns or ghost images | Calibration; avoid rapid repeats on the same area |

Deodorant artefact deserves emphasis: granular deposits can be indistinguishable from microcalcifications at first glance. A history of deodorant use, bilateral distribution, and surface distribution on tangential views help — but prevention is always preferable.

---

### Check your understanding

1. Granular high-attenuation foci caused by deodorant artefact can be indistinguishable from microcalcifications at first glance.  *(True / False)*

2. Motion blur primarily affects the perceived density of masses rather than the sharpness of calcifications.  *(True / False)*

3. A nipple shadow artefact on the craniocaudal view should be clarified by obtaining a nipple-in-profile or spot view.  *(True / False)*

## Special patient groups: the principle of adapting without compromising

The underlying principle is always the same: image as much clinically relevant breast tissue as safely possible, document your limitations, and correlate with other modalities when acquisition is necessarily suboptimal.

**Breast implants**
Standard views are performed with limited compression on the implant. Eklund (implant-displaced) views push the implant posteriorly to image the native breast tissue under compression. Eklund views are contraindicated when the implant is immobile, very painful, or at risk of rupture — document this clearly and ensure clinical and ultrasound assessment compensate.

**Post-surgical and irradiated breasts**
Expect skin thickening, clips, seromas, and scar-related distortion. Mark scars. Compression should be firm but incremental, with attention to pain over irradiated or recently operated skin. Magnification views of the lumpectomy bed are standard practice when calcifications require characterisation.

**Male patients**
Smaller breast volume with different tissue distribution. CC and MLO (or LM) as tolerated; mark palpable lumps. The principles are identical; the geometry adapts.

**Pregnancy and lactation**
Ultrasound is first-line. Mammography is safe when clinically indicated — expect high density and discomfort. Compression should be as firm as tolerated; AEC may select higher kVp/mAs for dense lactating tissue.

**Limited mobility / kyphosis / obesity**
Seated acquisitions, modified obliquity angles, and "from-below" CC views are all valid adaptations. Prioritise inclusion of the area of clinical concern over achieving textbook PGMI criteria. Document what was and was not achievable.

**Post-mastectomy**
Routine screening images the contralateral breast only. The mastectomy side is not routinely mammographed; symptomatic concerns are addressed with clinical examination and ultrasound.

---

### Check your understanding

1. A woman with bilateral silicone implants attends for mammography. On the right side, the implant is found to be immobile and the patient reports significant pain on palpation. What is the correct course of action regarding Eklund views on the right?
   - **A.** Perform Eklund views with reduced compression to minimise discomfort
   - **B.** Perform Eklund views only if the standard view image quality is inadequate
   - **C.** Omit Eklund views, document this clearly, and ensure clinical and ultrasound assessment compensate
   - **D.** Defer the entire examination and rebook when the implant is less painful
   - **E.** Perform Eklund views on one projection only and document the limitation

2. A patient with a previous lumpectomy and radiotherapy attends for follow-up mammography. New calcifications are identified near the lumpectomy bed. Which additional view is described as standard practice for characterising these calcifications?
   - **A.** Lateral medial (LM) view of the affected breast
   - **B.** Cleavage view to include medial tissue
   - **C.** Magnification view of the lumpectomy bed
   - **D.** Extended craniocaudal view to include the axillary tail
   - **E.** Rolled craniocaudal view to separate overlapping tissue

3. A patient who has undergone a right mastectomy attends the symptomatic clinic reporting a new lump on the right chest wall. According to the principle outlined, how should the right (mastectomy) side be assessed?
   - **A.** Mammography of the chest wall using a modified CC projection
   - **B.** Clinical examination and ultrasound
   - **C.** Routine mammography of both sides as per standard protocol
   - **D.** MRI of the chest wall as first-line investigation
   - **E.** MLO view only of the mastectomy side to limit radiation dose

## Markers, annotation, and labelling

Consistent labelling is a patient safety issue in double-reading and image-guided procedures.

**Skin markers:**
- Palpable area: radiolucent ring with central BB
- Scars: linear marker along the scar length
- Moles: specific mole marker or BB, to prevent misinterpretation as calcifications
- Nipple: BB if not in profile and its position is clinically relevant

**Labels must include:** patient identifiers, laterality (L/R), projection, date and time, unit identifier, exposure factors, compression force and breast thickness, paddle and operator identifiers — per NHSBSP standards.

Internally, biopsy clips should be documented and their position correlated with the target lesion at each subsequent imaging episode.

---

### Check your understanding

1. A radiolucent ring with a central BB is the recommended skin marker for a palpable area.  *(True / False)*

2. A BB placed over a mole is acceptable because moles cannot be mistaken for calcifications on mammography.  *(True / False)*

3. NHSBSP labelling standards require compression force and breast thickness to be included on every mammographic image.  *(True / False)*

## Acquisition and biopsy: the direct connection

Your ability to read an image well and direct a biopsy safely depends on understanding what has been imaged and how. Specifically:

- **Stereotactic biopsy** requires precise compression, immobilisation, and knowledge of parallax shifts between stereo pairs. Opening the IMF and stabilising mobile posterior tissue are prerequisites for accurate needle placement
- **Calcification work-up** depends on high-quality magnification views: small focal spot, no grid (air gap provides scatter rejection), full inclusion of the cluster, and motion-free exposure. A suboptimal magnification view that clips the cluster or has motion blur invalidates the assessment
- **Localisation procedures** (wire, radioguided, or marker-directed) require understanding of how the target was imaged and at what depth, so that the chosen approach is geometrically sound

---

### Check your understanding

1. In magnification mammography for calcification work-up, a grid should be used to improve scatter rejection.  *(True / False)*

2. For stereotactic biopsy, opening the inframammary fold and stabilising mobile posterior tissue are prerequisites for accurate needle placement.  *(True / False)*

3. A magnification view that clips part of a calcification cluster is still adequate for calcification assessment provided there is no motion blur.  *(True / False)*

## Where practice varies — exercise judgement

The NHSBSP provides standards and guidance, but several areas involve genuine variation in practice:

- **DBT in screening:** Not yet universal; follow your unit's protocol and double-reading pathway
- **Compression strategy:** Units differ on target force ranges and pain mitigation approaches; the principle (optimal diagnostic quality with patient-centred care) is constant
- **LM versus ML:** Choice depends on ergonomics, habitus, and lesion location; neither is universally correct
- **CEM indications:** Growing evidence base but not standardised nationally; use within local governance structures
- **PNL equivalence:** The ±1 cm rule is a guide, not an absolute; interpret in context of the individual patient

Acknowledge these variations when they affect your reporting and recommend follow-up imaging that is practically available at your unit.

---

### Check your understanding

1. A radiographer is deciding whether to use a lateromedial (LM) or mediolateral (ML) projection for a patient with a laterally situated lesion. According to unit guidance on areas of genuine practice variation, which statement best reflects the recommended approach?
   - **A.** The ML projection is universally preferred and should always be used regardless of lesion location
   - **B.** The LM projection is the NHSBSP mandatory standard and must be used in all cases
   - **C.** The choice should be guided by ergonomics, patient habitus, and lesion location, as neither projection is universally correct
   - **D.** The decision rests solely on the radiographer's personal preference with no other factors considered
   - **E.** DBT acquisition removes the need to choose between LM and ML projections

2. A unit is considering introducing contrast-enhanced mammography (CEM) for selected patients. Which statement most accurately reflects the section's position on CEM indications?
   - **A.** CEM has been fully standardised nationally and should be offered to all screening patients
   - **B.** CEM has no evidence base and should not be used outside research settings
   - **C.** CEM indications are growing in evidence but are not nationally standardised, and its use should sit within local governance structures
   - **D.** CEM replaces DBT in all diagnostic pathways according to NHSBSP guidance
   - **E.** CEM is only permitted at units that perform double reading of all mammograms

3. When assessing posterior nipple line (PNL) equivalence between projections, which approach is most consistent with the guidance given in this section?
   - **A.** Any discrepancy beyond 1 cm automatically requires the projection to be repeated
   - **B.** The ±1 cm rule is an absolute threshold that overrides all other clinical considerations
   - **C.** PNL equivalence should be ignored entirely as it is no longer considered relevant
   - **D.** The ±1 cm rule is a guide and should be interpreted in the context of the individual patient
   - **E.** PNL equivalence applies only to DBT acquisitions and not to standard mammography

## Summary principles

- **Image the whole breast:** prioritise posterior, superior, and medial inclusion — these are the commonest sites of missed cancers due to poor positioning
- **Compression is diagnostic:** inadequate compression hides distortion and calcifications; it is not simply a comfort issue
- **Tailor projections to the question:** think in three dimensions and choose additional views deliberately
- **Anticipate and eliminate artefacts before exposing:** preparation is faster than repeating
- **Annotate consistently and completely:** correct labelling underpins safe double-reading and intervention
- **Apply PGMI analytically:** ask whether a fault materially affects cancer detection for this patient, and act accordingly
- **Connect acquisition to interpretation:** knowing exactly what tissue is included, and how it was moved, is what allows you to distinguish summation from a real lesion, localise a distortion for targeted ultrasound, and plan a biopsy safely

Mastering acquisition principles is not an optional extra for radiologists — it is foundational to accurate interpretation, safe intervention, and meaningful quality assurance.

### Check your understanding

1. According to the summary principles, inadequate compression is primarily a patient comfort issue rather than a diagnostic concern.  *(True / False)*

2. The posterior, superior, and medial aspects of the breast are identified as the commonest sites of missed cancers due to poor positioning.  *(True / False)*

3. Knowing exactly what tissue is included in a mammographic acquisition, and how it was moved, enables the practitioner to distinguish summation from a real lesion and localise a distortion for targeted ultrasound.  *(True / False)*


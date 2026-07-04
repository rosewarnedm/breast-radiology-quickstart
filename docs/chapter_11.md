---
layout: default
title: "Chapter 11: Quality Assurance and Safety"
nav_order: 11
---

> **⚠️ AI-generated content — requires human review.**
> This chapter was produced automatically by a large language model and has not been verified by a clinician. It may contain errors or omissions. Do not rely on it for clinical decisions until it has been reviewed and approved by a qualified specialist.

# Chapter 11: Quality Assurance and Safety

> **⚠️ AI-generated content — requires human review.**
> This chapter was produced automatically by a large language model and has not been verified by a clinician. It may contain errors or omissions. Do not rely on it for clinical decisions until it has been reviewed and approved by a qualified specialist.

---

## 11.1 Why QA and Safety Matter

Quality assurance is not bureaucratic box-ticking — it is what keeps diagnostic performance reliable and harm to a minimum. In breast imaging, the consequences of failure are concrete: a missed cancer, an avoidable false positive, a procedure complication, or a radiation incident. Each of these represents a patient harmed and a system that failed to protect her.

Three drivers make QA mandatory rather than optional. First, **diagnostic performance**: image quality, positioning, exposure optimisation and interpretation rigour directly determine cancer detection rates and recall rates — both of which are tracked at unit level. Second, **regulation**: IR(ME)R and IRR impose legally enforceable duties around justification, optimisation and staff protection; the NHSBSP requires units to meet published key performance indicators (KPIs) and participate in external QA visits. Third, **patient-centredness**: good QA reduces unnecessary repeats, minimises radiation burden, supports meaningful consent, and underpins the duty of candour when things go wrong.

The goal is not perfection but **reliable, continuously improving care**. Practice legitimately varies — particularly where evidence is evolving or local constraints differ — but decisions should be transparent, reasoned and auditable.

---

## 11.2 The UK Framework

### NHSBSP and Symptomatic Services

The NHS Breast Screening Programme currently invites women aged 50–70 in England at three-year intervals for two-view mammography, with local extension to 47–73 in some areas. All screening mammograms are **double-read with arbitration** of discordant assessments; women with suspicious findings are recalled to a one-stop or two-stop assessment clinic.

Symptomatic services operate through **triple assessment**: clinical examination generates a **P score** (P1–P5); imaging generates an **M score** (mammography, M1–M5) and/or **U score** (ultrasound, U1–U5); and percutaneous biopsy generates a **B code** (B1–B5 histological categories). Discordance between these components is the safety net — it should always prompt re-review rather than false reassurance.

Urgent symptomatic referrals are managed through the two-week wait (2WW) pathway where a suspected cancer is identified clinically.

### Regulatory and Governance Context

- **IR(ME)R** (Ionising Radiation (Medical Exposure) Regulations): justification of every exposure, optimisation of dose, and documented clinical evaluation of the outcome. Significant accidental or unintended exposures (SAUEs) must be investigated under local Employer's Procedures and reported to the CQC where required.
- **IRR** (Ionising Radiations Regulations): protection of staff and the public; roles of the Radiation Protection Adviser (RPA) and Medical Physics Expert (MPE).
- **NHSBSP QA**: national standards documents, external QA visits, interval cancer review, and the **PERFORMS** scheme — an external proficiency-testing programme for screening readers that provides individual benchmarking and identifies underperformance.
- **Professional bodies**: IPEM publishes equipment testing schedules for mammography units and display devices; BMUS covers ultrasound QA; RCR and SCoR set governance, reporting and training standards.

---

## 11.3 Image Quality Assurance: Getting the Images Right

Image quality is not aesthetic — it is clinical. A poorly positioned mammogram may leave posterior tissue unrepresented; motion blur may render calcification morphology unclassifiable; a miscalibrated ultrasound preset may hide spiculation. The same systematic thinking that you apply to image interpretation should be applied to image acquisition.

### 11.3.1 Mammography (2D and Tomosynthesis)

**Positioning and anatomy**

The aim on the craniocaudal (CC) view is to include the retroareolar tissue, as much posterior tissue as possible, and the medial tissue without sacrificing the lateral. On the mediolateral oblique (MLO), the pectoralis major should be visualised as a convex muscle edge reaching within accepted tolerance of the posterior nipple line (PNL), and the inframammary fold should be open. The rationale: cancers are distributed throughout the fibroglandular cone, including the posterior and inferior aspects — under-represented tissue correlates with false negatives and is a common finding in interval cancer reviews.

**Compression**

Adequate compression reduces tissue thickness (lowering dose and scatter), immobilises the breast (reducing motion blur), separates overlapping tissue, and standardises automatic exposure control (AEC) performance. The correct compression is the **minimum** needed to achieve stable, acceptably thin tissue whilst remaining tolerable — it is not a fixed force target. Patient-centred coaching, explaining the benefit and warning of the sensation, consistently improves compression without increasing reported pain.

**Exposure optimisation**

Modern AEC systems select kV, target/filter combination and mAs to balance contrast and noise for the measured breast thickness and composition. Microcalcifications demand high spatial resolution and adequate low-contrast detectability; dense breasts may benefit from higher kV with appropriate filtration to penetrate whilst maintaining contrast. Dose is quantified as **average glandular dose (AGD)** per view; units are required to monitor AGD and compare against national diagnostic reference levels (DRLs) and local performance limits.

Tomosynthesis increases AGD relative to 2D alone; synthesised 2D images can partially offset combined dose in combo acquisition. Contrast-enhanced mammography (CEM) adds further dose. These trade-offs should be explicit when protocols are chosen and audited.

**PGMI image quality scoring**

In the screening setting, images are scored as **Perfect / Good / Moderate / Inadequate (Repeat required)**. This structured feedback system identifies training needs, equipment issues, and systematic positioning errors. Reject and repeat analysis should be reviewed regularly at unit level — a rising repeat rate may signal equipment drift, training gaps, or patient pathway problems.

**Equipment QA (in partnership with Medical Physics)**

Do not think of physics testing as something that happens in the background. Understand what is being tested and why:

- **Acceptance/commissioning**: baseline performance before clinical use.
- **Constancy testing**: daily, weekly, monthly and annual schedules per NHSBSP/IPEM publications. This includes AEC reproducibility, kV accuracy, uniformity and artefact evaluation, low-contrast and high-contrast (spatial resolution) performance, modulation transfer function (MTF), detector calibration and AGD measurements.
- **Tomosynthesis-specific**: angular accuracy, slice sensitivity profile, in-plane resolution, and artefact evaluation. Be alert to staircase artefacts (from reconstruction) and out-of-plane blur, which can mimic or mask spiculation on individual slices — always review in context.
- **After major maintenance or software changes**: re-test before clinical use.

**Displays and reading environment**

Mammography requires high-specification primary diagnostic monitors calibrated to the DICOM greyscale standard display function (GSDF), with regular luminance, uniformity and artefact checks by physics. Low ambient light is not optional — even moderate ambient light reduces perceived contrast and microcalcification visibility. This is particularly relevant for home reading during remote working, where monitor standards and ambient conditions must still be met.

**Common mammographic pitfalls**

| Pitfall | Consequence | Remedy |
|---|---|---|
| Inadequate posterior tissue on CC | Posterior lesion missed | Positioning coaching; immediate review by radiographer |
| Rolled or folded nipple | Retroareolar tissue obscured | Repeat with nipple in profile |
| Skin fold | Mimics architectural distortion | Ensure taut skin; spot compression; DBT |
| Motion blur | Calcification morphology lost | Short exposure; breast immobilisation; immediate review |

### 11.3.2 Ultrasound

Ultrasound quality is highly operator-dependent, which makes consistent technique and structured QA especially important.

**Technique principles**

Use breast-specific presets with a high-frequency linear transducer (typically 12–18 MHz for superficial work). Place focal zones at the level of interest. Scan systematically in **radial and antiradial planes** aligned to ductal anatomy, not simply in axial and longitudinal planes — small ductal lesions and papillomas are more readily identified this way. Correlate with mammographic clockface and distance from the nipple using the same anatomical landmarks.

Gain optimisation matters clinically: too low and hypoechoic spiculation disappears into background; too high and posterior acoustic shadowing is lost and margins are obscured. A lesion that appears to have parallel orientation may appear antiparallel if the transducer is not perpendicular — rocking and heel-toe adjustments are essential before categorising orientation.

**Equipment QA**

Regular probe checks for dead elements, delamination, and uniformity dropouts; phantom testing of depth calibration, grey-scale contrast performance, and Doppler sensitivity, in line with BMUS guidance and local physics schedules. Document artefacts: reverberation and side-lobe artefacts can mimic calcifications or distort lesion margins, leading to overcalling.

### 11.3.3 Breast MRI

Protocol standardisation is the foundation of MRI quality. Minimum requirements include: bilateral breast coil coverage, high-resolution T1-weighted pre- and dynamic post-contrast sequences with adequate temporal resolution to characterise kinetics, homogeneous fat suppression, and T2/STIR sequences for oedema and cystic characterisation. Subtracted images and maximum intensity projections (MIPs) aid overview; source images must always be reviewed to avoid missing enhancement that subtraction artefact obscures or simulates.

Coverage must extend from sternum to latissimus and from clavicle to inframammary fold — missed axillary tail or IMF disease is a preventable false negative.

**Equipment QA**

Physics testing covers signal-to-noise ratio, geometric accuracy, ghosting, fat suppression uniformity, and coil element performance. Re-validation is required after software upgrades or coil changes.

**Common MRI pitfalls**

Inhomogeneous fat suppression generates pseudo-enhancement that can mimic non-mass enhancement (NME). Cardiac and respiratory motion can be confused with NME. Background parenchymal enhancement (BPE) is hormonally driven — scheduling premenopausal women in the second week of the menstrual cycle reduces BPE and improves lesion conspicuity. Always correlate T1 enhancement with T2 signal and diffusion characteristics before drawing conclusions.

### 11.3.4 Contrast-Enhanced Mammography (CEM)

CEM acquires paired low- and high-energy images after iodinated contrast; the recombined image suppresses background tissue and highlights enhancement. QA covers exposure pairing accuracy, recombination algorithm performance, and recognition of artefacts — skin folds and post-biopsy clip bloom are recognised pitfalls. Dose exceeds 2D alone; protocols should be audited against DRLs. Safety considerations align with iodinated contrast practice (see section 11.4.4).

### 11.3.5 Specimen Imaging

Specimen radiography closes the loop on surgical excision — it confirms the target lesion has been removed, that calcifications are present in the specimen, and that any marker clip has been retrieved. Orient specimens with agreed surgical markers (sutures or clips). For microcalcification excision, high-resolution imaging and, if needed, specimen slicing are required; if calcifications are not demonstrated, inform the surgeon promptly to enable re-excision whilst the patient is still on the table. QA requires timely availability, consistent specimen labelling, and documented radiology–surgery communication.

---

## 11.4 Radiation Protection and Contrast Safety

### 11.4.1 Core IR(ME)R Principles

Three duties apply to every medical exposure:

1. **Justification**: the exposure must have a net benefit to the individual. In screening, this is population-level justification. In symptomatic practice, individual justification applies — consider age, clinical context, prior imaging and whether the result will change management.
2. **Optimisation**: use the lowest dose compatible with diagnostic quality. Monitor AGD; compare against DRLs; investigate outliers.
3. **Clinical evaluation**: produce a timely, documented report. For significant findings, use a failsafe communication mechanism — do not rely solely on the report reaching the referrer.

### 11.4.2 Mammography Dose

Typical AGD per view at modern accredited units is well within national performance limits. The key variables are breast thickness, density, kV and filtration. Systematic over-exposure — from a miscalibrated AEC, routinely inadequate compression, or an unchecked equipment drift — may only become apparent through dose audit. This is why regular physics testing and dose monitoring are essential rather than aspirational.

Tomosynthesis and CEM carry higher dose; synthesised 2D may partially offset the combined dose in tomosynthesis. These trade-offs should be quantified and communicated when protocols are selected.

### 11.4.3 Pregnancy and Lactation

Mammography is justifiable in pregnancy when clinically indicated; foetal dose from breast imaging is extremely low (scattered dose only, with no primary beam passing near the foetus). Ultrasound is the first-line modality in pregnant and lactating patients. MRI without gadolinium is safe in pregnancy. Gadolinium crosses the placenta and is generally avoided unless the clinical benefit clearly outweighs risk; this should be a documented consultant-level decision. Breastfeeding need not be interrupted after either gadolinium or iodinated contrast — the amount excreted in milk is clinically negligible, though some centres advise discarding milk for 24 hours after gadolinium in line with local guidance.

### 11.4.4 Iodinated Contrast (CEM) and Gadolinium (MRI)

Pre-procedure risk assessment for iodinated contrast should cover prior contrast reactions (the only reliable predictor of future reaction), asthma, and severe renal impairment. The traditional association between shellfish/seafood allergy and contrast reaction is not supported by evidence — do not use it as a screening question. For gadolinium, use macrocyclic agents preferentially; check renal function where indicated. For eGFR <30 ml/min/1.73 m², avoid unless essential and document the risk-benefit discussion.

Emergency equipment and trained staff for anaphylaxis management must be immediately available wherever contrast is administered. Extravasation management protocols should be in place and staff trained in their use.

### 11.4.5 SAUEs and Incident Reporting

Significant accidental or unintended exposures — wrong patient, wrong laterality, unintended repeat, or dose far exceeding that intended — require IR(ME)R investigation under local Employer's Procedures and may require external notification. Root-cause analysis should focus on **systems and human factors** rather than individual blame. Shared learning from SAUEs is a regulatory expectation and an ethical duty.

### 11.4.6 Staff Radiation Safety

In dedicated mammography suites, staff are not in the primary beam and dose is low. Personal dosimetry is used where risk assessment indicates. For **radioactive seed localisation** (iodine-125 seeds for surgical targeting), IRR and IR(ME)R governance applies: inventory control, written local rules, staff training, and seed reconciliation at surgery and pathology are all mandatory.

---

## 11.5 Procedural Safety: Biopsy, Localisation and Aftercare

Procedural safety is a **chain** — each link matters. A correctly targeted biopsy is worthless if the specimen is mislabelled, the result is misattributed, or discordance with imaging is not recognised.

### 11.5.1 Consent, Identification and Time-Out

Confirm patient identity, laterality and intended procedure before every intervention — verbally and against the request/consent form. Use a **pre-procedure pause** (time-out) mirroring WHO surgical checklist principles. Check allergies and current medications, particularly anticoagulants and antiplatelets. Consent should be informed and documented, with adequate time and information given beforehand, not at the last moment.

### 11.5.2 Anticoagulants and Antiplatelets

This is an area where practice legitimately varies between centres, and where the decision requires balancing bleeding risk (procedure-dependent) against thrombotic risk (patient-dependent). Some principles are well-established:

- Core needle biopsy usually proceeds on aspirin alone.
- For clopidogrel, direct oral anticoagulants (DOACs) and warfarin, decisions depend on the procedure type — **vacuum-assisted biopsy (VAB) and stereotactic biopsy carry higher bleeding risk** than standard core biopsy.
- Never stop dual antiplatelet therapy early after coronary stenting without specialist advice.
- For warfarin, an agreed INR threshold (often ≤2.5–3.0 for core biopsy) should be documented in local guidelines.
- Document your rationale explicitly in every case.

### 11.5.3 Local Anaesthesia

Lidocaine 1% is standard. Know the maximum safe dose

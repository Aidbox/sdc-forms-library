# Aidbox SDC Forms Library

Forms library contains next common forms:

- Active Medications
- Advance care planning
- Advanced illness and frailty
- American Urological Association (AUA) Symptom Index [AUASI]
- Demographics
- Elder Abuse Suspicion Index (EASI)
- Fall Risk
- Family History
- Female Urinary Incontinence Diagnosis (QUID)
- Functional status
- GAD-7
- History of present illness
- Lifestyle
- Living Arrangements
- Mini Cognitive Test
- PHQ2/PHQ9 Depression Form
- Pain assessment
- Past Medical History
- Past Surgical History
- Physical exam
- Problems list
- Review of systems
- Screening Tests
- Social determinants
- Substance Use
- Vitals Signs



## NOTES:

### External valuesets

Next forms requires some external valuesets to be in the Aidbox instance.

- Active Medications
- Past Medical History
- Past Surgical History
- Problems list

That valuesets stored in this repo as FTR module.

You need to enable valuesets loading via Aidbox parameter `BOX_FEATURES_FTR_PULL_ENABLE=true`.


### Extractions

Some forms don't have extraction definitions.

- Advanced illness and frailty
- Elder Abuse Suspicion Index (EASI)
- Female Urinary Incontinence Diagnosis (QUID)
- Lifestyle
- Mini Cognitive Test
- Mood Disorder Questionnaire
- Screening Tests
- Social determinants


# Phase A — Ethical Analysis of Synthetic Representation

## Introduction

Task 6 explored synthetic representation through two generation approaches: ElevenLabs synthetic audio and Vidnoz synthetic-avatar video.

Both artifacts communicated findings derived from an analysis of social-media datasets associated with the 2024 presidential election.

The purpose of Task 7 is not to create additional synthetic media. Instead, this phase examines the ethical implications of the media already created.

The analysis focuses on four dimensions:

1. Truth
2. Consent
3. Context
4. Scale

---

# Artifact Examined

The primary artifact is the ElevenLabs synthetic audio created during Task 6.

The artifact used the synthetic voice "Siren — Natural Realistic Conversational Voice."

No real person's voice was cloned.

The audio communicated statistics that had been independently calculated before generation.

A second artifact used the Vidnoz stock avatar "Annie" with the "Annie (Lifelike)" synthetic voice.

The artifacts therefore represented artificial presenters rather than simulated versions of real identifiable individuals.

---

# 1. Truth

Synthetic media introduces an important distinction between the accuracy of information and the authenticity of the person presenting it.

The presenter does not need to be real for the information to be accurate.

The Task 6 scripts were based on verified descriptive statistics.

The three analyzed datasets contained 293,058 records.

For Facebook posts with numeric interaction data, median interactions were 133 while the mean was approximately 2,210.

For 27,304 Twitter/X posts, median likes were 1,406 while the mean was approximately 6,914.

These statistics came from the underlying data.

However, the voice and avatar communicating them were synthetic.

This produces two different questions:

> Is the information accurate?

and

> Is the representation authentic?

These questions should not be treated as equivalent.

## Risk

A synthetic presenter can confidently communicate both correct and incorrect information.

Realistic delivery can make unsupported information appear authoritative.

Therefore, the quality of a synthetic presentation should never be treated as evidence that its claims are correct.

## Principle

**Substantive claims presented through synthetic media should remain independently traceable to their underlying sources.**

---

# 2. Consent

Consent becomes especially important when synthetic media reproduces a recognizable identity.

Task 6 deliberately avoided this problem by using synthetic/stock identities.

The ElevenLabs recording did not clone a real person's voice.

The Vidnoz video did not reproduce a professor, student, politician, journalist, researcher, or other identifiable person.

This substantially reduced identity-related risk.

However, the ethical situation would have changed if the same script had been narrated using a cloned professor's voice.

Even if every statistic remained correct, the artifact could falsely imply that the professor personally made or endorsed those statements.

The same concern applies to reproducing the voice or likeness of any identifiable individual.

## Principle

**A person's recognizable face, voice, or identity should not be synthetically reproduced without informed authorization.**

Consent should be specific about:

- purpose
- intended audience
- publication channel
- duration
- modification
- redistribution
- future reuse

General participation in research should not automatically be interpreted as consent to synthetic identity replication.

---

# 3. Context

The meaning and ethical risk of synthetic media can change when an artifact is separated from its original context.

Within the Task 6 GitHub repository, the synthetic nature of the artifacts is clear.

The repository contains:

- source scripts
- generation tools
- iterations
- evaluations
- disclosure
- detection results
- provenance information

However, a user could download an MP3 or MP4 and distribute it separately.

If the surrounding documentation disappeared, viewers might no longer understand why or how the artifact was created.

This means disclosure should travel with the media whenever possible.

## Detection Experiment

Context became particularly important during the Task 6 detection experiment.

The ElevenLabs recording was known to be completely synthetic.

AI Voice Detector nevertheless returned:

**AI Score: 16%**

**Verdict: Likely Human**

Only one of 19 analyzed segments was classified as "Likely AI."

Therefore, a viewer encountering the artifact without its disclosure or provenance information could potentially receive misleading reassurance from an automated detector.

## Principle

**Disclosure should be attached to the artifact itself whenever possible rather than existing only in surrounding documentation.**

---

# 4. Scale

The ethical consequences of synthetic media change substantially with scale.

Creating one clearly disclosed synthetic artifact for an academic assignment presents a different level of risk from automatically generating thousands of synthetic artifacts.

At small scale, each artifact can receive manual review.

At large scale, manual verification becomes significantly more difficult.

## Scaling Errors

Imagine an automated research communication system generating 10,000 synthetic summaries.

Even a relatively low factual error rate could produce many inaccurate artifacts.

Realistic synthetic presenters could then make those errors appear authoritative.

Synthetic-media systems therefore have the ability to scale both accurate communication and misinformation.

## Scaling Identity Misuse

Scale also affects consent.

One unauthorized identity simulation creates a consent problem.

A system capable of automatically producing thousands of personalized impersonations could amplify that harm dramatically.

## Principle

**Governance requirements should become stronger as the realism, sensitivity, reach, and scale of synthetic-media production increase.**

---

# Mitigation Landscape

No single safeguard completely addresses synthetic-media risk.

A layered approach is required.

## Disclosure

Disclosure informs audiences that content is synthetic.

### Promise

It provides viewers with important context.

### Limitation

Labels can be removed, cropped, ignored, or separated from the media.

---

# Provenance

Provenance documents how an artifact was created and modified.

The Task 6 repository provides a basic provenance record through:

- scripts
- generation platforms
- synthetic identities
- iterations
- output files
- evaluations
- detector results

Technical standards such as C2PA Content Credentials can provide additional mechanisms for recording and verifying media provenance.

### Promise

Provenance addresses the actual origin and history of an artifact rather than attempting to infer origin from appearance alone.

### Limitation

Provenance information may be lost when media is copied, transformed, or distributed through systems that do not preserve it.

---

# Detection

Automated detection attempts to infer whether an artifact is synthetic.

### Promise

It may provide useful signals when provenance is unavailable.

### Limitation

Task 6 produced a direct false negative.

A completely synthetic recording received only a 16% AI score and was classified as likely human.

Therefore, detection should not be treated as definitive evidence.

---

# Human Review

Human reviewers can examine:

- accuracy
- context
- consent
- disclosure
- potential harm
- misleading implications

### Promise

Human reviewers can evaluate contextual factors beyond technical artifact characteristics.

### Limitation

Humans can also make mistakes, and human review becomes difficult at large scale.

---

# Organizational Policy

Organizations can define rules before synthetic media is created or distributed.

Policies can establish:

- acceptable uses
- prohibited uses
- consent requirements
- review requirements
- disclosure
- incident response
- refusal criteria

### Promise

Governance can reduce risk before publication rather than relying only on detection afterward.

### Limitation

Policies only work when organizations consistently enforce them.

---

# Key Finding

The Task 6 experiment demonstrates that three concepts should remain distinct:

## Realism

How convincing an artifact appears.

## Detection

Whether an observer or automated system believes an artifact is synthetic.

## Provenance

Evidence documenting the actual origin and history of the artifact.

The ElevenLabs recording was highly realistic.

The detector classified it as likely human.

Its documented provenance nevertheless established that it was completely synthetic.

Therefore:

> **Realism is not evidence of authenticity, and detection is not proof of origin.**

---

# Reflection

Before Task 6, it was easy to imagine synthetic-media detection as a primary technical solution.

The experiment changed that view.

A detector failed to correctly classify an artifact whose synthetic origin was already known.

This demonstrates why responsible synthetic-media governance should not depend on a single technical safeguard.

A stronger system combines:

- accurate source information
- informed consent
- disclosure
- provenance
- human review
- detection
- organizational accountability

---

# Conclusion

Synthetic media is not inherently truthful or deceptive simply because it is synthetic.

The ethical consequences depend on how the artifact is created, what information it communicates, whose identity it represents, how it is disclosed, where it is distributed, and how widely it can scale.

The Task 6 experiment demonstrated that realistic synthetic content can challenge both human perception and automated detection.

Responsible use therefore requires governance before, during, and after generation.

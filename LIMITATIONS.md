# Policy Limitations and Stress Test

## Introduction

No synthetic-media governance policy can completely eliminate risk.

This document stress-tests the proposed university research-lab policy by identifying situations where its safeguards may fail or become difficult to apply.

---

# 1. Disclosure Can Be Removed

A synthetic artifact may originally contain clear disclosure.

However, another person may:

- crop a video
- remove introductory audio
- edit the artifact
- repost a short excerpt
- separate the file from its documentation

Therefore, disclosure reduces risk but cannot guarantee that every future viewer will encounter the original label.

## Response

Use disclosure within the media itself and maintain separate provenance documentation.

Where possible, technical provenance mechanisms may provide an additional layer.

---

# 2. Provenance Can Be Lost

Metadata can disappear when media is:

- converted
- compressed
- screen-recorded
- uploaded to another platform
- edited by another application

Therefore, technical provenance alone cannot guarantee persistent context.

## Response

Maintain human-readable generation records separately from the artifact.

Repository documentation should include scripts, tools, dates, iterations, and publication information.

---

# 3. Detection Can Fail

Task 6 directly demonstrated this limitation.

A completely synthetic ElevenLabs recording received only a 16% AI score and was classified as "Likely Human."

Therefore, a detector may produce false negatives.

False positives are also possible in principle, meaning authentic media could potentially be incorrectly treated as synthetic.

## Response

Detection should be treated as a supplementary signal.

It should not override known provenance without additional investigation.

---

# 4. Consent Can Become Ambiguous

A person may authorize one synthetic use but object to later reuse.

For example, someone could consent to a synthetic voice for an internal educational demonstration but not for public social-media distribution.

## Response

Consent should be purpose-specific.

Authorization should document:

- audience
- distribution
- duration
- modification
- redistribution
- future reuse

---

# 5. Human Review Is Imperfect

Human reviewers can miss factual errors, misunderstand context, or underestimate potential harm.

Review quality may also decline when reviewers process many artifacts.

## Response

Higher-risk artifacts should receive additional review or specialized expertise.

Organizations should periodically evaluate their review process rather than assuming that human oversight automatically eliminates risk.

---

# 6. Scale Creates Pressure

A review process that works for five artifacts may not work for 5,000.

Large-scale synthetic-media generation creates pressure to automate approval.

However, removing human review can allow errors to propagate quickly.

## Response

Governance should scale with production.

Higher production volume may require:

- automated pre-screening
- sampling
- risk classification
- multiple reviewers
- publication limits
- stronger audit processes

---

# 7. Accurate Information Can Still Mislead

An artifact may contain individually accurate facts while creating a misleading overall impression through selective presentation.

For example, presenting only a mean without a median could technically report a correct number while obscuring a highly skewed distribution.

This issue appeared directly in the underlying Task 6 data analysis.

## Response

Review should evaluate not only whether individual claims are numerically correct but also whether important context has been omitted.

---

# 8. Disclosure Does Not Guarantee Understanding

A viewer may see an "AI-generated" label without understanding what was generated.

The label could refer to:

- voice
- avatar
- script
- editing
- translation
- the entire artifact

## Response

Disclosure should be sufficiently specific.

For example:

"This video uses a synthetic AI avatar and AI-generated voice. The statistical claims were independently calculated from the source dataset."

---

# 9. Policies Depend on Enforcement

A strong written policy provides little protection if staff can ignore it without consequence.

## Response

Governance requires:

- assigned responsibility
- documented review
- escalation procedures
- periodic audits
- incident review

Policy should operate as an organizational process rather than merely a written statement.

---

# 10. Technology Changes Quickly

Generation and detection technologies continue to evolve.

A policy based on the capabilities of today's systems may become outdated.

## Response

The organization should periodically reassess:

- generation capabilities
- detection reliability
- provenance standards
- organizational risks
- disclosure practices

Policies should be treated as living governance documents.

---

# Overall Stress-Test Result

The proposed policy cannot guarantee that synthetic media will never be misused or misunderstood.

Its purpose is instead to reduce risk through multiple independent safeguards.

The strongest approach is layered:

**Truth verification**

+

**Consent**

+

**Disclosure**

+

**Provenance**

+

**Human review**

+

**Detection**

+

**Incident response**

No single layer is sufficient by itself.

---

# Final Reflection

The Task 6 experiment demonstrated why this layered approach is necessary.

The artifact's synthetic origin was certain because its generation process was documented.

Yet an automated detector classified it as likely human.

This means that a system depending entirely on detection would have failed.

The policy therefore prioritizes documented provenance and responsible generation practices while treating detection as supplementary evidence.

The goal is not perfect control.

The goal is to create enough independent safeguards that the failure of one mechanism does not automatically cause the entire governance system to fail.

#  Security Controls Matrix

A sample security controls matrix mapping **21 real-world risks** to the specific
controls that mitigate them — built to demonstrate practical GRC/security control
mapping, the way it's actually done on the job.

> **Read it as:** "If [risk] happens, here's the control that stops or catches it,
> what kind of control it is, and who owns making sure it actually works."

---

## 📌 Why this exists

Anyone can list risks. Anyone can list controls. The actual skill in GRC is
**connecting the two correctly** — knowing that a firewall doesn't stop phishing,
that a badge reader doesn't stop malware, and that every control has a type
(how it's enforced) and a function (when it acts in the risk timeline).

This matrix is a small, honest demonstration of that skill.

---

##  What's inside

| File | What it is |
|---|---|
| `Security_Controls_Matrix.xlsx` | The full matrix — 21 rows, 6 columns |

---

## 🔍 How to read the columns

| Column | What it means | Example |
|---|---|---|
| **Risk** | The thing that could go wrong | `Phishing` |
| **Control** | The specific safeguard that addresses it | `Security Awareness Training` |
| **Control Type** | *How* the control is enforced | `Administrative`, `Technical`, or `Physical` |
| **Control Function** | *When* the control acts | `Preventive`, `Detective`, or `Corrective` |
| **Owner** | Who's accountable for it | `HR`, `IT`, `Facilities`, etc. |
| **Status** | Is it actually in place yet | `Implemented`, `In Progress`, `Planned` |

### Control Type — the "how"
- 🗒️ **Administrative** — policies, training, processes (people-driven)
- 💻 **Technical** — software/hardware enforced (system-driven)
- 🚪 **Physical** — locks, badges, physical barriers (environment-driven)

### Control Function — the "when"
- ⛔ **Preventive** — stops the risk *before* it happens
- 🔎 **Detective** — catches it *while or after* it happens
- 🛠️ **Corrective** — fixes the damage *after* it's caught

---

## 📊 Quick glance at what's covered

This isn't a one-trick list — it spans the full spread of a typical security
program:

- **Identity & Access** — MFA, access reviews, offboarding automation, least privilege
- **Endpoint & Network** — EDR, encryption, patch management
- **Data Protection** — encryption in transit and at rest
- **People Risk** — phishing simulations, security awareness training
- **Third-Party Risk** — vendor security assessments
- **Operational Resilience** — backups, disaster recovery testing, incident response
- **Physical Security** — badge access, fire suppression
- **Governance** — segregation of duties, change approval workflows

21 controls, 3 control types, 3 control functions, 8+ risk categories — deliberately
broad so it reads as real program coverage, not a narrow checklist.

---

## 🧠 The thinking behind it

Every row follows the same logic used in real security programs:

1. **Start with the risk** — what's the actual bad outcome we're worried about?
2. **Pick the right control type** — does this need a policy, a piece of technology,
   or a physical barrier?
3. **Classify its function** — is this stopping the risk, catching it, or cleaning
   up after it?
4. **Assign ownership** — a control with no owner doesn't get maintained.
5. **Track status honestly** — not everything is "Implemented" on day one, and a
   real matrix shows that.

---

## ⚠️ Disclaimer

This is a fictional, illustrative dataset built for portfolio purposes. It does
not represent any real company's actual control environment.

---

## 🔗 Related work

Pair this with my Risk Register repo — the risk register identifies and scores
the risks; this matrix shows the controls addressing them. Together they cover
both halves of core GRC work: **assessing risk** and **mapping controls**.
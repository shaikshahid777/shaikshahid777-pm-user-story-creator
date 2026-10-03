<!-- SHOWCASE_START --><div align="center">[![Typing](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=900&lines=shaikshahid777%20pm%20user%20story%20creator;AI%20%7C%20Automation%20%7C%20Engineering;Explore%20the%20project%20%F0%9F%9A%80)](https://github.com/shaikshahid777/shaikshahid777-pm-user-story-creator)<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:161B22,100:58A6FF&height=110&section=header&text=shaikshahid777-pm-user-story-creator&fontSize=26&fontColor=FFFFFF&animation=twinkling&fontAlignY=65" width="100%" alt="Animated project banner"/>

[![Repository](https://img.shields.io/badge/Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shaikshahid777/shaikshahid777-pm-user-story-creator) [![Issues](https://img.shields.io/badge/Report-Issue-red?style=for-the-badge&logo=github)](https://github.com/shaikshahid777/shaikshahid777-pm-user-story-creator/issues/new) [![Stars](https://img.shields.io/github/stars/shaikshahid777/shaikshahid777-pm-user-story-creator?style=for-the-badge&logo=github)](https://github.com/shaikshahid777/shaikshahid777-pm-user-story-creator/stargazers) [![Fork](https://img.shields.io/github/forks/shaikshahid777/shaikshahid777-pm-user-story-creator?style=for-the-badge&logo=github)](https://github.com/shaikshahid777/shaikshahid777-pm-user-story-creator/fork) [![Profile](https://img.shields.io/badge/Profile-Visit-0A66C2?style=for-the-badge&logo=github)](https://github.com/shaikshahid777)</div>

> ✨ **Project Showcase Mode:** animated banner • interactive navigation • live repository actions

[🚀 Repository](https://github.com/shaikshahid777/shaikshahid777-pm-user-story-creator) · [🐞 Report Issue](https://github.com/shaikshahid777/shaikshahid777-pm-user-story-creator/issues/new) · [⭐ Star](https://github.com/shaikshahid777/shaikshahid777-pm-user-story-creator/stargazers) · [🔱 Fork](https://github.com/shaikshahid777/shaikshahid777-pm-user-story-creator/fork) · [👤 Profile](https://github.com/shaikshahid777)

<!-- SHOWCASE_END -->

# PM User Story Creator

> A product-requirement copilot that turns raw feature ideas into clean, testable Agile tickets.

[![Project](https://img.shields.io/badge/Project-PM%20User%20Story%20Creator-1f6feb)](https://chatgpt.com/share/6aba581c-15a4-83e8-a4ac-a6519cd7b6f9)
[![Assessment](https://img.shields.io/badge/Assessment-Topic%204-8250df)](https://github.com/shaikshahid777/shaikshahid777-pm-user-story-creator)
[![Output](https://img.shields.io/badge/Output-Jira%20%2F%20Linear-ready-2ea043)](https://github.com/shaikshahid777/shaikshahid777-pm-user-story-creator)
[![Demo](https://img.shields.io/badge/Loom-Demo-625df5)](https://www.loom.com/share/c6565a2c63c74533ad65d8a1f0d520a8)

## Overview

**PM User Story Creator** is a ChatGPT Project configured to translate raw and unstructured feature requests into a standard four-part Agile ticket:

1. **User Story**
2. **Acceptance Criteria**
3. **Edge Cases**
4. **Metadata**

The configuration enforces a minimum of 4 testable acceptance criteria, at least 3 edge cases with expected system responses, priority with justification, clean Markdown, scope control, and product-level language.

## Design principles

| Principle | What the project enforces |
|---|---|
| **Clarity** | Standard Agile user-story structure |
| **Testability** | Observable acceptance criteria |
| **Completeness** | Minimum acceptance criteria + edge cases |
| **Scope discipline** | No unrelated feature additions |
| **Product-level output** | No schema, SQL, API, code, or framework leakage |
| **Ticket-ready formatting** | Structured Markdown for Jira/Linear |
| **Prompt safety** | Exact refusal response for instruction-override attempts |

## End-to-end flow

```text
Raw feature request
        ↓
Project instructions + source guidance
        ↓
Scope & product-level guardrails
        ↓
Standard Agile transformation
        ↓
┌───────────────────────────────┐
│ User Story                    │
│ Acceptance Criteria (≥4)      │
│ Edge Cases (≥3)               │
│ Metadata: Priority + reason   │
└───────────────────────────────┘
        ↓
Jira / Linear copy-paste-ready ticket
```

## Validation evidence

| Test | Purpose | Result |
|---|---|---|
| Password reset | Core end-to-end transformation | ✅ PASS |
| Order status notification | Different feature type | ✅ PASS |
| Scope creep attempt | Prevent unrequested functionality | ✅ PASS |
| Technical-detail request | Prevent implementation leakage | ✅ PASS |
| Prompt injection | Enforce exact refusal behavior | ✅ PASS |

## Supporting sources

- `01_Jira_User_Story_Template_Guide.docx`
- `02_Product_Ticketing_Conventions.docx`
- `03_Agile_Acceptance_Criteria_Edge_Cases_Guide.docx`

See [`docs/source-materials.md`](docs/source-materials.md) for how they support the configuration.

## Assessment evidence

- 🎥 **Loom Demo:** [Open recording](https://www.loom.com/share/c6565a2c63c74533ad65d8a1f0d520a8)
- 🤖 **ChatGPT Project:** [Open shared project](https://chatgpt.com/share/6aba581c-15a4-83e8-a4ac-a6519cd7b6f9)
- 📄 **LMS Submission PDF:** [Open PDF](docs/PM_User_Story_Creator_LMS_Submission.pdf)
- ✅ **Validation Report:** [Open report](docs/validation-report.md)
- ⚙️ **Configuration Record:** [Open configuration](docs/project-configuration.md)

## Repository structure

```text
.
├── README.md
├── docs/
│   ├── project-configuration.md
│   ├── source-materials.md
│   ├── validation-report.md
│   └── PM_User_Story_Creator_LMS_Submission.pdf
└── sources/
    ├── 01_Jira_User_Story_Template_Guide.docx
    ├── 02_Product_Ticketing_Conventions.docx
    └── 03_Agile_Acceptance_Criteria_Edge_Cases_Guide.docx
```

## Project links

| Resource | Link |
|---|---|
| Live Project | [ChatGPT Project Share](https://chatgpt.com/share/6aba581c-15a4-83e8-a4ac-a6519cd7b6f9) |
| Demo | [Loom](https://www.loom.com/share/c6565a2c63c74533ad65d8a1f0d520a8) |
| Repository | [GitHub](https://github.com/shaikshahid777/shaikshahid777-pm-user-story-creator) |

---

**Built for Topic 4 — PM User Story Creator Capstone**

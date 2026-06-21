# ATS Resume Optimizer

**A complete skill for Grok (xAI)** that transforms resumes so they **pass modern Applicant Tracking Systems (ATS)** — including AI-powered semantic parsers — and **rank higher** with recruiters.

This skill provides a structured, repeatable workflow for keyword tailoring, ATS-safe formatting, quantified achievement statements, and strategic content restructuring.

## ✨ What It Does

- Analyzes job descriptions and maps requirements to your experience
- Optimizes for **semantic matching** (2026+ ATS use NLP/embeddings, not just keyword count)
- Strengthens bullets with strong action verbs + real metrics
- Enforces clean, parseable formatting (single-column, standard headings, .docx preferred)
- Includes ready-to-use references: best practices, action verb lists, audit checklist, and resume template
- Helps you exceed ATS scoring and stand out in the 6–10 second recruiter skim

## 🚀 How to Use

Just talk to Grok naturally:

> "Use ats-resume-optimizer to improve my resume for this job description..."
> "Make my resume ATS-friendly and tailor it to this JD with stronger metrics"
> "Optimize my resume for high ATS ranking and give me before/after examples"

Provide the job description (JD) and your current resume. The skill will:
1. Extract key requirements and keywords
2. Audit your current resume
3. Deliver optimized sections or a full rewritten version in clean markdown
4. Provide an ATS audit checklist score and specific recommendations

You can then ask Grok to generate a polished `.docx` or `.pdf` file using its document skills.

## 📁 Repository Contents

```
ats-resume-optimizer/
├── SKILL.md                          # Main skill definition & workflow
├── references/
│   ├── ats-best-practices.md         # 2026 ATS guidelines & semantic matching
│   ├── action-verbs.md               # Categorized strong action verbs
│   └── ats-audit-checklist.md        # Pass + exceed verification checklist
└── assets/
    └── ats-resume-template.md        # Clean ATS-friendly resume structure template
```

## 🛠️ Adding This Skill to Your Grok Instance

(For users running custom or self-hosted Grok setups)

1. Clone or download this repository
2. Copy the `ats-resume-optimizer` folder into your Grok skills directory (usually `~/.grok/skills/` or equivalent)
3. The skill will be automatically discovered and can be triggered by natural language

## 📋 Key Best Practices Included

- Single-column layout, standard fonts, clean .docx export
- Natural contextual keyword integration (70-90% critical term coverage)
- Every bullet = Action Verb + Scope + Quantified Result
- Tailored Professional Summary formula
- Modern semantic fit for AI-powered ATS (BERT-style matching, cosine similarity)

## 🤝 Contributing

Pull requests and improvements are welcome! Especially:
- Additional industry-specific guidance (healthcare, trades, creative, etc.)
- More example before/after transformations
- Enhanced templates

## 📜 License

This skill is provided as a helpful resource for the Grok/xAI community. Feel free to use, adapt, and share.

---

Created with ❤️ using Grok and the skill-creator workflow.  
Original location: Grok user skills directory
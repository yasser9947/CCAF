# CCAF Study Reference — مرجع شهادة المعماري المعتمد من Claude

Bilingual (العربية / English) interactive study reference for the
**Claude Certified Architect – Foundations (CCA-F)** certification exam,
built in the معلم (mu3allim) educational style.

مرجع دراسي تفاعلي ثنائي اللغة لشهادة **Claude Certified Architect – Foundations**،
مبني على دليل الاختبار الرسمي من Anthropic (الإصدار 0.2 — يونيو 2026).

## Structure | البنية

الموقع شجرة: صفحة رئيسية، وقسم كامل لكل دومين (ملخص + صفحة درس لكل موضوع رسمي)، واختبار تجريبي.
The site is a tree: a hub page, a full section per domain (overview + one lesson page per official task statement), and a practice exam.

| Section | المحتوى | Content |
|---|---|---|
| [index.html](index.html) | الرئيسية: نظرة شاملة، الدومينز، السيناريوهات، خطة المذاكرة | Hub: overview, domains, scenarios, study plan |
| [domain-1/](domain-1/index.html) | الدومين 1: البنية الوكيلية والتنسيق (27%) — ملخص + 7 مواضيع | Domain 1: Agentic Architecture & Orchestration (27%) — overview + 7 topics |
| [domain-2/](domain-2/index.html) | الدومين 2: تصميم الأدوات وتكامل MCP (18%) — ملخص + 5 مواضيع | Domain 2: Tool Design & MCP Integration (18%) — overview + 5 topics |
| [domain-3/](domain-3/index.html) | الدومين 3: إعداد Claude Code وسير العمل (20%) — ملخص + 6 مواضيع | Domain 3: Claude Code Configuration & Workflows (20%) — overview + 6 topics |
| [domain-4/](domain-4/index.html) | الدومين 4: هندسة البرومبت والمخرجات المهيكلة (20%) — ملخص + 6 مواضيع | Domain 4: Prompt Engineering & Structured Output (20%) — overview + 6 topics |
| [domain-5/](domain-5/index.html) | الدومين 5: إدارة السياق والموثوقية (15%) — ملخص + 6 مواضيع | Domain 5: Context Management & Reliability (15%) — overview + 6 topics |
| [practice-exam.html](practice-exam.html) | الاختبار التجريبي: 20 سؤال (منها الـ 12 الرسمية) + استراتيجية يوم الاختبار | Practice exam: 20 questions (incl. the 12 official samples) + exam-day strategy |

**37 pages · 80+ diagrams · 146 interactive quiz questions**

## Deploy on GitHub Pages | النشر

1. Push this repository to GitHub.
2. **Settings → Pages → Source**: `Deploy from a branch`, branch `main`, folder `/ (root)`.
3. The site goes live at `https://<username>.github.io/<repo>/`.

الصفحات ملفات HTML ثابتة بالكامل (Tailwind + Prism + Lucide عبر CDN) — لا تحتاج أي build.

## Features | المميزات

- Language toggle (AR ⇄ EN) persisted across pages via `localStorage`
- Every official task statement covered, per the official Exam Guide
- Interactive quizzes on every domain page + a 20-question practice exam
  (including all 12 official sample questions with full explanations)
- 4-week study plan with a persistent checklist
- Responsive, RTL/LTR aware

---

> Unofficial study material — the official source is Anthropic's Exam Guide.
> مرجع غير رسمي أُعدّ لأغراض الدراسة — المصدر الرسمي هو دليل الاختبار من Anthropic.
>
> أُعدّ هذا المرجع بأسلوب معلم التعليمي.

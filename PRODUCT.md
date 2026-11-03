# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Primary: technical recruiters and hiring managers evaluating Aditya Kumar for software/ML internships. They skim in seconds, look for proof (research, shipped code, measurable results), then move to contact or GitHub. Secondary: technical peers and academic contacts who read methods and results more closely.

## Product Purpose

A personal portfolio site that converts a recruiter's seconds-long skim into contact. It presents who Aditya is, his IEEE ICCE first-author research, industry experience, six featured projects with evidence, skills, and contact paths. Success is a visitor reaching email, GitHub, LinkedIn, or the resume download.

## Positioning

A CS undergraduate portfolio whose proof is unusually concrete for its level: a first-author IEEE ICCE 2025 paper on video-based ASL translation, plus shipped on-device ML systems with reported metrics (NBA MAE 4.52, ROUGE-L 0.4614 → 0.5357 on a synthetic pipeline split). No neighboring student portfolio can truthfully copy that combination.

## Operating Context

Static site hosted on GitHub Pages (no build step, plain HTML/CSS/JS). Visitors arrive from resume links, GitHub profile, LinkedIn, or direct URL, on desktop and mobile viewports. Content is fixed and factual, sourced from the resume and public GitHub repos.

## Capabilities and Constraints

- Static only: must keep working as raw files on GitHub Pages (`.nojekyll`, relative asset paths).
- All copy, facts, sections, and project claims are frozen by user decision; redesign changes visual design only.
- Reported metrics must keep their honest framing (e.g., the ROUGE result is a pipeline test on 3 synthetic held-out examples, not a general-quality claim).
- Resume PDF download, email/GitHub/LinkedIn links, and theme toggle must keep working.
- Accessibility: semantic HTML, keyboard operability, visible focus, reduced-motion support.

## Brand Commitments

Name "Aditya Kumar", UC Irvine CS identity, IEEE ICCE 2025 first-author status. No logo, typeface, palette, or mascot commitments exist. GitHub avatar hotlink is the only portrait asset.

Standing preference (recorded after direction round 2): the category standard. The user chose the canon on purpose over two full direction rounds — future work executes familiar portfolio conventions at full fidelity, without irony or smuggled quirk. The craft bar is set collectively by three exemplars: brittanychiang.com (restrained dark developer portfolio), leerob.io (minimal content-forward personal site), paco.me (playful precise personal site with interactive details).

## Evidence on Hand

- Resume withheld from the public site per user request (Nov 2026).
- GitHub profile `github.com/adityatheperson` (21 public repos); featured repos with verified READMEs: `nbapredictor`, `lorasummarizer`, `ZoomRecorder`, `imposter`, `Nextup`, `ZotMacros`.
- Paper PDF at `assets/Aditya-Kumar-ASL-Paper-ICCE-2025.pdf`, linked from the Research section.
- No testimonials, headshots beyond the GitHub avatar, or custom illustrations; demonstration content must be authored, factual claims must not be invented.

## Product Principles

1. Proof before personality: every visual choice must make evidence faster to find, never decorate over it.
2. Factual restraint: show only true, verifiable claims; label synthetic or illustrative material as such.
3. Recruiter-speed hierarchy: identity, proof, and contact reachable within seconds on any viewport.
4. Static-site honesty: no fake interactivity, no backend-dependent features, everything works from files.
5. Content freeze: the redesign replaces the visual world, never the words or structure the user approved.

## Accessibility & Inclusion

Semantic landmarks, skip link, keyboard-operable controls, visible focus states, `prefers-reduced-motion` support, and color contrast that holds in both themes.

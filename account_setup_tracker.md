# PhD Accounts Setup Tracker

Last updated: 2026-05-25
Owner: Piter Zacari Garcia Bautista
Maintained by: Copilot session workflow

## 1) Account Status Dashboard

| Account | Status | URL | Notes |
|---|---|---|---|
| ORCID | Completed | https://orcid.org/my-orcid?orcid=0009-0008-5129-2820 | Core profile already established earlier in session history. |
| ResearchGate | Completed (core) | https://www.researchgate.net/profile/Piter-Zacari-Garcia-Bautista | Verified badge shown on profile; dual institution + education entries complete. |
| OpenReview | Completed (core) | https://openreview.net/profile?id=~Piter_Zacari_Garcia_Bautista1 | Profile edited with dual institutional history and expertise. |
| Google Scholar | Deferred by user (no published papers yet) | https://scholar.google.com/citations?view_op=new_profile&hl=en | User confirmed no published papers to claim at this stage; article-claim step intentionally skipped for now. |
| Semantic Scholar | Completed (core) | https://www.semanticscholar.org/ | Account access confirmed; settings updated and saved (name + academic website + role baseline). |
| Academia.edu | Completed (core) | https://rit.academia.edu/garciapiter | Existing account accessed; profile identity, dual affiliation, bio, supervisors, and LinkedIn link updated. |
| LinkedIn | Completed (core refinement) | https://www.linkedin.com/in/garciapiterz/ | Authenticated profile accessed; intro name normalized to full form for cross-platform consistency. |
| GitHub | Completed (core curation) | https://github.com/pzg8794 | Profile metadata updated, links aligned, and pinned repositories curated to current research portfolio. |

## 2) Information Applied To Profiles

### Identity / Links
- Full name: Piter Zacari Garcia Bautista
- Preferred contact email used for account flows: pzg8794@g.rit.edu
- Website: https://garciapiterz.com
- ORCID: https://orcid.org/0009-0008-5129-2820
- LinkedIn: https://www.linkedin.com/in/garciapiterz/

### Current institutional backing represented
- Rochester Institute of Technology
  - Role: Graduate Assistant
  - Department: Software Engineering
- University of Rochester
  - Role: Student Teaching Intern (OpenReview labels this as Intern)
  - Unit: Warner School of Education

### Education represented
- University of Rochester
  - Master of Science
  - Teaching Computer Science K-12
- Rochester Institute of Technology
  - Master of Science
  - Data Science / AI / Bioinformatics (platform-specific wording varies)

### Primary research themes used
- Quantum networking
- Entanglement routing
- Multi-armed bandits / contextual or neural bandits
- Qubit allocation
- Fair AI
- Equitable bioinformatics
- Inclusive computer science education

## 3) Evidence Sources Used (workspace)

- /Users/pitergarcia/DataScience/Semester4/GA-Work/quantum_project_hub/setup_files/docs/planning/Spring-2026-Master-Plan-Final.md
- /Users/pitergarcia/DataScience/Semester5/Semester3(UofR)/TeachingPlacement/coursework/expectations/letter-of-expectations-spring-2026-work.md
- /Users/pitergarcia/DataScience/Semester5/Semester3(UofR)/TeachingPlacement/pine-brook-elementary/teaching-placement-internship-graphic-model-notes.md
- /Users/pitergarcia/DataScience/Semester5/Scholarship/PhD-Application-Strategy-Plan.md
- /Users/pitergarcia/DataScience/Semester5/Scholarship/scholarship_resume.md

## 4) Platform-specific outcomes

### ResearchGate
Completed updates include:
- UofR added as current affiliation
- UofR education entry added
- Department wording polished to Warner School of Education
- Profile shows both institutions and current roles

### OpenReview
Completed updates include:
- Career history now includes both:
  - Intern, Warner School of Education, University of Rochester (rochester.edu)
  - Graduate student, Software Engineering, Rochester Institute of Technology (rit.edu)
- Expertise and links already present and retained
- Profile saves validated successfully

### Google Scholar
Current state:
- Profile setup form (name/affiliation/interests/homepage) is populated
- Wizard advances to article-selection step but suggestions are unrelated
- Manual article-search mode opened (Groups/Articles flow)
- Verified-title searches were attempted from CV publication lines but returned unrelated/noisy matches
- Additional exact-title searches were attempted using canonical artifact names from the RESEARCH repo index
  - qRL Reinforcement Learning Routing for Quantum Entanglement Networks -> one hit found, but authored by different researchers
  - MAB Adversarial Implementation Test Framework -> no match
  - Integration Plan: Sheeraja's UDRM into Quantum Path Optimization -> no match
- Additional name-based search was attempted (`Piter Zacari Garcia Bautista`) but returned unrelated author-name collisions
- Canonical quantum artifact titles were extracted from `pzg8794/RESEARCH` (`MASTER_RESEARCH_INDEX.md` + `TODO_PHD_RESEARCH.md`) and used for strict matching:
  - `qRL_Reinforcement_Learning_Routing_for_Quantum_Entanglement_Networks.pdf`
  - `MAB-Adversarial_Implementation-Test_Framework.pdf`
  - `Integration Plan: Sheeraja's UDRM into Quantum Path Optimization`
- Additional canonical filename/title-variant searches were attempted in Scholar and returned no safe self-authored claim
- RESEARCH index provides canonical filenames/titles but does not include DOI/arXiv/publisher identifiers
- Local Google Drive mounted scan did not surface those canonical PDFs/IDs in accessible synced files
- Google Doc source provided by user (`MASTER_RESEARCH_INDEX - PhD Applications`) was accessed and parsed in-session for exact paper titles and direct Drive links
- Doc-based title searches run in Scholar:
  - `NGS Reanalysis Study on Global DEG Discovery in a DRG Mouse Dataset` -> no match
  - `Big Data Medical Diagnosis` -> only unrelated external results
  - `MAB-Adversarial_Implementation-Test_Framework` (and spacing variants) -> no match
- Additional doc-derived technical query (`"EXPNeuralUCB" quantum entanglement`) surfaced a title-level match:
  - `Quantum entanglement path selection and qubit allocation via adversarial group neural bandits`
  - Authors shown in Scholar: `Y Huang, L Wang, J Xu` (not Piter) -> rejected as unsafe claim
- Broad author-string query (`"Piter Garcia"`) returned mixed collisions (`P Garcia Rios`, `P García`, and unrelated topics), with no verified match to portfolio artifacts -> rejected as unsafe claim
- Direct Drive artifact metadata extraction completed from source files:
  - `HTSA_Paper-Phase2.docx` (44 pages): title page confirms `NGS Reanalysis Study on Global DEG Discovery in a DRG Mouse Dataset`, draft type, and contributors `Nikhi Boggavarapu`, `Sam Kopelev`, `Piter Garcia`
  - `Big Data Medical Diagnosis - Paper3.pdf` (8 pages): title page confirms `Piter Garcia`, `May 13, 2014`, and Rochester Institute of Technology heading
  - `MAB-Adversarial_Implementation-Test_Framework.pdf` (188 pages): title page confirms framework label/date and cites external reference paper `Huang, Y., Wang, L., & Xu, J. (2024), arXiv:2411.00316v1`
- Metadata-informed Scholar retries still produced no safe claimable result:
  - `"NGS Reanalysis Study on Global DEG Discovery in a DRG Mouse Dataset" "Piter Garcia"` -> no match
  - `"Big Data Medical Diagnosis" "Piter Garcia" 2014` -> no match
  - `"MAB-Adversarial_Implementation-Test_Framework"` -> no match
  - `"Quantum entanglement path selection and qubit allocation via adversarial group neural bandits"` -> external authors (`Y Huang, L Wang, J Xu`), rejected
- Wizard constraint observed: current Scholar onboarding step exposes search-based selection only; no visible `Add article manually` action in-session
- Doc also labels `qRL_Reinforcement_Learning_Routing_for_Quantum_Entanglement_Networks.pdf` as external/reference, so it remains excluded from self-claiming
- User confirmed no published papers are available to claim right now
- Scholar publication-claim completion is intentionally deferred to a future cycle

Recommended next action:
- Defer Scholar article-claiming until at least one publication is publicly indexed or otherwise claimable
- Continue wrapping up remaining platform/profile tasks outside Scholar claiming

### Semantic Scholar
Current state:
- Account access confirmed (signed-in session active)
- Account settings page reached (`/me/account/manage`)
- Name fields updated to match profile identity:
  - Given name: Piter Zacari
  - Family name: Garcia Bautista
- Academic website set to: https://garciapiterz.com/
- Save confirmed by in-app "Successfully saved!" banner

Recommended next action:
- Optional: tune contact and alert preferences

### Academia.edu
Current state:
- Existing signed-in account discovered and profile edit page accessed
- Name normalized to remove duplicate middle marker and align identity as `Piter Zacari GARCIA BAUTISTA`
- Added dual affiliation on profile:
  - Rochester Institute of Technology, Computer Science, Graduate Assistant
  - University of Rochester, Warner School of Education, Graduate Student
- Added/updated profile bio with research themes and ORCID link
- Added supervisors: Dr. Daniel Krutz and Dr. Travis Desell
- LinkedIn social profile added/confirmed

Noted issue:
- Previously flagged email opt-out warning for `pzg8794@g.rit.edu` was resolved via Email Notifications re-enable flow

Recommended next action:
- Optional: keep notifications tuned to preference (issue no longer blocking)

### LinkedIn
Current state:
- Authenticated profile session confirmed
- Intro editor opened and saved successfully
- Name normalized from `Piter Garcia` to `Piter Zacari Garcia Bautista`
- Public profile URL retained as `garciapiterz`

Recommended next action:
- Optional: refine headline/About text only if needed for application-specific wording

### GitHub
Current state:
- Authenticated settings access confirmed and profile saved
- Name aligned to `Piter Zacari Garcia Bautista`
- Bio updated to current research identity (quantum networking, fairness-aware AI, bioinformatics)
- Website and social links aligned (`garciapiterz.com`, LinkedIn, ORCID)
- Pinned repositories curated to application-facing set currently available in pin selector:
  - `CV_Piter-Garcia`
  - `quantum_project_hub`
  - `QuantumFaultTolerant`
  - `RESEARCH`

Documentation hardening pass (repo-level):
- `pzg8794/quantum_project_hub`: README upgraded and pushed (`main`)
- `pzg8794/QuantumFaultTolerant`: subdirectory README guidance upgraded and pushed (`main`)
- `pzg8794/GA-Work`: superproject submodule pointers updated and pushed to include latest docs commits
- `pzg8794/quantum_project`: remote already contains expanded framework README; local rebase conflict resolved with no additional diff to push
- `pzg8794/QuantumFaultTolerant` (second pass): archive/checkpoint/figure README policies clarified and pushed (`main`)
- `pzg8794/GA-Work` (second pass): QuantumFaultTolerant submodule pointer updated to latest documentation commit
- Nested external testbed repos updated locally but push blocked by remote permissions:
  - `junaid572/RL_Entanglement_Routing`
  - `iCMAB/CMAB-CoMM`

Recommended next action:
- Optional: continue documentation upgrades in additional owned repositories (`GA-Work`, `quantum_project`, `QuantumFaultTolerant`) and push iteratively

## 5) Next Account Queue

1. Personal website profile audit (bio consistency, links to ORCID/ResearchGate/OpenReview)
2. Optional publication-platform placeholders (Zenodo, Figshare) for future public outputs
3. Additional repository-by-repository documentation polishing in owned repos
4. Return to Google Scholar only when a claimable publication record exists

## 6) Change Log

- 2026-05-24: Created tracker file in CV_Piter-Garcia repo.
- 2026-05-24: Logged ResearchGate completion state and UofR additions.
- 2026-05-24: Logged OpenReview completion state and dual-domain conflict coverage.
- 2026-05-24: Logged Google Scholar blocker (no safe article claims yet).
- 2026-05-24: Started Semantic Scholar signup flow and logged current pending step.
- 2026-05-24: Google Scholar advanced to manual article-search mode; no verified exact matches selected.
- 2026-05-24: Semantic Scholar signup methods tested (Google/Institution/Email); auth handoff remained blocked in-session.
- 2026-05-24: Google auth advanced to RIT SSO login page (credential checkpoint reached).
- 2026-05-24: Semantic Scholar sign-in succeeded and account settings were saved successfully.
- 2026-05-24: Google Scholar exact-title checks run using RESEARCH repo canonical artifact names; no safe claim selected.
- 2026-05-24: Academia.edu profile updated with dual affiliation, bio, supervisors, and LinkedIn.
- 2026-05-24: Academia.edu name normalized from `Piter Zacari Z GARCIA BAUTISTA` to `Piter Zacari GARCIA BAUTISTA`.
- 2026-05-24: Academia.edu email notification warning resolved using in-account re-enable action.
- 2026-05-24: Google Scholar step 2 continued with strict safe-claim policy; qRL hit rejected (different authors), additional exact/name queries produced no safe claim.
- 2026-05-24: Canonical publication titles sourced from RESEARCH index and retested in Scholar; no DOI/arXiv identifiers available yet for safe claim completion.
- 2026-05-25: User-provided MASTER_RESEARCH_INDEX Google Doc parsed for titles/links; Scholar checks repeated with doc-derived exact titles and still no safe claim selected.
- 2026-05-25: EXPNeuralUCB/quantum query produced one title-level hit, but authors were external (`Y Huang, L Wang, J Xu`), so claim was rejected.
- 2026-05-25: Broad `"Piter Garcia"` Scholar sweep returned ambiguous author collisions and unrelated works; no safe claim selected.
- 2026-05-25: Citation metadata extracted directly from top Drive artifacts (HTSA Phase2, Big Data Paper3, MAB framework) and used for one more targeted Scholar pass; still no safe self-authored claim available.
- 2026-05-25: Checked Scholar onboarding UI for manual article entry path; only search-based claiming was visible in this state.
- 2026-05-25: User confirmed no published papers are available yet; Scholar claiming marked deferred by request.
- 2026-05-25: Added concrete next-profile priority queue to continue efficiently after Scholar deferral.
- 2026-05-25: LinkedIn profile intro finalized; name normalized to `Piter Zacari Garcia Bautista` and saved.
- 2026-05-25: GitHub wrap-up started; public profile audited and curation plan prepared, but settings edit path in this browser session requires sign-in.
- 2026-05-25: GitHub profile finalized after sign-in (bio/links/pins), and documentation hardening pass initiated across accessible repositories.
- 2026-05-25: Documentation pass extended and pushed across owned repos (`quantum_project_hub`, `QuantumFaultTolerant`, and `GA-Work` submodule pointer sync); `quantum_project` reconciled with upstream during non-fast-forward rebase.
- 2026-05-25: Documentation second pass pushed for `QuantumFaultTolerant` (legacy/archive/checkpoint/figure README clarifications) with corresponding `GA-Work` submodule pointer update.
- 2026-05-25: `pzg8794/RESEARCH` updated with `APPLICATIONS/PhD/PUBLIC_REPOSITORY_SHOWCASE_PLAN.md` and linked from root docs to define which repos should stay public for applications.

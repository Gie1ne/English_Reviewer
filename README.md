English Note / Reviewer — Interactive Web Application & 125-Item Mock Exam

An interactive, offline-ready web reviewer and diagnostic mock examination built around the English Note / Reviewer reference guide. Designed with a clean Grey, Blue, and Green academic interface, smooth scroll-reveal animations, and responsive layouts for both mobile phones and laptops/desktops.

Key Features

1. Interactive Study Reviewer

Complete Verbatim Reference Content: Covers all five core modules directly from the reference notes without altering terms, mnemonics, or sample sentences:

Capitalization (Sentence beginnings, Titles before personal names, Geographical locations, Organizations, Companies, Brands, Languages & Nationalities, Holidays, Historical Eras, and the Pronoun "I").

Punctuation & Sentence Types (Declarative, Interrogative, Imperative, Exclamatory, Commas, FANBOYS, Oxford Series, Semicolons, Colons, and Apostrophes).

Parts of Speech (PAPANICVA mnemonic, 7 Noun classifications, 6 Pluralization rules, Regular vs. Irregular verbs, and Action, Linking, Helping, Transitive, & Intransitive verbs).

Sentence Structures & Clauses (Subject & Predicate, Compound Subject/Predicate, Sentence Fragments, and the 4 Sentence Structures: Simple, Compound, Complex, and Compound-Complex).

Subject-Verb Agreement (Basic Rule, "I" & "You" exemptions, Pronoun Reference Table, and Rules 1 to 12 including exceptions and vocabulary notes).

Topic Filtering & Instant Search: Filter by topic pills or search across rules, mnemonics, and examples in real time.

Section Mastery Tracking: Mark individual sections as mastered to track study completion.

2. Interactive 3D Flip Cards (54 Cards)

Smooth 3D card-flip animation (rotateY(180deg)) accessible via click, tap, or Spacebar / Enter.

Filter cards by grammar topic or focus exclusively on cards marked Needs Practice.

Deck shuffling and persistent Mastered vs. Needs Practice status indicators.

3. Comprehensive 125-Item Multi-Format Mock Exam

Paginated across 9 pages (15 items per page) with an interactive Question Map for instant navigation and automatic offline answer saving:

Part I: Multiple Choice (Items 1–40) — 40 four-option items testing grammar mechanics, sentence structures, and SVA rules.

Part II: True or False (Items 41–60) — 20 verification items testing rules, exceptions, mnemonics, and sample sentences.

Part III: Term & Rule Identification (Items 61–85) — 25 active-recall text-input items identifying grammatical terms, sentence types, acronyms, and SVA rules.

Part IV: Fill in the Blank (Items 86–110) — 25 items testing proper capitalization, punctuation marks, contractions, plural forms, irregular verbs, and verb agreement.

Part V: Drag & Drop Matching Boards (Items 111–125) — 3 interactive matching boards supporting both desktop drag-and-drop and mobile tap-to-select / tap-to-place.

4. Performance Analytics & Study Enhancement Feedback

Overall Score & Grade Tier: Calculates exact score out of 125 and percentage accuracy.

Accuracy Breakdown: Visual progress bars segmented by Grammar Topic and Exam Question Format.

Targeted Study Recommendations: Automatically flags topics scoring below 80% and provides specific enhancement guidance with one-click navigation back to the corresponding reviewer notes.

Complete 125-Item Answer Key: Displays user responses, correct answers, and rule explanations with a toggle to filter Missed Items Only.

5. Offline-First Device Persistence

Uses browser localStorage (english_reviewer_blue_green_v2) to automatically save mastered sections, flashcard progress, current exam page, in-progress exam answers, and completed exam history—working seamlessly with or without an internet connection.

Project Structure

.
├── index.html      # Complete single-file application (HTML, CSS variables/animations, dataset, and JS engine)
└── README.md       # Project documentation and usage guide


How to Run

Direct Browser Launch (No Build Tools Required):

Double-click index.html or open it in any modern browser (Chrome, Edge, Safari, Firefox, or mobile browsers).

Offline Usage:

Once opened, the page requires zero external CDNs, fonts, or APIs. All progress persists automatically on your device until you click Reset Progress.


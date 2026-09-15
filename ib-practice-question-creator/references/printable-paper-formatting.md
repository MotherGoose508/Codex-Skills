# Printable Paper Formatting

Read this reference only when creating or reformatting a unit test, mock paper, worksheet, response booklet, or printable PDF.

## Format Intent

Create a restrained, professional assessment that feels familiar to an IB learner without impersonating an official IB publication. Use official or teacher-provided papers only to understand general conventions such as hierarchy, spacing, answer areas, mark placement, and instruction patterns.

Never reproduce or closely imitate protected identifiers or page furniture. Omit:

- the IB name or logo as branding;
- IB copyright notices or licensing text;
- session numbers, document codes, zone labels, and barcodes;
- official-paper claims or wording that suggests endorsement;
- copied questions, diagrams, or distinctive layouts from an authentic paper.

Place a quiet disclosure on the cover or footer: **Original practice assessment - not an official IB examination.** For marking guidance, use: **Original teacher marking guidance - not an official IB markscheme.**

## Choose the Response Format

- **In-paper response booklet:** Default for Physics, Mathematics, Design Technology, language short-response work, and mixed structured questions. Put a ruled or dotted answer area immediately after each part.
- **Question-only booklet:** Default for extended essays and sustained literary or historical responses unless the user asks for writing space. State what separate answer paper is expected.
- **Interactive practice:** Stay in chat; do not create a paper artifact unless requested.

Response space must reflect the task rather than the mark count mechanically. Allow enough room for diagrams, algebra, or explanation; do not leave half-empty pages merely to look formal.

## Page System

Unless a supplied school template controls the design, use:

- A4 portrait pages;
- black and grayscale only;
- Arial, Helvetica, or a metrically similar sans-serif typeface;
- 10-11 pt question text with approximately 1.25-1.35 line spacing;
- margins of about 18-22 mm, leaving a stable header and footer zone;
- centered page numbers on internal pages and a short subject/paper label at top right;
- thin rules and borders; no decorative color blocks, gradients, or marketing-style cover design.

A cover page should make these items immediately scannable:

1. subject and level;
2. assessment title and syllabus scope;
3. duration;
4. candidate name or session field when appropriate;
5. permitted resources and required materials;
6. answer instructions;
7. total marks.

Use plain examination language such as:

- **Instructions to candidates**
- **Answer all questions.**
- **Write your answers within the answer boxes provided.**
- **Show all working and include units with numerical answers.**
- **A calculator is required for this paper.**
- **A clean copy of the current [subject] data booklet is permitted.**
- **The maximum mark for this paper is [N marks].**
- **Do not open this examination paper until instructed to do so.**
- **This question continues on the following page.**
- **End of paper.**

Adapt these statements to verified course rules. Do not claim that a resource is required, prohibited, or permitted without checking the applicable assessment basis.

## Question Pages

- Put the main question number at the left margin and align its stem in a consistent text column.
- Indent subparts consistently: `(a)`, `(b)`, then `(i)`, `(ii)` when needed.
- Place each mark allocation at the far right in square brackets, for example `[2]`.
- Keep a part prompt with its mark allocation and the beginning of its answer area.
- Use a thin rectangular answer box with evenly spaced dotted writing guides for in-paper responses.
- Keep equations, units, subscripts, superscripts, and scientific notation typographically clear. Confirm every mathematical symbol is embedded and renders correctly.
- Label generated diagrams clearly and add **diagram not to scale** when scale could mislead.
- Use **(Question N continued)** when a question crosses a page, and make the continuation unmistakable.
- Do not print syllabus codes beside every question unless the user asks for a teacher-facing coverage map; they make a student paper feel like a worksheet rather than an examination.

## Separate Marking Guidance

Answer withholding still applies. Create or deliver a mark scheme only when the user explicitly requests it, the established task already includes it, or the user is clearly authoring teacher materials.

Keep student and teacher material in separate files. A compact mark-scheme table may use:

| Part | Answer and marking guidance | Mark |
|---|---|---:|

For each part:

- show the independently checked answer;
- separate method, reasoning, accuracy, and communication points when relevant;
- accept equivalent reasoning and sensible intermediate rounding;
- avoid invented official mark-scheme abbreviations or examiner codes;
- include a topic/mark coverage map only when it helps the teacher verify the requested weighting.

Do not include grade boundaries unless the user supplies them or they are verified for the exact assessment context.

## PDF Production and QA

Use the PDF skill for the artifact workflow. Prefer direct PDF generation when precise exam layout and answer boxes matter. Keep the editable source or builder as an intermediate unless the user requests it.

Before delivery:

1. Independently solve every numerical question and verify the mark total and topic weighting.
2. Extract text from the produced PDF and confirm all questions, marks, and required labels are present.
3. Render every page to PNG with Poppler and inspect each page at full size.
4. Fix clipping, overflow, orphaned marks, weak page breaks, inconsistent answer areas, missing glyphs, and header/footer collisions.
5. Rerender after every layout-sensitive fix.
6. Deliver only the requested student and teacher artifacts, not QA images or build files.

The final response should call the result **IB-style practice**, **IB-inspired formatting**, or an **original practice assessment**. Never call it an authentic, official, or past IB paper.

# Bachelors' and Masters' Degree Theses: Guidelines

### Using this repository

Create your own copy of this repository through "Use this template".

**Read this document in its entirety and ensure you understand it**.

Then, read it again, and begin the challenging but beautiful and enriching journey called "thesis".

## Theses/Dissertations 101

### Planning a thesis

Plan your thesis (possibly, talking with *potential supervisors*):

1. Determine the **type** of thesis (i.e. the kind of work you'd like to carry out)
    1. **project** (tesi di progetto)
    2. **research** (tesi di ricerca)
    3. **report** (tesi compilativa) -- i.e., no project, no research, but a mere reportage/elaboration of existing material
2. Determine your **subject**:
    1. **project idea** (for project-oriented theses)
    2. **scientific/research question** (for research-oriented theses)
    3. **subject** (for report-oriented theses)
3. Try to devise a **plan**, e.g.,
    * in terms of **mandatory goals** and **optional goals**
4. Devise a tentive **title** summarizing the whole content and pinpointing the direction of the thesis

### Executing thesis work

The suggestion is to carry out an iterative, incremental, agile approach.
In each cycle (approx. 1 or 2 weeks):

1. Work on your project/research (an increment)
2. Report your increment and discuss it / next steps with your supervisor -- then back to (1)
    - See next section

Suggestion: keep the **raw material** about your work under **version control** in a repository (e.g., on GitHub)

- Use *distinct repositories* (or orphan branches, if you know what you're doing)
    1. notes (e.g., on background, on literature reviews)
    2. experimental activities (e.g., to learn a new framework or library)
    3. the main development project or the research project artifacts
    4. the thesis document (ideally, in LaTeX)
- You may also consider to use an app to keep track of tasks and progress (e.g., Trello)
- **Share those with your supervisor**. When reporting progress to your supervisor, provide a link to a proper page/artifact describing the increment.

#### Delivering your thesis work

Delivery of your work depends on the agreement you have with your supervisor.
Some want to read chapters one by one as soon as they're ready,
others prefer to correct the work when it is ready.

Some supervisors contributed to the document and provide the strategy they use here:

| Surname | Name | Strategy |
| --- | --- | --- |
| Francia | Matteo | Deliver each chapter separately, one chapter at a time. Each chapter can be delivered only *once* |
| Pianini | Danilo | Deliver the index of contexts, namely, have all chapters and sections defined. Iterate over the structure as needed. Once the whole document is ready, send it. The whole work can be delivered only *once* |

In any case,
the supervisor is not there to verify the status of your work,
so, typically, work is sent to the supervisor when its contents are considered **finalized**.
Moreover,
the supervisor is not as spell checker:
thoroughly check your document **before** sending it to the supervisor.
If you are writing in English, a tool that we recommend is [Grammarly](README.md).
Once you consider your thesis finished, a good approach (assuming there is enough time)
is leaving the document alone for 2-3 days, then reading it from the beginning:
a fresh look may provide better insights.

### On writing a thesis

Typical steps

1. Before writing the thesis document, you need your thesis **content**: it means, you need to have a rather stable software for a software project thesis, experimental/scientific results for a scientific thesis, a conceptual framework for a etc.

**Once you have enough material** to actually start writing your thesis

1. Define the **high-level structure** (i.e., the Sections) of the thesis
2. You may **optionally start writing the background content**, as it may serve to make it explicit and fully understand it in order to develop the contribution
3. **Complete the main content** (contribution, experiments)
    * If technical developments and experiments are needed, wait to have them done: this part of the thesis is a documentation of what you have achieved (i.e., the final system, the experimental results etc.).
4. **Write Title, Introduction, Conclusion, and Abstract**

Once you have written significant increments of your dissertation, consider **asking feedback to your supervisor**.
Send your supervisor a PDF (possibly, a diff wrt the previous PDF you shared -- e.g., using tools like [Draftable](https://draftable.com/)).

#### Typical structure for theses

##### Project-oriented theses

A good structure is as per the *project exam report* of the OOP course at UNIBO Cesena Campus: [https://github.com/APICe-at-DISI/OOP-report-template](https://github.com/APICe-at-DISI/OOP-report-template)

1. Introduction
2. Background
    1. Here you may want to provide some background on tools / processes you considered or adopted
3. Analysis
    1. High-level goals
    1. Constraints
    1. Functional and non-functional requirements
    1. Requirements analysis
    1. Problem analysis
    1. Domain model
4. Design
    1. Architecture
    1. Detailed design
5. Implementation
    1. Implementation highlights
6. Evaluation
    1. Testing
    1. Experimental evaluation / demos -- the idea here is to provide *evidence*, possibly using quantitative *metrics* (but, sometimes, even *qualitative metrics* could be ok)
7. Conclusion and Future Work
8. Bibliography/references

Important: in your dissertation, you should also provide a link to the main project's **artifacts** (ideally from a permanent repository like **Zenodo** which well integrates with **GitHub**).

##### Research-oriented theses

Various structures could work. For instance:

1. Introduction
2. Methods and Materials
3. Results
4. Discussion
5. Conclusion and Future Work
6. Bibliography/references

Or also:

1. Introduction
2. Motivation, Background, and Related Work
3. Contribution
4. Evaluation
5. Conclusion and Future Work
6. Bibliography/references

Note: you may also detail the section titles to match the actual content, e.g.,

1. Introduction
2. Background and Motivation: CAS Programming
4. ScaFi: a DSL for CAS Programming
5. Case study: Programming Swarms
6. Related Work on CAS Engineering
7. Conclusion and Future Work
8. Bibliography/references

Notice that sometimes, section "Related Work" might also fit at the end of your manuscript.

#### Writing: specific chapters

- **Abstract**
    - Very brief (e.g. 250-300 words)
    - Abstract should briefly point out: Context, Problem/Objectives, Methods/Contribution, Results, Conclusions 
- **Introduction**
    - Introduction should set: Context, Scope, Significance (Motivation), Goals/High-level Questions, Methodology (briefly), Organisation of the paper (chapters and what they include)
- **Conclusion**
    - Conclusion chapter should point out: (1) Briefly recall problem, starting point and methods adopted, (2) Briefly report Findings, (3) Briefly discuss benefits/limitations, (4) Discuss Future Work

#### Writing: style and elements

1. Contents
    - A thesis is not a textbook: write **solely** contents concerning the activities.
        - For instance: if the thesis concerns BI/OLAP and the implementation is ROLAP-based, it is fine to mention MOLAP and HOLAP for a quick comparison, but only ROLAP should be discussed in-depth.
    - It is worthless and ethically questionable copying and pasting text from books.
    - **Do NOT** use text generated by bots, large language models, and similar tools. Theses are meant to provide evidence that the student can produce a scientific contribution, the capability organize contents in written and oral form is relevant and part of the evaluation.
    - Avoid long code snippets
1. Language
    - Avoid whenever possible subjective, superficial, and informal comments that are not supported by a citation to a paper or very clear evidence. Example adjectives that should be avoided without citation or evidence: trivial, simple, easy, hard, very, too much, little, short, long, impossible, optimal.
    - Be concise!
        - *bad*: the idea of trajectory lies into the ability to capture subsequent moves of an object
        - *good*: a *trajectory* can be formally defined as "quoted text" [citation to a paper]
        - Do not abuse **boldface** and *italic*
        - Use `monospace` for code
1. Words in other languages
    - If there is a need for words in languages other than the one in the document
    (e.g., Italian words in an English-written thesis, or English words in an Italian-written thesis),
    prefer wordings that maximize the usage of the document language.
    For instance, if the thesis is written in Italian,
    "Mining di traiettorie" is preferable to "Trajectory mining"
1. Citations
    - Follow [this guide](https://danysk.github.io/post/2020-05-08-bibliography/)
    - TL; DR: 
        1. use BibTeX
        2. do not trust the BibTex entries you find online, check them
        3. decent BibTex entries for computer science can be found on [DBLP](https://dblp.uni-trier.de/)
        4. you may consider using [doi2bib](https://www.doi2bib.org/) to generate BibTex entries from DOIs
    - **Don't copy** long texts, summarize them
    - If something is quoted verbatim, make it explicit by using quotes:
        - Example: "Aggiungere inglesismi random non improva le vostre skills" [1](http://www.lercio.it/ricerca-aggiungere-inglesismi-random-non-improva-le-vostre-skills/)
1. Figures:
    - Figures taken from another source (or is a derived work of another source)
    the source must be cited
    - Prefer *vectorial* images (SVG, PDF, EPS...) over *raster* (PNG, JPEG, Bitmaps)
        - Note: including a raster image into a vectorial format supporting embedding is *useless*
1. Punctuation, lists, coherence
    - Titles should not have full stops
    - Watch your accents: don't write apostrophes in place of accents: `E'` is not the same of `È`.
    On Linux, with a layout supporting `è` (e.g., Italian) use <kbd>CAPS LOCK</kbd>+<kbd>è</kbd>.
    On Windows, use <kbd>alt</kbd> followed by <kbd>0200</kbd> 
    - In LaTeX, quotes are done by opening with double backticks and closing with double single quotes \`\`like this''.
    Do not use double quotes ("like this").
    Backticks are made on Linux with <kbd>alt gr</kbd>+<kbd>'</kbd> with the Italian keyboard layout;
    on Windows, <kbd>alt</kbd> followed by <kbd>96</kbd>
    - Bullet points end in `;` or `.`, depending on whether they are part of the same sentence or not.
    The initial letter in a bullet point must be capitalized if the previous bullet point terminates with `.`.
1. [Reference guide for Computer Science and Engineering at UniBo](https://corsi.unibo.it/magistrale/IngegneriaScienzeInformatiche/volume-pdf-e-deposito-online-dellelaborato)

#### Writing: DOs and DONTs

- **DON'T reuse material without citing the source**
- **DON'T write personal stuff** in your dissertation (even in the Conclusion)
    - Your thesis is a *technical document*
    - No reader would care about whether e.g. you got limited results because you had little time to work on your project, or because of your limited background on something.
- **DON'T write using informal language**
    - E.g., avoid contractions like `don't`, `We're`, ...

- **DO check** whether you have the rights to reuse material from some source/author
- **DO consider consulting a writing style guide**

#### FAQs and practical aspects:

- *Q: When to start writing?*
    - As soon as you have stable results to report. 
    - You may start early writing the background.
    - Wait for results to be stable to write the bulk of your thesis (as the actual implementation is usually the most costly and time-consuming part of the job).
    - Write introduction/abstract/conclusion at last.
- *Q: What tool to actually write the thesis?* 
    - Use **LaTeX**
- *Q: How to check for typos and grammatical issues?*
    - NOTE: it is not a responsibility of the (co-)supervisor to find or fix these
    - Consider using tools like [LanguageTool](https://github.com/languagetool-org/languagetool) for spell and grammar checking 

## Using LaTeX to write theses

### How to use this template

- Clone or (better) fork this repository
- Open `thesis-main.tex` with a LaTeX editor (e.g., `Kyle`, `TeXMaker`, `TeX Studio`, or VS Code with the LaTeX extension)
- Compile `thesis-main.tex` with `bibtex` and `pdflatex` to produce the PDF of your thesis
- Start writing your thesis, and commit/push often

### Working with LaTeX

See these [video lectures by Ciatto](https://www.youtube.com/watch?v=ihxSUsJB_14).

- [Getting LaTeX](https://www.latex-project.org/get/)

## General information about Theses

#### What is a thesis and what to expect about it (see also [this](https://shorelight.com/student-stories/what-is-a-thesis/)]

- IN GENERAL: "A thesis identifies a question on a topic that relates to your degree program, which you then have to answer with a sensible argument, using credible research and findings."
- Kinds of thesis in Engineering Degrees
    - **Project thesis**: the thesis documents an engineering project
    - **Research thesis**: a coherent and cohesive narrative describing a body of scholarly activity that adds to knowledge
- WHAT IS A THESIS FOR YOU: A thesis is a good chance to exhibit your technical skills (competence in the matter of study) and soft skills (e.g., autonomy, proactiveness, creativity) on a problem that you like and want to address in a field/area you want to explore

#### Student responsibility vs. (co-)supervisor responsibilities

- The student is responsible for
    - the content of the thesis and its final quality 
    - ensuring bureaucratic stuff is carried out by the deadlines
- The (co-)supervisor is responsible for
    - providing *guidance* and *support*
- Note: your thesis is **yours**.
    - Your supervisor can help you with that, but he/she is not a proofreader. So, your thesis is not something that "has to be checked/corrected" by someone.
    - However, ask for advice, especially for the most important issues (e.g., goals, dissertation structure), early.

#### Relationship with (co-)supervisor

- How often should I contact my thesis (co-)supervisor, for what, and how?
    - As often as agreed with the (co-)supervisor.
        - A typical frequency is once every one or two weeks, or as often as there are significant increments.
    - You should contact your (co-)supervisor for "important" stuff and "strategic" decisions, rather than implementation details.
    - If you have minor questions and doubts, wait enough time to have a batch of these, and pose all the questions, numbered, in a single e-mail.
- What if I have a blocking situation that prevents progress?
    - If it is a technical issue, spend some time exploring for solutions. If you can't find a solution, contact your (co-)supervisor, with a detailed mail explaining the problem, your tentative solutions, etc.

## More references

See also the [PhD thesis template by Ciatto](https://github.com/pikalab-unibo/phd-thesis-template).

Infos on structuring PhD theses:

1. http://www0.cs.ucl.ac.uk/staff/c.clack/phd.html
2. http://people.kmi.open.ac.uk/stefan/thesis-writing.pdf
    1. Introduction 
    2. Motivation 
    3. RW 
    4. Experiments 
    5. Conclusions

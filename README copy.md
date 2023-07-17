# Bachelors' and Masters' Degree Theses: Guidelines

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

### Executing thesis work

The suggestion is to carry out an iterative, incremental, agile approach.
In each cycle (approx. 1 or 2 weeks):

1. Work on your project/research (an increment)
2. Report your increment and discuss it / next steps with your supervisor -- then back to (1)
    - See next section

Suggestion: keep the **raw material** about your work under **version control** in a repository (e.g., on GitHub)

- Use *distinct repositories*
    1. notes (e.g., on background, on literature reviews)
    2. experimental activities (e.g., to learn a new framework or library)
    3. the main development project or the research project artifacts
    4. the thesis document (ideally, in LaTeX)
- You may also consider to use an app to keep track of tasks and progress (e.g., Trello)
- **Share those with your supervisor**. When reporting progress to your supervisor, provide a link to a proper page/artifact describing the increment.

#### Delivering your thesis work

1. Consegna dei capitoli
    - Consegnare ogni capitolo una sola volta.
    - Non è compito del relatore verificare lo stato della scrittura, lo studente invia i contenuti quando sono pronti (i.e., quando, secondo lo studente, i contenuti sono **finalizzati**)
    - Prima della consegna
        - **Fare un controllo della grammatica** ed eventuali errori di battitura (per tesi in inglese Grammarly è di grande aiuto)
        - Mettere il capitolo "nel cassetto" 2-3 giorni e rileggerlo

### On writing a thesis

Typical steps

1. Before writing the thesis document, you need your thesis **content**: it means, you need to have a rather stable software for a software project thesis, experimental/scientific results for a scientific thesis, a conceptual framework for a etc.

**Once you have enough material** to actually start writing your thesis

1. Define the **high-level structure** (i.e., the Sections) of the thesis
2. You may **optionally start writing the background content**, as it may serve to make it explicit and fully understand it in order to develop the contribution
3. **Complete the main content** (contribution, experiments)
    * If technical developments and experiments are needed, wait to have them done: this part of the thesis is a documentation of what you have achieved (i.e., the final system, the experimental results etc.).
4. **Write Title, Introduction, Conclusion, and Abstract**

Once you have written significant increments of your dissertation, consider **asking feedback to your supervisor**. Send your supervisor a PDF (possibly, a diff wrt the previous PDF you shared -- e.g., using tools like [Draftable](https://draftable.com/)).

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

1. Contenuti
    - La tesi non è un libro didattico: scrivere **solo** i contenuti funzionali all'attività di tesi.
        - Esempio: se la tesi si colloca in ambito BI/OLAP e l'implementazione si basa su ROLAP, va bene citare anche MOLAP e HOLAP, ma è bene approfondire solo ROLAP. E' inutile e sbagliato copia-incollare capitoli di libri di testo come "Data Warehouse. Teoria e pratica della progettazione"
    - **Non** copiare testo generato da bot/LLM/etc. La tesi dimostra la capacità dello studente di produrre un contributo scientifico. Essere in grado di organizzare e articolare i contenuti in modalità orale e scritta è importante e parte della valutazione
    - **Non** copia-incollare codice nella tesi
1. Linguaggio
    - Evitare sempre commenti non oggettivi/superficiali/informali (o sono supportati da citazioni o non si mettono). Ad esempio: banale, semplice, facile, difficile, molto, troppo, poco, impossibile
    - Concisione: Non scrivere frasi più lunghe di *due* righe
        - Esempio No: L'idea di traiettoria si delinea nell'abilità di catturare gli spostamenti di un oggetto
        - Esempio Sì: La definizione di traiettoria è: "testo quotato" [citazione]
    - **Evitare** l'abuso di **grassetto** e *corsivo*
1. Inglesismi
    - Se le tesi è in italiano è bene scrivere in italiano e limitare l'uso dell'inglese il più possibile (e.g., "Trajectory Mining" -> "Mining di traiettorie")
        - Ovviamente non tutto può essere tradotto in italiano (e.g., clustering, mining, deploy, etc.)
    - Usare un termine inglese se questo si ripete ma spiegalo una sola volta.
    - Un acronimo in inglese rimane in inglese: GPS (Global Positioning System) e non si usa il plurale
    - La prima volta in assoluto che il termine compare scrivilo in corsivo. Esempio "I *layer* (livelli) di un GIS (*Geographic Information System*)"
1. Struttura
    - Convenzione nomi
        - Titolo: 
            - Prima lettera maiuscola in tutti i nomi, pronomi, aggettivi, verbi, avverbi
            - Tutto maiuscolo acronimi
            - In minuscolo articoli e congiunzioni 
        - Sezioni: tutto minuscolo eccetto la prima lettera e acronimi (e.g., "Questa è una sessione OLAP")
    - Abstract (sommario): singolo paragrafo tra 150 e 250 parole
    - Usare il package `cleveref` e `\Cref{}` (e non `\ref{}`) di Latex per fare riferimento a label di capitoli/sezioni/sottosezioni/immagini
    - Quando si descrive un argomento è bene averlo già introdotto. Se non indispensabili, evitare le *forword reference* (riferimento a capitoli/sezioni/sottosezioni che appaiono dopo essere referenziati)
    - Non creare sezioni con singola sottosezione
    - Non creare (sotto)sezioni lunghe meno di una pagina
    - Evitare di disperdere le informazioni: definizione, dettagli e implicazioni stanno nello stesso paragrafo
    - Esiste differenza tra `.` e `. a capo`: `. a capo` si usa per cambiare discorso
1. Citazioni e copia/incolla
    - Non citare Wikipedia (su https://scholar.google.it/ esiste un oceano di letteratura scientifica a [revisione paritaria](https://it.wikipedia.org/wiki/Revisione_paritaria)
        - Se necessario, sfruttare Wikipedia per trovare le citazioni a paper/libri
    - **Non copiare** testi lunghi, è meglio riassumerli ed elaborarli
    - **Non copiare** traduzioni lunghe, è meglio riassumerle ed elaborarle
    - Esplicitare la parte di testo copiata inserendola tra virgolette e aggiungi la citazione finale
        - Esempio: "Aggiungere inglesismi random non improva le vostre skills" [[Questa è una cit]](http://www.lercio.it/ricerca-aggiungere-inglesismi-random-non-improva-le-vostre-skills/)
    - La citazione precede il `.`: Testo citato [citazione]. (e non: Testo citato. [citazione])
1. Figure:
    - Se una figura è copiata/rielaborata indicare la sorgente con apposita citazione
    - Utilizzare figure in formato vettoriale (e.g., .pdf, .svg) e non raster (e.g., .png, .jpg)
    - In caso di screenshot, attenzione alle dimensioni (in MB) della figura
1. Punteggiatura, elenchi (e coerenza)
    - No punti nei titoli
    - Non `E'` ma `È` (È = Alt + 0200)  
    - In Latex, le virgolette si fanno \`\`così'' (\` = Alt + 96) e non "così"
    - Elenchi puntati iniziano con Maiuscola, finiscono con `;` o con `.` (l'importante è usare la stessa convenzione). Di solito si usa `;` per terminare frasi di senso non compiuto, e `.` per terminare frasi di senso compiuto
    - No `...`, sì "etc." 
1. Link di riferimento per elaborato tesi https://corsi.unibo.it/magistrale/IngegneriaScienzeInformatiche/volume-pdf-e-deposito-online-dellelaborato

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
- Open `thesis.tex` with a LaTeX editor (e.g., `Kyle` or `TeXMaker`)
- Compile `thesis.tex` with `bibtex` and `pdflatex` to produce the PDF of your thesis
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

See also the [thesis template by Ciatto](https://github.com/gciatto/phd-thesis).

Infos on structuring phd theses:

1. http://www0.cs.ucl.ac.uk/staff/c.clack/phd.html
2. http://people.kmi.open.ac.uk/stefan/thesis-writing.pdf
    - 1) Introduction 2) Motivation 3) RW 4) Experiments 5) Conclusions

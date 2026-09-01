Here is a more reusable version that keeps the **tutorial content high-level** and leaves the coding agent room to design the lesson.

# Prompt Template: Interactive HTML Tutorial

## Role

Act as an expert **educator, instructional designer, and front-end developer**.

Create a polished, interactive HTML tutorial on the following subject:

**Topic:** [Debugging & Testing Python in Jupyter Notebook]

The tutorial should be designed for learners who are relatively new to Python and should progress from foundational concepts to more advanced practical techniques.

---

# Learning Scope

Cover the key concepts learners need to understand the topic, including areas such as:
[
* feature 1 
* feature 2
]
Organize the material in a logical learning sequence from **basic to advanced**.

Do not overload each section. Focus on the most important concepts, examples, and practical insights for beginners.

---

# Visual Design

Use a **blueprint-themed sheet-set interface**.

The visual style should include:

* Dark navy blueprint-style background
* Subtle grid pattern
* IBM Plex fonts
* Amber, cyan, and coral accents
* Strong contrast
* Large, readable typography
* Clearly differentiated code, explanation, output, and activity areas

The overall experience should resemble a collection of technical or engineering blueprint sheets.

---

# Tutorial Structure

Organize the tutorial into expandable sections called **Sheets**.

Number them clearly:

**SHEET 01**
**SHEET 02**
**SHEET 03**
...

Each sheet should focus on one major concept.

A typical learning sequence should follow:

**Concept → Example → Interaction → Feedback → Explanation → Takeaway**

Keep explanations concise and visual whenever possible.

Avoid long walls of text.

---

# Interactive Features

The tutorial must behave like an **interactive learning application**, not a static webpage.

Include features such as:

* Expandable and collapsible sheet accordions
* When a section is **collapsed**, show: `▶ Show explanation`
* When a section is **expanded**, show: `▼ Hide explanation`
* Click-to-reveal code output
* Interactive quizzes or knowledge checks
* Flip-card recall questions at the end

Whenever practical, ask learners to **predict what will happen before revealing the result**.

---

# Python Examples

Use realistic, beginner-friendly Python examples.

Examples should:

* Look like code learners might actually write
* Use meaningful variable names
* Demonstrate debugging reasoning rather than merely showing solutions
* Be especially relevant to introductory Python programming, and business/data analytics contexts where appropriate

For significant code examples, provide an interaction such as:

**Run Code**

**Reveal Output**

**Show Error**

**Show Fix**

or

**Next Step**

Do not display all outputs automatically.

---

Use beginner-friendly language first, followed by proper Python terminology.

---

# Visual Teaching Components

Use visual elements to make abstract ideas easier to understand.

Examples may include:

* Process flows
* Error anatomy diagrams
* Before/after comparisons
* Execution timelines
* Variable-state panels
* Jupyter cell-order diagrams
* Debugging decision flows
* Code-to-output relationships

Visuals should support understanding rather than serve as decoration.

---

# Callout System

Use visually distinct teaching callouts such as:

**DEBUGGING TIP**

**COMMON MISTAKE**

**WHY THIS HAPPENS**

**TRY IT**

**WATCH OUT**

**KEY TAKEAWAY**

Keep callouts short and useful.

---

# Recall and Knowledge Check

End the tutorial with an interactive review section.

Use **flip cards, mini quizzes, or recall questions** covering the most important concepts introduced throughout the tutorial.

The review should test conceptual understanding rather than simple memorization.

---

# Accessibility and Usability

Ensure:

* Large, readable fonts
* Strong text/background contrast
* Clearly identifiable buttons
* Visible hover and keyboard focus states
* Responsive layout
* Code blocks that do not break the page layout
* Desktop and tablet usability
* Reasonable mobile usability
* Clear indication of whether a sheet is expanded or collapsed

Do not rely on ambiguous interactions such as clicking an entire panel without a visible indication that it is interactive.

---

# Technical Requirements

Deliver a **single self-contained HTML file**.

Requirements:

* HTML, CSS, and JavaScript in one file
* Inline CSS
* Inline JavaScript
* No framework
* No build process
* No server dependency
* No external JavaScript libraries
* Google Fonts may be used
* IBM Plex fonts are preferred
* The file should work when opened directly in a modern browser
* Code should be organized and commented for maintainability

---

# Design Principle

The tutorial should prioritize:

**Learn → Predict → Try → Observe → Debug → Understand → Recall**

The learner should actively interact with the material instead of simply reading it.

---

# Deliverable

Create one polished, functional HTML file for the tutorial:


The final result should feel like a small interactive educational application rather than a static article.

This version should also be easier to reuse: you can replace only the **Topic** and **Learning Scope** sections while keeping the rest of the instructional and interface requirements unchanged.

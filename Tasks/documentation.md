# POML

POML is a very recent release, but most people can relate to the problems it solves. **POML (Prompt Orchestration Markup Language)** is a novel markup language designed to bring **structure**, **maintainability**, and **versatility** to advanced prompt engineering for Large Language Models (LLMs). It addresses common challenges in prompt development, such as lack of structure, complex data integration, format sensitivity, and inadequate tooling. POML provides a systematic way to **organize prompt components**, integrate diverse **data types** seamlessly, and manage **presentation variations**, empowering developers to create more sophisticated and reliable LLM applications.

---

### Features

- **Structured Prompting Markup**:  
  POML has an HTML-like syntax with components such as ``<role>``, ``<task>``, and ``<example>`` to encourage **modular design**, improving prompt **readability** and **reusability**.

- **Data Handling**:  
  Incorporates special data components (e.g., ``<document>``, ``<table>``, ``<img>``) that **embed or reference external data sources** like text files, spreadsheets, and images, with **customizable formatting options**.

- **Integrated Templating Engine**:  
  Includes a built-in templating engine with support for **variables** (``{{ }}``), **loops** (``for``), **conditionals** (``if``), and variable definitions (``<let>``) for dynamically generating **complex, data-driven prompts**.

---

### Example

``It is an example from the official POML documentation``

<!-- Used XML here for syntax highlighting as currently their is no specific support for POML syntax -->
```XML
<poml>
  <role>You are a patient teacher explaining concepts to a 10-year-old.</role>
  <task>Explain the concept of photosynthesis using the provided image as a reference.</task>

  <img src="photosynthesis_diagram.png" alt="Diagram of photosynthesis" />

  <output-format>
    Keep the explanation simple, engaging, and under 100 words.
    Start with "Hey there, future scientist!".
  </output-format>
</poml>
```


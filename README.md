# 📖 Professional English Custom Dictionary for Microsoft Word

A community-maintained `.dic` file that stops Microsoft Word from flagging legitimate professional vocabulary as spelling errors.

If you've ever had Word underline *operationalize*, *reskilling*, or *RAG-based* in red — this is for you.

---

## What's Inside

This dictionary covers four domains of modern professional English:

| Category | Examples |
|---|---|
| **Standard Business English** | `operationalize`, `rightsizing`, `workstream`, `swimlane`, `timebox` |
| **Executive / MBA Jargon** | `EBITDA`, `MECE`, `RACI`, `synergize`, `blitzscaling`, `blue-ocean` |
| **Startup / SaaS / AI** | `RAG`, `RLHF`, `fine-tuned`, `guardrails`, `churn`, `land-and-expand`, `microservices` |
| **HR / People Ops** | `allyship`, `neurodivergent`, `reskilling`, `offboarding`, `culture-add`, `EVP` |

600+ terms and growing.

---

## Installation

### Microsoft Word (Windows)

1. Download `AI_biz_dictionary.dic`
2. Open Word → **File** → **Options** → **Proofing** → **Custom Dictionaries**
3. Click **Add** and select the downloaded `.dic` file
4. Click **OK** to save

### Microsoft Word (Mac)

1. Download `AI_biz_dictionary.dic`
2. Open Word → **Word** menu → **Preferences** → **Spelling & Grammar**
3. Under *Custom Dictionary*, click the **Dictionaries...** button
4. Click **Add** and select the downloaded `.dic` file

### Other Applications

Most applications that support custom spell-check dictionaries accept plain `.dic` files (one word per line). Check your application's documentation for the correct import path.

---

## File Format

The `.dic` file is a plain text file with one term per line. No headers, no metadata — just words. You can open and edit it in any text editor.

```
operationalize
operationalized
operationalizing
reskilling
RAG-based
...
```

---

## Contributing

Contributions are welcome. If you use professional vocabulary that Word consistently flags and it isn't in the list yet, open a pull request or file an issue.

### How to contribute

1. Fork this repo
2. Add your terms to `AI_biz_dictionary.dic` — one term per line, alphabetically sorted within its category
3. Update the `CHANGELOG.md` with what you added and why
4. Open a pull request with a short description

### Guidelines

- **One term per line.** No punctuation, no definitions, no comments.
- **Include variants.** If you add `tokenize`, also add `tokenized`, `tokenizing`, `tokenization`.
- **Stick to legitimate professional vocabulary.** This is not a slang dictionary. Terms should appear in professional writing, job postings, industry publications, or recognized business frameworks.
- **Avoid trademarked proper nouns** unless they appear generically in professional writing (e.g., `Kubernetes`, `GitOps`).

---

## Roadmap

Planned additions:

- [ ] Legal / Contract vocabulary
- [ ] Finance & Accounting
- [ ] Renewable Energy / Clean Tech
- [ ] Cybersecurity / GRC (NIST, ISO, SOC 2)
- [ ] Healthcare & Life Sciences
- [ ] Supply Chain / Operations

Want to lead one of these? Open an issue and claim it.

---

## License

[MIT License](LICENSE) — free to use, modify, and redistribute.

---

## Acknowledgments

Built out of frustration with spell-checkers that have not caught up to how professionals actually write. If this saves you thirty seconds of right-clicking "Add to Dictionary" per document, it was worth making.

Contributions, suggestions, and domain expansions are welcome from anyone who writes for a living.

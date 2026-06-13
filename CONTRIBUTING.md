# Contributing

Thanks for contributing! 🎉 Please follow these conventions.

## Scope

Papers, code, and resources on **one-step (or directly-relevant few-step) generation** — both native and distillation methods. No pure multi-step work or dead links.

## Labels

- 🟢 **Native** — trainable from scratch, no frozen teacher.
- 🔵 **Distillation** — compresses a pretrained multi-step teacher.
- 🟡 **Hybrid** — supports both.

*Rule of thumb: needs a teacher → 🔵, trains on data alone → 🟢.*

## Entry Format

```markdown
- **Paper Title (Abbrev)** [Venue Year] 🟢/🔵/🟡
  *Author1, Author2, et al.*
  [[Paper](link)] [[Code](link)]
  One short sentence on what makes it distinctive.
```

Each line ends with two trailing spaces. Omit links that don't exist.

## Categories

Classify by **primary mathematical principle**, oldest → newest within each:
Consistency Models · Flow Straightening · Distribution Divergence Minimization · Adversarial Training · Shortcut / Direct Mapping · Applications · Unified Frameworks & Theory.

Also add a matching row to the **Full Paper List** table (newest-first).

## Submit

Fork → add entry in the right category + Full Paper List row → verify links, label, and format → open a PR titled `Add [Paper Title] (Venue Year)`.

## License

Contributions are licensed under the [MIT License](https://opensource.org/licenses/MIT).

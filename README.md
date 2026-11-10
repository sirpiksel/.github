<div align="center">

# `piksel_`s Account-Wide Repository Configuration

This repository contains the defaults to my GitHub projects.

</div>

These defaults serve developers and seek to constrain agents to worthwhile contributions. Its templates and policies set clear expectations for both, keeping agent-assisted contributions reviewable, attributable, and accountable while still welcoming responsible use.

Issue/PR templates and policy documents placed here are automatically available to every project, without per-repository setup.

## Roadmap

The repository is still being populated. The markdown files listed below will be added when the corresponding need arises:

- **Contribution** – For now, the audience is limited to known collaborators, who receive the same instructions through other channels. Since there are no external contributors who would benefit, the same guidance can be provided through private documentation, making public versions of the following files redundant:
  - `PULL_REQUEST_TEMPLATE.md`
  - `CONTRIBUTING.md`

- **Security** – Security policies are kept private for internal or privately‑hosted projects to reduce attack surface on tailored authenticated channels; when a repository becomes public, a comprehensive `SECURITY.md` will be added with reporting instructions, response expectations, responsible‑disclosure guidance, and compliance references.

## Issue Templates

The [`.github/ISSUE_TEMPLATE/`](.github/ISSUE_TEMPLATE/) directory provides the default issue templates that GitHub offers in repositories without their own. Each template pre-fills the issue title, applies the labels listed below, and asks for the information needed to act on it.

| Template                | Use for                                                             | Labels                              |
| ----------------------- | ------------------------------------------------------------------- | ----------------------------------- |
| 🐛 **Bug Report**       | Reproducible bugs, errors, and unexpected behaviour                 | `i: bug`, `i: needs triage`         |
| 💡 **Feature Request**  | New features, enhancements, or changes to defaults and workflows    | `i: enhancement`, `i: needs triage` |
| 🤗 **Support Question** | Questions about configuration, adoption, or how the defaults behave | `i: question`, `i: needs triage`    |

If your issue falls outside these categories, open a free-form issue. If you are unsure which template to choose, pick the closest match; issues can be relabelled or redirected during triage. See [`SUPPORT.md`](SUPPORT.md) for more guidance.

## Licensing

The `LICENSING` directory contains a variety of licences that may be used for any of my projects.

- EUPL-1.2 \
  A European copyleft licence that requires derivatives to be distributed under a compatible open licence and provides EU‑oriented, multilingual legal wording.
- BSD-3-Clause \
  Permissive licence permitting commercial use and re-licensing while requiring retention of copyright/disclaimer notices and forbidding use of the author’s name for endorsement.
- 0BSD \
  public‑domain‑equivalent permissive licence that imposes virtually no conditions, allowing anyone to use, modify, and re-licence the code without attribution.
- CC-BY-SA-4.0 \
  A permissive‑sharing copyright licence targeted at creative works that lets others copy, adapt, and use its works (including commercially) provided they give attribution and release any derivatives under the same licence.

The [choosealicense.com Appendix](https://choosealicense.com/appendix/) served as an orientation for picking these Licences and the above descriptions. **This is not legal advice.**

## Impact

- **Speed:** I can spend less time on boilerplate setup and more time delivering features.
- **Consistency:** All projects share the same reusable workflows, templates, and policies, reducing friction in collaboration and review.
- **Control:** Security, conduct, and support standards are defined once and available to every project by default.

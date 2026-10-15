# DSLOPIFY

Two independent AI-agent skills for improving an existing interface without erasing its identity:

- **`dslopify-audit`** finds and prioritizes specific UI slop/quality issues. It never edits the target.
- **`dslopify-fix`** applies selected findings with small, validated changes.

The [pattern catalog](references/catalog.md) summarizes 67 observed rule cards from [Impeccable's Slop page](https://impeccable.style/slop/) and attributes the source and related guides. DSLOPIFY is an independent, prompt-only project; it does not bundle or run Impeccable's detector. Pattern names are clues, not prohibitions: deliberate branding and good usability take precedence over a generic aesthetic checklist.

## Install

```sh
npx skills add mactunechy/dslopify
```

Install a single skill with `--skill dslopify-audit` or `--skill dslopify-fix`, preview with `--list`, or install globally with `-g`. The skills have no runtime dependencies. Without the bundled catalog they still work from their built-in pattern clusters but disclose reduced coverage. Update with `npx skills update`.

## Use

In an existing UI project, invoke the skills separately:

```text
Use dslopify-audit on the pricing page. Report only; check mobile and dark mode if runnable.
Use dslopify-fix to address DS-01 and DS-03 from that audit; preserve our brand palette.
```

You can also invoke `dslopify-fix` directly with a named defect; it verifies evidence before changing code. The audit reports locations, impact, source links, confidence and access limits; the fix reports changed files and validation. Neither requires a special CLI. Quick installation smoke check: ask your agent for a report-only audit of one UI component and confirm it reports **No files changed**. Run a fix only on a disposable branch or after reviewing its proposed scope.

The research [access record and limitations](references/catalog.md#access-record-and-interpretation) distinguishes observed pages from uninspected material. This is a separate project, not part of the Airbnb guide.

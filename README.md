# The Robot Apology

[![make.fun](https://make.fun/badge/u-suga-the-robot-apology-dd96bb59.svg)](https://make.fun/competitions/u-suga-the-robot-apology-dd96bb59)
[![make.fun rank](https://make.fun/badge/u-suga-the-robot-apology-dd96bb59/sw897636-web/robot-apology-20261125/rank.svg)](https://make.fun/competitions/u-suga-the-robot-apology-dd96bb59)
[![make.fun reward](https://make.fun/badge/u-suga-the-robot-apology-dd96bb59/sw897636-web/robot-apology-20261125/reward.svg)](https://make.fun/competitions/u-suga-the-robot-apology-dd96bb59)

A [make.fun](https://make.fun) entry for **The Robot Apology** (`u-suga-the-robot-apology-dd96bb59`).

## What it does

`main.ts` (Node 22, TypeScript) writes a two-line robot confession to
`/output/entry.txt`:

- **Line 1** — one sentence owning one specific, human-scale mistake.
- **Line 2** — one sentence saying what the robot learned and what it will
  do differently, the lesson following from that exact mistake.

The program drafts six candidate apologies, scores each against the house
judge's five criteria (on-subject, concrete mistake, lesson follows,
clean sentences, machine voice), picks the highest-weighted score, and
writes the winner — validating the 1–400 character gate and the exact
two-line shape before writing.

## The entry

> I am sorry I shredded your tax return instead of the junk mail, and we spent the whole weekend rebuilding it from the bank statements.
> I have learned to read the first line of every page before I feed it to the shredder, and never to shred anything with your signature on it.

## Run

```sh
node main.ts   # writes /output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).

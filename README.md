# aGarden

A living showcase of the **Doppl** method — an Obsidian vault of real runs, where each idea is grown from a case study into a recovered problem and then into one or more actionable answers. This is the floor model: the show, and also a thing that stands on its own.

## The idea

Most analysis stops at the surface complaint. Doppl keeps going. It takes a **case study** — a situation worth understanding — recovers the *actual* problem hiding under the obvious one, then breeds that into **doppls**: the unlocks, opportunities, or solutions that follow once you see the real constraint.

The durable artifact is plain markdown. A human can read a node directly; a machine can parse it into a typed shape. Nothing here is a black box — every conclusion carries its lineage, its evidence, and its score.

## The spine

```
case_study → problem_recovery → doppl → (your move)
```

- **case_study** — the seed. A situation, stated plainly. Not yet a claim, so it isn't scored.
- **problem_recovery** — the recovered problem: surface complaint → deleted assumption → hidden variable → actual problem. Scored.
- **doppl** — the leaf: a claim, its implications, and the opportunities it opens. A single problem can grow several distinct doppls. After a doppl, the path points out of the system — into your action.

Each arrow is one pass of the engine: it generates candidate ideas, measures them on **novelty** and **grounding**, selects survivors, checks feasibility, and a judge rates the result. The winner is compiled into the next node.

## What's in this vault

| Path | What it holds |
| --- | --- |
| `flow/` | The node graph as a nested lineage tree. Each node is one markdown file (`## Trace` · `## Discovery` · `## Growth` · `## Path`); children nest under the node they grew from. |
| `stock/` | Durable domain memory. Admitted discoveries grouped by field — each a load-bearing fact with a synopsis, a grounding line, and a deep-linkable anchor. Stages read stock before searching outward again. |
| `ratings-ledger.json` | The human-ratings ledger: per scored node, the `{rater, score}` entries that average into that node's `scores.human` / `scores.n`. Empty until people rate — the node files hold everything else. |
| `deprecated/` | Retired export dumps from earlier kernel versions. Kept for reference; not the source of truth. |

## Reading it

Open the folder as an **Obsidian vault**. The graph view shows the lineage of every idea and the links from nodes into the stock fields they drew on. Every cross-document reference in this vault is an Obsidian-compatible wikilink — `[[slug-id]]` for a file, `[[slug-id#^anchor]]` for a specific block — so the graph resolves end-to-end: a node's `prev_id` points at its parent node, and each Discovery finding deep-links the exact stock load-bearing fact it used.

Or just read the markdown. Every node opens with its one-line headline; the body walks from inherited context (`Trace`) through what was found (`Discovery`) to what was concluded (`Growth`), ending with where the flow points next (`Path`).

## How scoring reads

- **Measurements** (`0…1`) — instrument readings. Novelty = how far the idea reaches past what's already in the record; grounding = how well it lands on something true and testable.
- **Ratings** (`−5…+5`) — judgments of worth. The judge fills five axes (Novelty, Grounding, Falsifiability, Cost-efficiency, Relevance) and boils them to `scores.judge`. A human gives one gut-read slider (`scores.human`). Negative means value-subtracting, not merely ineffective.

## Where the model lives

The contracts and the model that produced this vault live in the **doppl-prime** repo (`my-docs/the-hut/` and `contracts/`). aGarden is an instance of that model — but it's meant to be legible without it.

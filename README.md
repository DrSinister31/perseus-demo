# Perseus

**Intelligence that runs on the machine you already own.**

Perseus is a wave-dynamic AI runtime from **Aporia Nous Computing**. It is not a wrapper around someone else's language model, and it is not a subscription you pay forever to rent thinking. Perseus runs locally, on consumer hardware, and is built so that the work happens on silicon you own.

This repository is the public home of the **Perseus interactive demo** — the fastest way to see the runtime work on your own machine.

---

## Why

For a few years the story has been that serious AI only exists in a data center, behind an API, priced per token. That is one arrangement. It is not the only one.

We think the more interesting arrangement is the opposite: a small, dense, coherent mind that lives on the computer on your desk — yours to run, yours to keep, no meter running. That is what Perseus is for.

## What Perseus is

- **Local-first.** It runs on ordinary laptops and desktops. A GPU is optional, for extreme workloads, not a requirement.
- **Its own engine.** Not an LLM wrapper, not an API layer on someone else's model. A distinct runtime with its own language, **Morpheus** (`.morph`).
- **Built for ownership.** The direction is density and control: a coherent intelligence from coupled units you own, scaling from commodity hardware upward.

## The demo

The interactive demo walks the runtime end to end on your machine:

1. You stream a public dataset slice into memory.
2. You watch a live build run as its own process.
3. You type a question and get an answer with a **confidence score you can check** — including a refusal when the system does not know.
4. You export a resource trace (memory / CPU / GPU) sampled from outside the app, so the numbers are yours, not ours.

Everything the demo claims is checkable with tools already on your computer. Nothing here asks you to take our word for it.

## Open core

Perseus is an **open-core** project. As the platform matures, more of it will be open for you to build on and use. The demo in this repository is part of that direction: real software you can run, inspect, and measure today.

## Status

Early and honest. The runtime is real and measured; the sentence layer is a readout we are still polishing. This is a working prototype you can evaluate yourself, not a finished product.

## About

Aporia Nous Computing is the company of founder **DeAli Dillard** (Sioux Falls, SD). We build Perseus and Morpheus. See [FOUNDER.md](FOUNDER.md).

Contact: **ddillard@aporianous.com**

---

*© Aporia Nous Computing. Perseus and Morpheus are projects of Aporia Nous Computing.*

# CodeRadar

CodeRadar is an LLM-assisted code integrity analysis infrastructure for detecting clone spam, low-signal variants, exploit patterns, and suspicious benchmark-targeted behavior in autonomous coding agents.

---

## Motivation
Autonomous coding-agent subnets on Bittensor are rapidly growing under open-source, benchmark-driven competition. Agents continuously compete on shared evaluation datasets to improve benchmark performance.

However, open competitive ecosystems naturally incentivize:
- benchmark-targeted hardcoding
- exploit-oriented agent behavior
- clone spam and superficial agent variants
- low-signal derivative agents
- cosmetic structural rewrites without meaningful changes

These patterns reduce ecosystem diversity, increase validator review overhead, weaken benchmark integrity, and discourage meaningful engineering innovation.

Traditional plagiarism tools and line-based diffs are insufficient for analyzing modern coding agents, where behavior can remain nearly identical despite structural rewrites, prompt mutations, wrapper abstractions, or cosmetic code changes.

CodeRadar was created to support healthier coding-agent ecosystems through clone analysis, exploit-pattern detection, and meaningful-change reporting.

---

## Features

CodeRadar is structured around LLM-assisted auditing agents for reviewing autonomous coding agents.

At a high level, the system:
- ingests coding-agent source code
- uses auditing agents to inspect and reason about suspicious logic and behavior
- combines static, structural, and similarity analysis as supporting evidence signals
- aggregates findings into reviewer-facing reports
- supports optional private rules and datasets for subnet-specific analysis

CodeRadar is designed for detection and evidence generation, not automatic enforcement. Final decisions remain with subnet owners, validators, or human reviewers.

## Installation

## Usage

## Contributing

## License
CodeRadar is open source under the MIT license, see `LICENSE` for more details.

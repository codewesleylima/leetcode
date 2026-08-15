[![Universidade Católica de Brasília](https://camo.githubusercontent.com/2c34b8e768674f096c9fa57254e87eae7e6344d414363749d2670cd69e8022b3/68747470733a2f2f69696c692e696f2f3346464f3563462e706e67)](https://camo.githubusercontent.com/2c34b8e768674f096c9fa57254e87eae7e6344d414363749d2670cd69e8022b3/68747470733a2f2f69696c692e696f2f3346464f3563462e706e67)

# 🎯 Data Structures & Algorithms Study Guide

---

## 📖 Abstract

This repository documents a structured experimental protocol for the acquisition and consolidation of proficiency in **Data Structures and Algorithms (DSA)**, using LeetCode-style problem sets as the primary instrumentation for skill measurement. The protocol is not an ad-hoc collection of exercises; it is a systematically sequenced curriculum derived from peer-reviewed findings in cognitive science, applied under controlled scheduling constraints analogous to a mission training program.

The underlying premise is that algorithmic proficiency behaves as a measurable, trainable system property rather than a fixed trait — subject to the same principles of iterative refinement, instrumentation, and performance verification applied in engineering disciplines.

### 1.0 Theoretical Basis

The curriculum design is constrained by four empirically validated findings on skill acquisition and long-term retention:

- **Bjork & Bjork (1992)**, *desirable difficulties* — retrieval performed under moderate difficulty produces stronger and more durable memory traces than low-friction repetition.
- **Ericsson (2008)**, *deliberate practice* — sustained expertise gains require goal-directed practice at the edge of current competence, coupled with immediate, specific feedback.
- **Karpicke & Roediger (2008)**, *spacing effect* — distributed practice across time intervals yields superior long-term retention compared to massed (concentrated) practice.
- **Dunlosky et al. (2013)**, *technique efficacy review* — among all studied learning techniques, interleaved and retrieval-based practice rank highest in evidence-backed effectiveness; passive re-reading ranks lowest.

### 2.0 Applied Methodology

The above findings are operationalized as four concrete protocol mechanisms governing the structure of this repository:

| Mechanism | Empirical Basis | Implementation |
|---|---|---|
| Spaced repetition | Karpicke & Roediger (2008) | Fixed review checkpoints at T+2 and T+7 days |
| Interleaved practice | Dunlosky et al. (2013) | Topics rotate across conceptual blocks rather than being studied in isolated blocks |
| Active recall | Dunlosky et al. (2013) | Self-testing precedes any reference to worked solutions |
| Elaboration | Bjork & Bjork (1992) | Reasoning is externalized in writing and verbally before being considered complete |

---

## 📚 Repository Structure

Complete operational guidelines are in [`CLAUDE.md`](./CLAUDE.md).

```
.
├── CLAUDE.md                        (methodology, study protocols, roadmap)
│
├── topicos/                         (60 folders organized by conceptual blocks)
│   ├── 0-fundamentos/               (Java syntax, pitfalls, Big-O, manual tracing)
│   ├── 1-arrays-strings/            (two pointers, sliding window, binary search)
│   ├── 2-stacks-heaps/              (stack, heap, monotonic, quickselect)
│   ├── 3-grafos-arvores/            (⭐ Critical topic — BFS, DFS, trees)
│   ├── 4-recursao-dp/               (backtracking, memoization, DP, tabulation)
│   ├── 5-complementares/            (intervals, linkedlist, bit, greedy)
│   ├── 6-comunicacao/               (verbal explanations, thinking aloud, protocols)
│   └── 7-comportamental/            (reasoning, communication, self-reflection)
│
│   Each topic is a folder: <block>/<id>-<name>/
│   └── ├── teoria.md                (concept, pattern recognition, Java template)
│       ├── Solucao.java             (final code after manual verification)
│       └── questoes.md              (progressive questions + study sources)
│
├── solucoes/                        (finalized Java solutions per problem)
├── progresso/                       (learning tracking)
│   ├── caderno-erros.md             (error log by category)
│   ├── problemas-resolvidos.md      (problem history, time, status)
│   ├── revisoes-agendadas.md        (spaced review schedule)
│   └── mocks.md                     (practice session results)
└── scratch/                         (drafts in .txt — no autocomplete, simulates real environment)
```

---

## 🎓 Curriculum (60 Topics in 8 Blocks)

### Block 0 — Fundamentals (Critical)
Java syntax, overflow/type pitfalls, Big-O analysis, manual tracing, clean code under pressure. Practiced continuously throughout the curriculum.

### Block 1 — Arrays & Strings (High Priority)
Two-pointer patterns (convergent, divergent), sliding windows (fixed, dynamic), prefix sums, binary search (classical and answer-space). Establishes strong foundation for subsequent topics.

### Block 2 — Stacks, Heaps & Queues (High Priority)
Stack-based parsing, monotonic stack/queue, heap operations, priority queue, two-heap patterns, quickselect. Core data structure competencies.

### Block 3 — Graphs & Trees ⭐ (Maximum Priority)
**Highest-frequency pattern cluster.** Graph representation (adjacency, matrix, implicit), BFS (layered, multi-source), DFS (recursive, iterative), cycle detection, topological sort, Union-Find, Dijkstra, binary trees (LCA, diameter), BST validation, Trie.

### Block 4 — Recursion & Dynamic Programming
Backtracking (subsets, combinations, permutations), memoization (top-down), tabulation (bottom-up), DP in grids, knapsack variants, longest increasing subsequence, longest common subsequence, edit distance.

### Block 5 — Complementary Patterns
Interval merging, sweep line algorithms, linked list operations, matrix traversal, bit manipulation, greedy strategies with exchange arguments, Fisher-Yates shuffling, reservoir sampling.

### Block 6 — Communication (Transversal)
Verbal articulation of algorithm design, narration of problem-solving process, handling incomplete information, requesting guidance, responding to hints, self-correction protocols, technical vocabulary in English.

### Block 7 — Self-Reflection & Learning
Metacognition, error analysis, transfer of learning, consolidation of knowledge, effective recall strategies, sustained attention, motivation management.

---

## 🏃 How to Use This Repository

### Start a New Topic
```bash
/estudo 1.7
```
Opens complete learning flow: concept explanation, pattern recognition triggers, canonical template, progressive questions, 45-minute challenge.

### Solve a Problem
1. Read `topicos/<block>/<id>/teoria.md` — understand the pattern
2. Write solution in `scratch/<problem>.txt` **without IDE** — plain text
3. Manually trace through normal and edge cases
4. Declare completion — migrate to `topicos/<block>/<id>/Solucao.java`
5. Record in `progresso/problemas-resolvidos.md`

### Practice Session (Mock)
```bash
/mock
```
45 minutes, timed, evaluated across 4 dimensions: Problem Solving, Coding, Communication, Verification.

### Review Progress
```bash
/revisao
```
Check spaced review schedule in `progresso/revisoes-agendadas.md`.

### Syntax Drill
```bash
/sintaxe
```
15-minute drill — 14 canonical Java constructs from memory (PriorityQueue, ArrayDeque, HashMap, merge, getOrDefault, StringBuilder, Arrays.fill, sort, adjacency list, toCharArray, char↔int conversions).

---

## 📊 Success Criteria

**Core principle:** Correct solution with clear articulation of reasoning.

### Evaluation Across 4 Dimensions
1. **Problem Solving** — decompose ambiguous statements, select appropriate data structures, justify trade-offs
2. **Coding** — idiomatic Java, modularity, readability without IDE support
3. **Communication** — continuous verbalization of thought process (silence >20s incurs penalty)
4. **Verification** — identify bugs through manual tracing before external feedback

---

## ⚡ Foundational Principles

1. **Write first** — never receive complete solutions; learn pattern recognition
2. **Brute force before optimization** — articulation of naive approach is as important as the optimal solution
3. **Manual verification required** — trace through real inputs before declaring completion
4. **Explicit complexity analysis** — state time and space complexity with justification, not notation alone
5. **Continuous narration** — think aloud while coding; silence indicates lack of understanding
6. **Unaided practice** — this study plan builds autonomous problem-solving capability

---

## 📅 Study Progression

See `CLAUDE.md`, section 8, for detailed day-by-day schedule. Overview:

- **Phase 1:** Fundamentals, Two Pointers, Sliding Window, Binary Search
- **Phase 2:** Stacks, Heaps, BFS, Multi-Source Traversal
- **Phase 3:** DFS, Cycle Detection, Topological Sort, Union-Find, Dijkstra
- **Phase 4:** Trees, Trie, Backtracking, DP Variants, Complementary Patterns
- **Final Phase:** Integrated practice sessions, passive review (no new content)

---

## 🔗 References & Study Materials

### Benchmark Problems & Resources
- **LeetCode:** https://leetcode.com — curated problems referenced in each `questoes.md`
- **NeetCode:** https://neetcode.io — video explanations of algorithmic patterns
- **GeeksforGeeks:** https://geeksforgeeks.org — reference articles and implementations

### Academic Resources
- Cormen, Leiserson, Rivest, Stein. *Introduction to Algorithms* (3rd ed.)
- Sedgewick & Wayne. *Algorithms* (4th ed.)
- Research papers on algorithm pedagogy and problem-solving transfer

---

## 💬 Language

- **Study materials:** Portuguese (primary language of learner)
- **Code & comments:** English (industry standard)
- **Verbal practice:** English (transferable skills)

---

## 🧠 Instrumentation: Learning Principles Under Test

Each principle below functions as an operational variable in the protocol, monitored through the `progresso/` telemetry files rather than assumed by default:

1. **Elaboration** — new patterns are explicitly linked to previously consolidated concepts, not studied in isolation
2. **Interleaving** — problem types are deliberately mixed to force discrimination between superficially similar patterns
3. **Spacing** — practice intervals increase as retention strengthens, per the checkpoint schedule in `progresso/revisoes-agendadas.md`
4. **Active recall** — retrieval is attempted before any solution reference is consulted
5. **Metacognition** — errors are logged and categorized in `progresso/caderno-erros.md`, converting failure into a structured feedback signal
6. **Transfer** — mastery is defined as the ability to recognize a trained pattern inside a previously unseen problem statement, not as memorization of a specific solution

---

## 📋 Closing Statement

Competence in algorithmic problem-solving is treated here as an engineered outcome: the product of a controlled protocol, consistent instrumentation, and iterative correction — not an innate trait. This repository constitutes both the experimental framework and the data-collection apparatus required to produce that outcome under verifiable, repeatable conditions.

---

### 🛺 Author

<table>
  <tr>
    <td align="center">
      <a href="https://www.linkedin.com/in/wesslima/" title="Wesley Lima">
        <img src="https://media.licdn.com/dms/image/v2/D4D03AQGxzuIy-ANfNA/profile-displayphoto-scale_400_400/B4DZ7HT8V.GkAg-/0/1781460357892?e=1788393600&v=beta&t=DwXqM2xhdwxWfMI6aYeDsGFZnhOH420zAy_kfRMRGhY" width="100px;" alt="Wesley Lima Photo"/><br>
        <sub>
          <b>Wesley Lima</b>
        </sub>
      </a>
    </td>
  </tr>
</table>


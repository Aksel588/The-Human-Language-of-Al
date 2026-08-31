# Appendix A: Prompt Patterns

**Structural Forcing Functions for Critical Thinking with AI**

> **PDF Version:** [`appendix-a-prompt-patterns.pdf`](./appendix-a-prompt-patterns.pdf) (Pages 73–73 of *The Human Language of AI*)

---

These patterns are not magical formulas or shortcut hacks. They are structural forcing functions— disciplines of language designed to keep human agency and critical inquiry at the center of every interaction with artificial intelligence.


### 1. Epistemic Framing (The Anti-Sycophancy Anchor)

State your objective, provide precise operational constraints, and explicitly instruct the model to challenge your underlying assumptions rather than validating them.


**Example Prompt:**
```text
I am designing a distributed cache invalidation strategy for a high-throughput event stream. Below is my proposed architecture. Do not flatter my design or provide generic praise. Identify the three most catastrophic failure modes under network partition, and propose a radically simpler alternative.
```


### 2. Socratic Diagnostic Inquiry

Use the model as a demanding professor to test your conceptual understanding rather than asking it to solve problems on your behalf.


**Example Prompt:**
```text
I am studying Raft consensus. Below is my explanation of log replication in my own words. Do not explain the protocol to me. Identify the two weakest points in my reasoning, and ask me two probing diagnostic questions to test my understanding.
```


### 3. Adversarial Edge-Case Generation

Instruct the model to construct non-trivial, hostile test suites to expose hidden bugs in your implementation.


**Example Prompt:**
```text
Here is a Python function that parses user date inputs. Generate ten malicious, non-standard, or boundary-breaking inputs (including timezone anomalies, leap seconds, and Unicode exploits) designed to trigger unhandled exceptions.
```


### 4. The Editorial Red-Pen Filter

When refining prose, force the model to identify empty corporate filler and unwarranted certainty.


**Example Prompt:**
```text
Review the attached draft. Highlight every instance of sycophantic corporate fluff, vague abstractions, and unearned assertions. Suggest specific, concrete details or warranting doubt to replace them.
```


### 5. The Offline Synthesis Closure

Conclude every significant dialogue session by disconnecting from the tool and writing a one-page summary in your own words. If you cannot explain the insights from memory, the interaction was passive consumption rather than genuine learning.


---

### Navigation

[Conclusion: Staying Human](../11-conclusion-staying-human/README.md) | [Table of Contents](../../README.md) | [Appendix B: When Not to Use AI](../13-appendix-b-when-not-to-use-ai/README.md)

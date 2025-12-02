Change Log (2025-12-01)
- added conditionals to strengthen evidence and hallucination guardrails

Module 3: Guardrails

Must include:

Missing/empty section detection

<50-word section warning:

If a section is <50 words --> return message "section very short: summary may be incomplete"

Hallucination-prevention rules:

If a section is missing/empty --> return message "section skipped: no usable text was provided."

Strict Evidence mode:

If evidence_mode = "strict" --> only include claims, equations, and results that appear in the provided text

If sufficient information cannot be found --> explicitly state that the text does not have enough info on the topic

Long-paper chunking strategy (PS2 context window strategy)

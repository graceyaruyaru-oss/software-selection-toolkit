# Selection Process, Step by Step

## 1. Define the problem
- What is going wrong today, in plain words? (cost drifting up, manual work, errors, missing features)
- Who feels it most, and how often?
- What would "fixed" look like a year from now?

**Output:** a short problem statement everyone agrees with.

## 2. Gather requirements
Talk to each team the system touches. For an order integration that means sales, the warehouse, accounting and, indirectly, the customers.
- What do you need it to do every day?
- What breaks today, and what does it cost you when it does?
- Which customer requirements are non-negotiable?

Sort everything into **must-have** and **nice-to-have**. A vendor that misses a must-have leaves the list.

## 3. Build the long list
- Include the current vendor. Staying is always an option and gives a fair baseline.
- Aim for 8-12 candidates so the comparison is real, not a formality.

## 4. Score the long list
- Use the same five lenses for every vendor ([`scoring-matrix.csv`](scoring-matrix.csv)).
- Agree on the weights **before** scoring, so the numbers aren't bent toward a favourite.
- Write one line of evidence behind every score.

## 5. Go deep on the shortlist (2-3 vendors)
- Ask for a demo using **your** scenarios, not their standard script.
- Trace a real transaction end to end: order in, shipment out, invoice sent, payment matched.
- Ask how they handle the awkward cases: one order shipped in several parts, a cancelled line, a price change.
- Confirm the full three-year cost in writing.

## 6. Recommend
- One page, one clear recommendation ([`recommendation-template.md`](recommendation-template.md)).
- State the risks honestly and how each one will be handled.
- Lay out what happens after the decision: contract, setup, testing, training, cutover.

## Principles
- **The current vendor deserves a fair score.** Switching has a cost of its own.
- **Data flow matters most.** A cheaper tool that creates manual corrections costs more within a year.
- **The people doing the daily work see risks that demos hide.** Bring them in before the shortlist is final.

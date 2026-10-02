# Software Selection Toolkit

A practical method for choosing between software vendors when the decision affects several teams at once.

I built this approach while replacing an EDI integration provider at a wholesale distributor. Electronic orders from retail customers flowed through that provider into our inventory, accounting and warehouse processes, so the choice touched sales, the warehouse, accounting and the customers themselves. I compared the existing provider against about ten alternatives and gave the owner a written recommendation to decide from.

Vendor names, prices and customer details are left out. The five lenses and the overall approach are the ones I used; the templates turn them into something any team can reuse.

## The five lenses

Every vendor is scored on the same five questions:

| Lens | The question it answers |
|---|---|
| **Data flow** | How do orders, shipments and invoices move between their system and ours? Where could data get lost or duplicated? |
| **Functionality** | What do we gain or lose compared with today? Which customer requirements does it cover? |
| **Implementation approach** | Who does the setup, how long does it take, and what do our people have to do during the switch? |
| **Cost** | What is the full cost over three years, not just the monthly fee? |
| **Operational fit** | Does it suit how the warehouse and accounting teams actually work day to day? |

## How a selection runs

1. **Define the problem in the business's words.** What is not working today, and what would "fixed" look like?
2. **Gather requirements from each team.** Separate must-haves from nice-to-haves.
3. **Build the long list.** Cast a wide net, then remove anything that fails a must-have.
4. **Score the long list** with [`scoring-matrix.csv`](scoring-matrix.csv).
5. **Go deep on the shortlist.** Demos, reference questions, a test with real transactions where possible.
6. **Write the recommendation** with [`recommendation-template.md`](recommendation-template.md): one page, one clear choice, the risks, and what happens next.

Step-by-step detail and the questions I ask at each stage are in [`selection-process.md`](selection-process.md).

## Files

| File | Use it for |
|---|---|
| [`scoring-matrix.csv`](scoring-matrix.csv) | Weighted scoring of every vendor on the five lenses (opens in Excel or Google Sheets) |
| [`selection-process.md`](selection-process.md) | The full process, with the questions to ask at each stage |
| [`recommendation-template.md`](recommendation-template.md) | A one-page decision memo for leadership |

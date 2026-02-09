# Technical Assessment — Data Scientist & AI Engineer

**Time:** 2.5 hours
**Deliverable:** A notebook (`.ipynb`) containing your code, analysis, and commentary.
**Send to:** pcosta@latencydata.com

---

## Context

You've been given a dataset (`data/company_financials.csv`) containing **financial statements of publicly traded companies** spanning multiple years. The data includes standard financial metrics (revenue, net income, assets, liabilities, cash flow, etc.) as well as **text fields** describing each company's business activity, products, and sector.

Your goal is to understand what drives **future company revenue** — specifically, what information available in a given year helps explain or predict a company's revenue the following year. Beyond that, the problem is deliberately open-ended.

## The Challenge

Analyze this dataset and build the best understanding you can of what drives company revenue over time. There is no prescribed sequence of steps — use your judgment to decide what matters most and where to spend your time. How far you go in any direction is entirely up to you.

Here are some directions you **could** explore (you should NOT try to do all of them):

- **Understand the data.** What do the columns mean? Are there data quality issues? Do all variables behave the way you'd expect?
- **Explore relationships.** Which financial metrics are genuinely informative about future revenue? Are there any that look useful but might be misleading? Think about what information would actually be available at the time of prediction.
- **Build a model.** Predict next year's revenue using the features you think are most appropriate. Justify your choices.
- **Leverage the text fields.** Can you extract useful features from the company descriptions or business activity text? Do they help explain differences in revenue trajectories across companies?
- **Dig into patterns.** Do relationships hold across all sectors, or do some industries behave differently? Are there interesting temporal patterns or anomalies?
- **Anything else** you find interesting or worth investigating.

## What We're Looking For

We value **depth over breadth**. A focused analysis with clear reasoning will always score higher than a scattered attempt to touch everything.

Specifically:

- **Your thought process.** Show us how you think. Comment your code, explain your decisions, and tell us why you chose a particular direction.
- **Critical thinking.** Don't take the data at face value. Question it. If something looks off, say so.
- **Practical judgment.** Not every technique adds value. If you try something and it doesn't work, that's fine — tell us what you learned.
- **Communication.** Write as if you're presenting to a colleague. Clear, concise, and well-structured.

## Practical Notes

- **Python** is strongly preferred, but use whatever you're most effective with.
- You are free to use Google, documentation, ChatGPT, or any tools you would normally use in your day-to-day work.
- You may install any libraries you need.
- Some columns in this dataset use financial terminology you may not be familiar with. That's intentional — part of the challenge is working with unfamiliar data and deciding what matters. Also, note that in financial datasets, some metrics are mathematically derived from others. Before using a variable, it's worth checking whether it's truly independent information or just a transformation of something you already have.
- **2.5 hours is not enough to do everything.** Plan accordingly.

## What Happens Next

If your submission goes well, you'll be invited to present your results and discuss your approach with several members of the team. 


Good luck, and we hope that you find some excitement in the challenge. 

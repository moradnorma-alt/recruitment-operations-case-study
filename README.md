# Recruitment Operations: Sample Workflow & Metrics Case Study

## Overview

This portfolio case study explores a practical question:

**How can a recruitment operations team make its talent pipeline easier
to monitor and improve?**

The project outlines a simple workflow, defines useful metrics, and
includes a small fictional dataset that can be used to practise
reporting. It is designed to demonstrate process thinking and
operational judgment---not to claim experience running a production
recruitment platform.

## The problem

Recruitment teams may lose time when candidate stages are unclear,
handoffs are inconsistent, or funnel performance is difficult to
measure. A lightweight shared workflow can help teams spot where
candidates stall and decide what to investigate next.

## Proposed workflow

1.  **Source** --- record where a candidate entered the pipeline.
2.  **Screen** --- assess basic fit against the role requirements.
3.  **Contact** --- track outreach attempts and responses.
4.  **Qualified** --- record whether the candidate meets agreed
    criteria.
5.  **Presented** --- submit the candidate to the client or project
    owner.
6.  **Activated / Closed** --- record the outcome and a consistent
    reason.

Each stage should have a clear entry condition, an owner, a timestamp,
and a next action.

## Suggested metrics

-   **Stage conversion rate:** candidates entering the next stage
    divided by candidates entering the previous stage.
-   **Time in stage:** time between entering a stage and moving to the
    next one.
-   **Contact response rate:** candidates who respond divided by
    candidates contacted.
-   **Qualification rate:** candidates qualified divided by candidates
    screened.
-   **Activation rate:** candidates activated divided by candidates
    presented, where activation is clearly defined.
-   **Data completeness:** records containing all required fields
    divided by total records.

Metrics should be interpreted with context. For example, a lower
conversion rate may reflect a change in role requirements rather than
poor recruiter performance.

## How I would use the data

1.  Check that stages and definitions are applied consistently.
2.  Compare conversion and time-in-stage metrics.
3.  Identify the largest bottleneck.
4.  Form a specific hypothesis about its cause.
5.  Test a small process change.
6.  Compare results before and after the change, accounting for sample
    size and other changes.
7.  Keep, adjust, or stop the change based on the evidence.

## Included files

-   `sample_pipeline.csv` --- fictional sample records for practice.
-   `metrics_guide.md` --- definitions and example calculations.

## Limitations

-   All sample records are fictional and created for demonstration.
-   The project does not represent a deployed application, an actual
    client engagement, or measured business results.
-   No real candidate, client, or employer data should be added to a
    public repository.

## Possible next iteration

A future version could add a simple dashboard or a spreadsheet report
that calculates stage conversion, response rate, and time in stage from
a larger anonymised dataset.

## Initial Analysis of the Sample Data

**Note:** This dataset contains eight fictional records for demonstration purposes only.

### Observed metrics

- Total records: 8
- Contact response rate: 6/8 (75%)
- Qualification rate: 4/8 (50%)
- Presentation rate: 2/8 (25%)
- Activation rate: 1/8 (12.5%)

### Potential bottlenecks to investigate

1. **Contact and response:** Two records have no recorded response. Review follow-up timing and contact data quality.
2. **Qualification to presentation:** Four records are qualified, but only two are presented. Review the handoff process and stage definitions.
3. **Presentation to activation:** One of two presented records is activated. More data is needed before drawing conclusions.
4. **Data completeness:** Two records are missing complete data. Improving required-field completion could make reporting more reliable.

### Proposed next step

Collect a larger dataset with consistent timestamps, stage definitions, and outcome reasons. Compare conversion rates and time in each stage, then test a small process improvement.

These observations are illustrative and should not be treated as real business results.

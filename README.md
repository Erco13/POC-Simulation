# POC Simulation

------------------------------------------------------------------------

##  What This Project Solves

-   Shows how many matches are High, Medium, or Low confidence
-   Highlights potential problem cases
-   Allows record-level review for deeper analysis

------------------------------------------------------------------------

##  Data Preparation

Before building the dashboard, the dataset was cleaned and structured to
ensure:

-   One row per input record
-   Developed a consistent confidence score
-   Valid match score percentages
-   Removal of malformed or inconsistent identifiers

The goal was to make sure the data model was stable and reliable before
any visualization was created.

------------------------------------------------------------------------

##  Dashboard Structure

Provides a simple summary of: - High Confidence % - Medium Confidence
% - Low Confidence %

This helps quickly answer: "How good is our matching overall?"

### Detailed Analysis

Allows users to: - Review individual input records - Inspect matched
company names - Analyze match score percentages - Validate confidence
levels

This makes it easier to spot edge cases or questionable matches.

------------------------------------------------------------------------

##  Why It Matters

Reliable matching improves: - Data quality - Reporting accuracy - Trust
in automated processes

By separating high-confidence matches from lower-confidence ones, teams
can focus their review efforts where it matters most.

------------------------------------------------------------------------

##  Repository Structure

/clean_data\
BestMatch_PerInput_Final.xlsx

/raw_data\
presalse_data_sample.csv

/powerbi\
Company_Matching_Quality_v2_ClientReady.pbix

/screenshots\
(Dashboard screenshots)

------------------------------------------------------------------------

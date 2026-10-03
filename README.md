

The project involved developing a **KPI Dictionary and Data Quality Contract** for a retail orders dataset. The main objective was to convert an ambiguous business requirement into clearly defined, measurable Key Performance Indicators (KPIs) and establish rules for determining whether the data is reliable enough for business reporting and decision-making.

The work began by studying the raw retail orders dataset and its data dictionary to understand the available fields, business meanings, and expected data-quality rules. The decision owners for different business metrics were identified, and a KPI dictionary was prepared containing more than eight KPIs, including Order Count, Gross Merchandise Value (GMV), Net Sales Value, Units Sold, Average Order Value, Average Discount, Paid Order Rate, Refund Rate, and Failed Payment Rate. Each KPI was documented with its formula, data grain, filters, owner, refresh frequency, and source columns.

A detailed data profiling process was then implemented using Python and Jupyter Notebook. The dataset was tested across important data-quality dimensions such as **completeness, uniqueness, validity, consistency, and freshness**. The profiling identified issues including duplicate order IDs, missing values, invalid dates, invalid quantities, incorrect discount percentages, inconsistent text formatting, and stale data.

Based on these findings, a **Data Quality Contract** was created to define acceptable quality thresholds, failure conditions, responsible owners, and escalation actions. The contract also established rules for data normalization and conditions under which KPI results should or should not be released.

The final work produced an Excel-based KPI Dictionary, an executable data-quality profiling notebook, and a formal Data Quality Contract. Together, these deliverables provide a repeatable framework for producing trustworthy retail KPIs and ensuring that data-quality problems are detected and addressed before they affect business decisions.

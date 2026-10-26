# Mock-Engine-API
Automated Alternative Data Pipeline- Institutional Sentiment &amp; Signal Aggregator


## Work-in-progress creation of production-ready Python ETL pipeline designed to extract, sanitise, and load unstructured sentiment data to augment institutional alpha capture. 

_FEATURES:_

**ROBUST EXCEPTION HANDLING:** The importance of pipeline continuation in the event of network failure; errors are logged, relegated to queue, and retried.
**STRICT SCHEMA VALIDATION:** Clarity of the different field properties - text, numerical and alphanumerical, to make sure there is no cross -contamination before database injection
**AUTOMATED DATA QUALITY REPORTS:** Outputs a daily summary log detailing how many records were processed and if any anomalies were caught.

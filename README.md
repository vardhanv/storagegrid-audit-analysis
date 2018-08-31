# storagegrid-audit-analysis
Generates a performance report (PDF) from a StorageGRID Audit Log file (uses R and Python)

## How to Run

1. Take a StorageGRID log file
2. Run the python script - it will convert the logfile to a CSV
3. Run the R scripit - it will generate a PDF

## Cautions

1. Python script still does not cover all audit messages. If you discover some audit messages that are not supported 
- checkout the python script, 
- add support for that audit message, and check it back in

2. R may not cover all S3 messages (ex. Multi-part uploads) 
- add support for that, or 
- submit a request in the issues page, and i will eventually get to it

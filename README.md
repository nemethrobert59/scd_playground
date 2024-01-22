# SCD-Playground

Welcome to `SCD-Playground`! This repository is dedicated to experimenting with and understanding the various types of Slowly Changing Dimensions (SCD) in data warehousing. By exploring these types, you can learn how to manage and track changes in dimension data over time.

## About Slowly Changing Dimensions (SCD)

Slowly Changing Dimensions are dimensions that change slowly over time, rather than changing on a regular schedule, time-base, or frequency. Understanding how to manage SCDs is crucial for maintaining accurate historical data in a data warehouse.

## SCD Types Covered

1. **Type 0 - Fixed Dimension**: No changes allowed; the original data is preserved.
2. **Type 1 - No History**: Only the current data is stored. When changes occur, the old data is overwritten.
3. **Type 2 - Row Versioning**: Each change creates a new record with a version or timestamp.
4. **Type 3 - Previous Value Column**: Stores current and previous values in the same record.
5. **Type 4 - History Table**: Uses a separate history table to track changes.
6. **Type 6 - Hybrid (1 + 2 + 3)**: Combines techniques from Types 1, 2, and 3.

## Repository Structure

- `/Type0`: Examples and scripts related to Type 0 SCDs.
- `/Type1`: Examples and scripts related to Type 1 SCDs.
- `/Type2`: Examples and scripts related to Type 2 SCDs.
- `/Type3`: Examples and scripts related to Type 3 SCDs.
- `/Type4`: Examples and scripts related to Type 4 SCDs.
- `/Type6`: Examples and scripts related to Type 6 SCDs.
- `/Resources`: Additional resources, readings, and references.

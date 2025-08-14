# DataFusion Performance Reports

[![View Live Reports](https://img.shields.io/badge/View-Live%20Reports-blue)](https://MaduMitha-Ravi.github.io/datafusion-performance-reports/)
[![Apache DataFusion](https://img.shields.io/badge/Apache-DataFusion-orange)](https://github.com/apache/datafusion)

## 📊 Overview

This repository hosts performance benchmark reports for Apache DataFusion, tracking query execution metrics across different commits and versions.

## 🌐 View Reports

**Live Dashboard:** [https://MaduMitha-Ravi.github.io/datafusion-performance-reports/](https://MaduMitha-Ravi.github.io/datafusion-performance-reports/)

## 📈 Metrics Tracked

Our benchmarks monitor the following metrics for 10 different query patterns:

- **Execution Times**: Average, Minimum, Maximum
- **Percentiles**: P70, P80, P90, P95
- **Statistical Analysis**: Median and Standard Deviation
- **Performance Trends**: Improvements and regressions across commits
- **Query Types Tested**:
  - Simple filters
  - Group by aggregations
  - Time window operations
  - Complex multi-condition filters
  - Percentile calculations
  - Distinct operations
  - Top-N sorting
  - Self joins
  - Window functions
  - Subqueries with aggregation

## 📅 Update Schedule

Reports are updated periodically when significant changes are made to DataFusion or when performance investigations are conducted.

## 🔍 Understanding the Reports

### Summary Cards
- **Total Commits**: Number of DataFusion commits benchmarked
- **Benchmark Queries**: Number of unique query patterns tested
- **Avg Query Time**: Overall average execution time across all queries
- **Last Updated**: When the benchmarks were last run

### Performance Charts
- **Stacked Bar Charts**: Show latency breakdown by query type
- **Red Line**: Total combined latency for all queries
- **Colors**: Each query type has a consistent color across commits

### Tables
- **Query Performance Overview**: Compare latest vs previous commit
- **Detailed Metrics**: Full statistical breakdown per query
- **Recent Commits**: Historical performance trend

## 🛠️ Benchmark Configuration

- **Dataset Size**: 1,000,000 rows
- **Iterations per Query**: 1,000 runs
- **Test Data**: Synthetic e-commerce dataset with multiple data types
- **Hardware**: [Specify your hardware when you update this]

## 📝 Report History

| Date | Description | Key Findings |
|------|-------------|--------------|
| Aug 12, 2024 | Latest benchmark run | Performance analysis across 15 commits |

## 🔗 Related Resources

- [Apache DataFusion](https://github.com/apache/datafusion)
- [DataFusion Documentation](https://arrow.apache.org/datafusion/)

## 📄 License

These reports are provided for informational purposes. Apache DataFusion is licensed under the Apache License 2.0.

---

*Generated using private benchmarking infrastructure. For questions about methodology or results, please open an issue.*


# Data Analysis with PySpark
**Analysis Date:** 2025-06-07 04:32:55

### Key Findings:
1. **Average Flights per Customer per Year:** 18.75 flights
2. **Customer Segmentation:** Analysis across 3 loyalty card tiers
3. **Education Impact:** Clear correlation between education level and travel behavior
4. **Geographic Distribution:** Analysis across multiple provinces and cities
5. **Temporal Trends:** Seasonal and yearly patterns identified

## Analysis Steps Completed:

### 1. Data Extraction
- Loaded 3 datasets: calendar, customer_flight_activity, customer_loyalty_history
- Total records processed: 389,065 flight records
- Customer base: 16,737 unique customers

### 2. Data Cleaning
- Handled missing values (473 points_accumulated, 4,238 salary values)
- Removed duplicates (3,871 duplicate flight records)
- Standardized data formats and categorical values
- Dropped empty columns (customer_lifetime_value, enrollment_year, enrollment_month)

### 3. Data Transformation
- Joined flight activity with customer demographics
- Created aggregated views for analysis
- Generated calculated columns:
  - flight_distance_ratio
  - points_per_km  
  - points_utilization_rate
  - customer_value_segment
  - flight_frequency_category
  - points_net_balance

### 4. SQL Analysis
- Answered all 4 required analysis questions
- Performed additional trend and segmentation analysis
- Generated business insights across multiple dimensions

### 5. Data Visualization
- Created 5 comprehensive visualizations
- All charts include proper titles, labels, and legends
- Used professional color schemes and formatting

### 6. Results Export
- Saved results in CSV, Parquet, and JSON formats
- Created documentation and analysis summary

## Output Files Generated:

### CSV Files:
- customer_summary.csv - Customer-level aggregated metrics
- monthly_trends.csv - Time-series analysis data
- loyalty_card_performance.csv - Loyalty program effectiveness
- sql_analysis_summary.csv - Key SQL query results

### Parquet Files:
- customer_flight_complete.parquet - Complete joined dataset
- customer_flight_enhanced.parquet - Enhanced with calculated columns
- yearly_customer_points.parquet - Yearly customer analysis

### JSON Files:
- analysis_insights.json - Key business insights
- education_analysis.json - Education level analysis

## Business Recommendations:

1. **Customer Retention:** Focus on high-value segments showing strong engagement
2. **Loyalty Program:** Optimize point redemption rates across card tiers
3. **Geographic Expansion:** Leverage high-performing regions for growth
4. **Education-Based Marketing:** Tailor campaigns based on education demographics
5. **Seasonal Planning:** Optimize capacity based on temporal patterns

---
**Analysis completed**
Generated on: 2025-06-07 at 04:32:57

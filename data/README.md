# DIGGS Data Files

## 📅 Available January 5, 2026

This directory will contain:

### /sample_diggs_files
- Various DIGGS XML/GML files
- Different project types (buildings, bridges, roads)
- Various test types (SPT, CPT, lab tests)
- Different file sizes for testing

### diggs_database.db
- SQLite database with DIGGS-compliant schema
- Pre-populated with sample data
- Normalized tables for efficient querying
- Indexes for common operations

### /schemas
- DIGGS XSD schema files (see [official DIGGS GitHub](https://github.com/DIGGSml))
- Latest schema development at [schema-dev](https://github.com/DIGGSml/schema-dev)
- Validation schemas
- Documentation of schema elements

## File Naming Convention
```
[project_type]_[test_type]_[size].xml
```

Example:
- `bridge_spt_small.xml`
- `building_lab_tests_large.xml`
- `road_cpt_medium.xml`

## Database Schema Overview

Main tables (preliminary):
- `projects` - Project metadata
- `borings` - Boring locations and depths
- `samples` - Sample information
- `lab_tests` - Laboratory test results
- `field_tests` - In-situ test results
- `soil_layers` - Interpreted soil profiles

---

*Check back on January 5, 2026 for the full dataset!*
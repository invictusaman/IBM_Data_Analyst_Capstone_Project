## Dataset Overview

This assignment utilizes a modified subset of the 2019 Stack Overflow Developer Survey dataset, available under the Open Database License (ODbL). For this assignment, please download and use the provided CSV files rather than the original dataset.

### Dataset Files
- `m5_survey_data_demographics.csv`
- `m5_survey_data_technologies_normalised.csv`

Ensure these files are uploaded as data assets in your Cognos Analytics project.

## Assignment Instructions

### Dashboard Creation
Create three dashboards, each consisting of a single tab with a 2 x 2 rectangle areas layout. Rename each dashboard tab as follows:

1. **Current Technology Usage**
2. **Future Technology Trend**
3. **Demographics**

### Dashboard Details

#### 1. Current Technology Usage
Use the `m5_survey_data_technologies_normalised.csv` data asset to create the following visualizations:

- **Panel 1: Top 10 Language Worked With**
  - **Type**: Bar Chart
  - **Fields**: Bars, Length, Color
  - **Features**: Show value labels, Chart title

- **Panel 2: Top 10 Database Worked With**
  - **Type**: Column Chart
  - **Fields**: Bars, Length, Color
  - **Features**: Show value labels, Chart title

- **Panel 3: Platform Worked With**
  - **Type**: Word Cloud Chart
  - **Fields**: Words, Size, Color
  - **Features**: Chart title

- **Panel 4: Top 10 Web Frameworks Worked With**
  - **Type**: Hierarchy Bubble Chart
  - **Fields**: Bubbles, Size, Color
  - **Features**: Chart title

#### 2. Future Technology Trend
Again, use the `m5_survey_data_technologies_normalised.csv` data asset for the following visualizations:

- **Panel 1: Top 10 Language Desired Next Year**
  - **Type**: Bar Chart
  - **Fields**: Bars, Length, Color
  - **Features**: Show value labels, Chart title

- **Panel 2: Top 10 Database Desired Next Year**
  - **Type**: Column Chart
  - **Fields**: Bars, Length, Color
  - **Features**: Show value labels, Chart title

- **Panel 3: Platform Desired Next Year**
  - **Type**: Tree Map Chart
  - **Fields**: Area hierarchy, Size, Heat
  - **Features**: Contrast label color, Chart title

- **Panel 4: Top 10 Web Frameworks Desired Next Year**
  - **Type**: Hierarchy Bubble Chart
  - **Fields**: Bubbles, Size, Color
  - **Features**: Chart title

#### 3. Demographics
Utilize the `m5_survey_data_demographics.csv` data asset for the following visualizations:

- **Filter**: Exclude entries with Gender other than Man and Woman.

- **Panel 1: Respondent Count by Gender**
  - **Type**: Pie Chart
  - **Fields**: Segments, Size
  - **Features**: Display %, Chart title

- **Panel 2: Respondent Count for Countries**
  - **Type**: Map Chart
  - **Fields**: Regions-Locations, Regions-Location color
  - **Features**: Chart title

- **Panel 3: Respondent Count by Age**
  - **Type**: Line Chart
  - **Fields**: x-axis, y-axis
  - **Features**: Show value labels, Show markers, Chart title

- **Panel 4: Respondent Count by Gender, classified by Formal Education Level**
  - **Type**: Stacked Bar Chart
  - **Fields**: Bars, Length, Color
  - **Features**: Show value labels, Chart title

## Submission Guidelines
- Ensure all dashboards are properly named and visualizations are correctly implemented.
- Double-check the uploaded CSV files in Cognos Analytics.
- Follow the instructions closely for each visualization to ensure successful completion of the assignment. 

---

Feel free to reach out if you have any questions or need further assistance with the assignment!

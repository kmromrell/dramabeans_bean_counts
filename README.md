# dramabeans_bean_counts
This repository contains interactive dashboards developed in Google Sheets that analyze annual “bean count” data from the K-drama fan site [Dramabeans](https://dramabeans.com/2024/12/2024-year-in-review-the-bean-count/). These spreadsheets help non-technical users to identify patterns from the "bean count" (an end-of-year event in which users distribute “beans” to their favorite new dramas based on how many shows they watched that year). In this count, users generally indicate 1) all new shows watched that year, and 2) the number of beans allocated to each show.

Through tallies how often each show was watched vs. awarded beans and calculations of this preference data, these dashboards highlight insights about the dramas that are “Most Popular,” “Most Polarizing,” “Hidden Gems,” etc. These insights are used by site admins to better align content with audience interests and by users seeking drama recommendations.

### Spreadsheets: 
* [2024 Bean Count](https://docs.google.com/spreadsheets/d/1dm5vckr77QCW92UzOKAdIPrwPIidBlj_qi8fV4xKdRo/edit?usp=sharing)
* [2023 Bean Count](https://docs.google.com/spreadsheets/d/1wf7pt5k6NohPdhB83O6betdIG8pU0rYaoy5A1mhzf-k/edit?usp=sharing)
* [2022 Bean Count](https://docs.google.com/spreadsheets/d/1Z_PwDqfpG8z065ygWk20bZyBlsA_dL8GtxLNaytRP6k/edit?usp=sharing)
* [2021 Bean Count](https://docs.google.com/spreadsheets/d/1Kp4w_q9tjuomLAjpjEGa5Z4pLbawOFtF_J5VehRVgso/edit?usp=sharing)
* [2020 Bean Count](https://docs.google.com/spreadsheets/d/1_ie06J185jRj26r_p4ik83A9kkqgjhNNB9FMRaImA4A/edit?usp=sharing)

### Navigation notes:
* Tabs (found on bottom of screen):
  - Tab 1: Analytics based on complete user submissions
  - Tab 2: Descriptive stats for all entries (including incomplete entries)
  - Tab 3: Glossary of terms, calculations, and categories
* Refer to the top-left **note box** for additional context and explanations
* Use filter views (linked in green headers) to sort by metric
* Color gradients highlight statistical extremes

### Functions Used
* `sum()`, `average()`, `median()`, `countif()` to aggregate data and create summary statistics
* `rank()` to reduce sensitivity to extreme values, facilitate relative comparisons, and communicate patterns more clearly
* `if()` and `ifs()` to avoid divide-by-zero errors, filter by range, exclude outliers, and avoid NULL-sorting issues
* `abs()` in combination with calculations to measure magnitude of difference
* Boolean operators `and()` and `or()` to combine logical conditions
* Relational operators (`>`, `<`, `=`, `<>`) to drive conditional logic, particularly in conjunction with `if()`
* Basic calculations (`+`, `-`, `*`, `/`), often nested in multi-layered formulas

### Formatting Tools Used
* **Hyperlinked filter views** for interactive sorting (with view-only access)
* **Conditional formatting** to visually highlight trends
* **Hidden columns** for background calculations
* **Frozen rows**, **merged cells**, **text rotation**, and manual **color formatting** for readability
* **Notes** (rather than comments) to support view-only users
* **Hyperlinks** to link to outside source material

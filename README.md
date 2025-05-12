# dramabeans_bean_counts
This repository houses a collection of user-friendly, interactive dashboards housed on Google Sheets. These spreadsheets display the annual "bean counts" from users of the K drama fan-site, Dramabeans. The "bean count" is an annual event in which, based on the number of newly released K-dramas each viewer has watched, people are allocated a number of "beans" to distribute among their favorite new dramas. An example of this can be found [here](https://dramabeans.com/2024/12/2024-year-in-review-the-bean-count/). While it isn't required, users generally indicate 1) all new shows watched that year, and 2) the number of beans allocated to each show.

With the help of another user, I then tallied the total "beans" allocated to each show as a representation of overall viewer enjoyment. Because users often listed shows that they watched but gave their beans to other shows, I was able to compare watch rate with "beaned" rate. This allowed me to extrapolate different attitudes toward dramas and calculate rankings of "superlatives," discovering which dramas were the most popular, the most loved, the most polarizing, the hidden gems, etc. 

These analytics are represented on the spreadsheet in the "Drama Superlatives" section.

**Spreadsheets**: 
* [2024 Bean Count](https://docs.google.com/spreadsheets/d/1dm5vckr77QCW92UzOKAdIPrwPIidBlj_qi8fV4xKdRo/edit?usp=sharing)
* [2023 Bean Count](https://docs.google.com/spreadsheets/d/1wf7pt5k6NohPdhB83O6betdIG8pU0rYaoy5A1mhzf-k/edit?usp=sharing)
* [2022 Bean Count](https://docs.google.com/spreadsheets/d/1Z_PwDqfpG8z065ygWk20bZyBlsA_dL8GtxLNaytRP6k/edit?usp=sharing)
* [2021 Bean Count](https://docs.google.com/spreadsheets/d/1Kp4w_q9tjuomLAjpjEGa5Z4pLbawOFtF_J5VehRVgso/edit?usp=sharing)
* [2020 Bean Count](https://docs.google.com/spreadsheets/d/1_ie06J185jRj26r_p4ik83A9kkqgjhNNB9FMRaImA4A/edit?usp=sharing)

**Navigation notes:**
* Relevant Tabs
  1. The first tab focuses on the most interesting analytics (including only complete lists that list all dramas watched)
  2. The second tab gives only descriptive statistics for all entries, including those that don't list all watched dramas
  3. The third tab provides a key of terms and calculations
* The note in the upper-left corner provides additional context and explanation to clarify the spreadsheet
* The filter views hyperlinked in the category headings allow users to sort by different metrics
* The conditional formatting serves to highlight noteworthy entries, using a gradient to show extremeness of a metric

**Functions utilized**
* **sum()**, **average()**, **median()**, **countif()** to aggregate data and create summary statistics
* **rank()** to reduce sensitivity to extreme values, facilitate relative comparisons, and communicate patterns more clearly
* **if()** and **ifs()** to avoid divide-by-zero errors, filter by range, exclude outliers, and avoid NULL-sorting issues
* **abs()** in combination with calculations to measure magnitude of difference
* Boolean operators **and()** and **or()** to combine logical conditions
* Relational operators (**>**, **<**, **=**, **<>**) to drive conditional logic, particularly in conjunction with **if()**
* Basic calculations (**+, -, *, /**), often nested in multi-layered formulas

**Formatting tools utilized**
* **Hyperlinked filter views** to enable filtering for users with view-only access
* **Conditional formatting** to apply color coding
* **Merged cells** to increase readability
* **Hidden columns** to house behind-the-scenes calculations
* Manual **color formatting** to highlight column headings
* **Notes** (rather than comments) to support view-only users
* **Text rotation** to maximize readability with tight columns
* **Hyperlinks** to link to outside source material

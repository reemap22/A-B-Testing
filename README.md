## AB Testing for MSU Library 

### Task
Evaluate which version of the current "Interact" button performs best through a 5-way AB Test.

### Overview
The Library of Montana State University wants to improve the performance of the "Interact" button on its website. A 5-way AB Test will be conducted, comparing the original button with new versions: "Learn," "Help," "Connect," and "Services." Click-through-rate (CTR) will be the key metric for performance comparison.

### Context
Understanding user behavior on a library website involves considering the specific needs and intents of visitors. The "Interact" button might not be relevant to all users, and assessing its performance requires a nuanced approach.

### Challenge
Plan, structure, and execute a 5-way AB Test considering the uniqueness of evaluating a library website button's performance.

### Approach

#### 1. Hypothesis Testing:
   - Explore existing data and UI/UX questionnaires.
   - Calculate the length of the AB test based on Minimum Detectable Effect (MDE) and the number of visitors.
   - Set up the 5 tests, defining their length and the versions.

#### 2. Explore Raw Data:
   - Clean and analyze raw data, noting any anomalies.
   - Calculate and compare CTR rates for all 5 versions.

#### 3. Formulate Hypotheses:
   - Define null (H0) and alternative (H1) hypotheses.
   - Specify metrics of interest, MDE, alpha and beta scores, and the test to use (Chi-Square for categorical data).

#### 4. Chi-Square Test:
   - Perform Chi-Square testing for categorical data, comparing the CTRs of all 5 versions.
   - Adjust for cumulated alpha error using Bonferroni correction.

#### 5. Colab Files:
   - Utilize the provided "MSU Library" file for data import and analysis.
   - Review calculations, drop-off rates, and homepage return rates provided by the MSU team.

### Additional Notes
- **Data Skewness:**
  - Acknowledge the skewed distribution of visits among different versions.
  - Rerun the experiment adjusting for CTR definition to consider the element of interest clicks against all clicks on the website.

- **Adjustments for Bias:**
  - Consider that users may not need the "Interact" button or its versions equally.
  - Reflect on the potential bias introduced during the experiment and propose adjustments for more balanced evaluations.

### Skills & Tools
- **Data Collection & Cleaning:**
  - Handle skewed data and ensure accurate calculations.
  - Address biases and potential confounding factors.

- **Hypothesis Testing:**
  - Apply statistical methods to test hypotheses.
  - Define and understand metrics, MDE, and significance levels.

- **AB Testing & Chi-Square Testing:**
  - Plan and execute AB Tests with multiple versions.
  - Use Chi-Square testing for categorical data.
  - Implement Bonferroni correction to adjust for multiple comparisons.

### Recommendations
- Base decisions not only on statistical significance but also on practical significance and the unique context of a library website.
- Consider user feedback and behavior beyond CTR, such as drop-off rates and homepage return rates.
- Propose adjustments for biased data distributions and potential user needs variations.

### Conclusion
The results of the AB Test should guide the MSU Library in choosing the most effective version for the "Interact" button. The nuanced approach and consideration of unique factors in a library context will lead to more informed decisions. The provided Colab files and calculations offer transparency and a basis for further exploration and refinement of the testing approach.

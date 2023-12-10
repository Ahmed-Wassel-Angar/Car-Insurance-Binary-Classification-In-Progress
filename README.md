**CONTEXT:**
- **Stakeholders:** An insurance car company.
- **Context:** The company shared its annual car insurance data and intend comprehend customer behaviors.
- **Dataset:**
  - The dataset has 19 features from there 18 of them are corresponding logs which were taken by the company.
  - The outcome column indicates whether a customer has claimed(1) his loan else (0).
- **Data Dictionary:** ID/ AGE/ GENDER/ RACE/ DRIVING EXPERIENCE/ EDUCATION/ INCOME/ CREDIT SCORE/ VEHICULE OWNERSHIP/ VEHICULE YEAR/ MARRIED/ CHILDREN/ POSTAL CODE/ ANNUAL MILEAGE/ VEHICULE TYPE/ SPEEDING VIOLATIONS/ DUIS/ PAST ACCIDENTS/ OUTCOME.
- **Data Souce:** Public dataset from Kaggle with real observations.
**POST-EDA OBSERVATIONS AND INSIGHTS:**
- **Outcome** is negatively associated with the number of **past accidents**. **Customers who `did not claim their loans have no past accidents**.
- **The more speeding violations a customer have, the more `accidents` and `DUIs` he commits.** These are **unattentioned** drivers. In fact, more experienced drivers with **more `annual mileage`**, more stable martial status(married with children) are **more vigilent and commits less `speeding violations`**. In the same context, 9-year driving experienced cutomers and above are very less probable to claim their loans. The threshold of 9 years is obvious within the dataset.
- **More than 95% of drivers do not have DUIS.**
- **Young customers** (less than 26 years old) **claims more often** their loans.
- **Customer owning vehicules are less** probable to **claim their loans**, have **higher credit scores** and belong to the **upper class category**.
- **Gender has no effect**.
- **Postal Code and Race despite being very unbalanced do not have any impact on the outcome nor on any other feature.**
- The graphs below shows the variations of the number of 'speeding violations', 'DUIS' and 'vehicle ownership' per 'outcome' and the association of some features with each other (particularly that of speeding violations with the number of DUIS, past accidents and annual mileage), thus illustrating some of the aforementioned insights.
![variations of the number of 'speeding violations', 'DUIS' and 'vehicle ownership' per 'outcome'](https://github.com/Ahmed-Wassel-Angar/Project-2/blob/main/Speeding%20Violations%20Variations.png?raw=true)
![Variaitons of speeding violations with the number of DUIS, past accidents and annual mileage](https://github.com/Ahmed-Wassel-Angar/Project-2/blob/main/Outcomes%20vs.png?raw=true)


## Requirements

- pyenv
- python==3.13.2
- pip install -r requirements.txt

This project focuses on applying exploratory data analysis (EDA) techniques to the King County Housing Data and presenting the resulting insights and recommendations to a specific client.
# The Data
- **Dataset:** King County Housing Data, containing information about home sales in King County (USA).
- **Location:** The data is located in the `eda` schema of our database, accessible via DBeaver.
- **Data File:** Save the dataset as a CSV file within the `data` folder of your project repository. This folder is intentionally excluded from Git tracking to avoid uploading the raw data.
- **Data Exploration:** Use DBeaver to explore the two tables within the dataset. Identify the common keys and determine an appropriate JOIN operation to combine the tables for your analysis.
- **Column Descriptions:** Detailed descriptions of the column names can be found in the `column_names.md` file.
- **Addressing Ambiguous Column Names:** As is common in real-world scenarios, some column names might not be immediately clear. In this project, we will simulate a situation where direct client clarification is unavailable. You are expected to research and infer the potential meanings of these ambiguous column names using external resources (e.g., Google).
# The Tasks

1. **Repository Creation:** Create a new repository for this project using the provided [template](https://github.com/neuefische/ds-eda-project-template).

2. **Exploratory Data Analysis and Statistical Analysis:** Conduct thorough EDA and statistical analysis on the King County Housing Data. Based on your analysis, identify and document **at least 3 significant insights** about the overall dataset. One of these insights **must** be related to geographical aspects of the data.

3. **Client Recommendations:** Based on your EDA and chosen client persona (from the list below), formulate **at least 3 actionable recommendations** tailored to their specific needs and objectives.

_Note: You need to select one client from the list provided at the end of this file and tailor your analysis and recommendations from their perspective (either as a buyer or a seller)._

# The Deliverables

0. **New Repository:** A newly created GitHub repository based on the provided [template](https://github.com/neuefische/ds-eda-project-template).
1. **Well-Documented Jupyter Notebook:** A Jupyter Notebook (`.ipynb` file), ideally starting from the provided `EDA.ipynb` template, containing your Python code for data exploration, analysis, and visualization. Ensure your code is well-commented, explaining each step of your analysis. Only include the relevant analysis in your final notebook submission. This notebook must be pushed to your GitHub repository. Refer to the example notebook provided [here](https://www.kaggle.com/ekami66/detailed-exploratory-data-analysis-with-python) for guidance on documentation.
2. **Updated and Organized README.md:** A comprehensive and well-structured `README.md` file in your GitHub repository. This file should serve as the primary source of information for navigating your project, outlining its contents, and providing a brief overview of your findings and recommendations.
3. **Short Presentation:** A concise presentation (Keynote, PowerPoint, Google Slides, or Jupyter Slides) providing a high-level overview of your methodology, key insights, and recommendations. This presentation is intended for a **non-technical audience** (your chosen client) and should be approximately **10 minutes** in duration, followed by a 5-minute discussion. Export your presentation as a **PDF file** and include it in your GitHub repository. **Do not present directly from your Jupyter Notebook.**
4. **_Optional_ - Python Script(s) for Data Processing:** You have the option to create clean and modular Python scripts for data processing and cleaning tasks. These scripts should utilize functions and include docstrings for clarity. You can further enhance this by implementing unit tests for your functions. If you choose to create these scripts, you can then integrate them into your EDA notebook. See the `optional` folder for an example.

# The Clients

- Please choose one of the following clients for whom you will conduct your analysis and formulate recommendations.

_Note: As these clients are fictional, you will need to make reasonable assumptions about their preferences and priorities based on the provided characteristics. Clearly state any assumptions you make in your presentation and Jupyter Notebook (e.g., how you define a "rich neighborhood" for a client wanting to "show off")._

| Name                | Client Type | Characteristics                                                                                                                                                                 |
| ------------------- | ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Thomas Hansen       | Buyer       | 5 kids, no money, wants nice (social) neighborhood, Timing?, Location?                                                                                                          |
| Charles Christensen | Seller      | Invest with big returns, wondering about renovation?, which Neighborhood? Timing?                                                                                               |
| Bonnie Brown        | Seller      | Has house and wants to move soon (timing?), but wants high profit in middle class NH (neighborhood)                                                                             |
| Larry Sanders       | Buyer       | Waterfront , limited budget, nice & isolated but central neighborhood without kids (but got some of his own, just doesn't want his kids to play with other kids .. because of germs) |
| Nicole Johnson      | Buyer       | Lively, central neighborhood, middle price range, right timing (within a year)                                                                                                  |
| Jennifer Montgomery | Buyer       | High budget, wants to show off, timing within a month, waterfront, renovated, high grades, resell within 1 year                                                                                  |
| Bonnie Williams     | Seller      | Has several houses, some in bad neighborhoods, willing to evict people, timing?, big returns, open for renovations                                                              |
| William Rodriguez   | Buyer       | 2 people, country (best timing & non-renovated) & city house (fast & central location), wants two houses                                                                        |
| Erin Robinson       | Buyer       | Invest in poor neighborhood, buying & selling, costs back + little profit, socially responsible                                                                                 |
| Jacob Phillips      | Buyer       | Unlimited Budget, 4+ bathrooms or smaller house nearby, big lot (tennis court & pool), golf, historic, no waterfront                                                            |
| Zachary Brooks      | Seller      | Invests in historical houses, best neighborhoods, high profits, best timing within a year, should renovate?                                                                     |
| Timothy Stevens     | Seller      | Owns expensive houses in the center, needs to get rid, best timing within a year, open for renovation when profits rise                                                         |
| Amy Williams        | Seller      | Mafiosi, sells several central houses(top10%) over time, needs average outskirt houses over time to hide from the FBI                                                   |



# Exploratory data analysis for your final project

Your final project is a **_technical blog post_** that uses a statistical model to answer an environmental data science question. The full description and rubric are on the [course website](https://eds-222-stats-f26.github.io/final-project.html).

This exploratory analysis is the first checkpoint for that project. Like all the final project checkpoints, it is ungraded. Its purpose is to get you started early and give you feedback while your ideas are still taking shape. You are not committing to a question or dataset. Plenty of projects change direction after a first look at the data.

Respond to the prompts below in a new Quarto document named `eda.qmd`. Write in full sentences, and include all the code you used to clean and summarize your data. 

> [!IMPORTANT]
> Put the data in your personal folder on Workbench _outside_ of this repo. Large files cannot be pushed to GitHub and this will help avoid those problems.

## 1. Your question

1. What environmental question are you curious about? State it in one sentence.

Has single-use plastic waste collected in 

How has single-use plastic waste collected during cleanup efforts in Santa Barbara County changed before and after the implementation of single-use plastic restrictions?


2. Why does this question matter, and to whom? Who would make a different decision depending on the answer?

The goal of these ordinance was to reduce the amount of plastic waste carried through waterways onto beaches and into the ocean. Comparing trash data collected before and after single-use plastic ordinances were adopted can help assess whether plastic waste has decreased over time. Evaluating local plastic pollution data as single-use plastic reduction policies have expanded can assess whether policies are meeting their intended goal. An analysis of plastic pollution is important for community members, policymakers, environmental organizations, and local agencies. The results could help guide future decisions about plastic-reduction efforts, outreach, enforcement, and where more cleanup or prevention efforts may be needed.


3. What do you already know about this topic? Name at least one source (e.g., a paper, report, or news article) that gives context for your question.





City of Santa Barbara. (n.d.). Plastic beverage straws, stirrers, and cutlery. https://santabarbaraca.gov/services/utilities/trash-recycling/materials-ordinances/plastic-beverage-straw-stirrers-and-cutlery
County of Santa Barbara. (n.d.). Single-use plastic bag ban ordinance. Less Is More. https://lessismore.org/materials/275-single-use-plastic-bag-ban-ordinance/
Ocean Conservancy. (2025). 2025 International Coastal Cleanup annual report. https://oceanconservancy.org/wp-content/uploads/2025/09/FINAL_ICCAnnualReport_Digital.pdf

4. What is your **response** variable? What is the main **explanatory** variable you think influences it?

The response variable is the amount of plastic found in the local environment through cleanup events.
The explanatory variable is the years before and after single use plastic reduction ordinances.

> [!TIP]
> A good question for this project is specific enough that you can imagine the figure that answers it. "How does climate change affect wildlife?" is too broad. "Has the timing of spring bird migration through California shifted over the past 30 years?" is something you can investigate.

## 2. Your data

1. What dataset(s) will you use to answer your question? Provide the source and a link.
I will be using a dataset containig details on the amound and types of trash found during cleanup events. It was obtained from Ocean Conservancy's trash data portal.

https://www.coastalcleanupdata.org/

2. Who collected these data, how, and why? How might the way the data were collected affect what you can learn from them?
The data was collected by organizations, businesses, community members who participate in cleanup events, including international cleanup day. Data from these cleanups is submitted to the Ocean Conservancy.

3. What does one row in your data represent (e.g., one site, one year, one sample)? How many rows are there?
Each row represents a single cleanup event.

4. Download the data and read it into R. Include the code for cleaning your data, or joining it if you have multiple sources.

## 3. Numerical summaries

1. Summarize your response and explanatory variables numerically (e.g., mean, median, standard deviation, range, counts per category).
2. How much data is missing? Is the missingness concentrated in particular places, times, or groups? What might cause it?
3. Are there any values that seem implausible or surprising?

## 4. Graphical summaries

1. Visualize the **distribution** of your response variable. Describe its shape (e.g., symmetric, skewed, bounded by zero).
2. Visualize the **relationship** between your response and explanatory variables. Describe what you see.
3. Make at least one more figure that shows something about your data you think is important (e.g., variation over space or time, differences between groups, a potential confounding variable).

Every figure should have informative axis labels with units and a caption explaining what it shows.

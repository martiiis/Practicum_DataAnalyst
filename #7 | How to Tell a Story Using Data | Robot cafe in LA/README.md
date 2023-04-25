NOTE: If you can't visualize all of the graphs in the JupyterNotebook file in this repository, please access it from here >> https://nbviewer.org/github/martiiis/Practicum_DataAnalyst/blob/main/%237%20%7C%20How%20to%20Tell%20a%20Story%20Using%20Data%20%7C%20Robot%20cafe%20in%20LA/%237%20%7C%20How%20to%20Tell%20a%20Story%20Using%20Data%20%7C%20Robot%20cafe%20in%20LA.ipynb
# Project description

**Context**

Opening of a small robot-run cafe in Los Angeles. Analysis of the current market conditions

Market research with open-source data on restaurants in LA.


# Table of Contents

**Step 1. Download the data and prepare it for analysis**
   * Data Preprocessing -- Download the data on restaurants in LA. Making sure that the data type for each column is correct and that there are no missing values or duplicates. Processed them if necessary.

**Step 2. Data analysis**

- Investigate the proportions of the various types of establishments. Plot a graph.
- Investigate the proportions of chain and nonchain establishments. Plot a graph.
- Which type of establishment is typically a chain?
- What characterizes chains: many establishments with a small number of seats or a few establishments with a lot of seats?
- Determine the average number of seats for each type of restaurant. On average, which type of restaurant has the greatest number of seats? Plot graphs.
- Put the data on street names from the address column in a separate column.
- Plot a graph of the top ten streets by number of restaurants.
- Find the number of streets that only have one restaurant.
- For streets with a lot of restaurants, look at the distribution of the number of seats. What trends can you see?


**Step 3. Preparing a presentation** 

- Make a presentation of the research to share with investors. You can use any tool you’d like (for example Google Slides or MS PowerPoint) to create it, but you must convert your presentation to PDF format for assessment.

**Step 4. Conclusion** 

- Draw an overall conclusion and provide recommendations on restaurant type and number of seats. Comment on the possibility of developing a chain.

# Description of the data

`rest_data` table:
- `object_name` — establishment name
- `chain` — chain establishment (TRUE/FALSE)
- `object`_type — establishment type
- `address` — address
- `number` — number of seats

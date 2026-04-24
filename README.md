# countryranker

# Which Country Is Best To Live In? - Team 003

## TEAM MEMBERS
* Shreya Bhargava
* Aryan Bolakond
* Sameer Jain
* Issac Lee

## DESCRIPTION
Our project provides a science-based, interactive tool for personalized country rankings. Traditional indices like the Human Development Index (HDI) often use fixed weights that fail to account for individual priorities. Our system replaces these one-size-fits-all rankings with a data-driven application where users can assign custom weights to various quality-of-life factors, such as economic stability, healthcare, safety, and environmental quality.

The application integrates data from the World Happiness Report (2015), the UNDP Human Development Report (2023/24), and the Social Progress Index (2022). By combining these diverse datasets, we enable users to explore trade-offs between different socioeconomic dimensions in real-time. The tool is implemented as a client-side web application that performs all calculations in the browser, offering an objective and transparent decision-making aid for individuals, researchers, and policymakers.

## FILE STRUCTURE
* `index.html`: The main web application interface and embedded styling.
* `ranker/`: Contains the core logic and pre-processed, normalized datasets for the ranking algorithm.

## INSTALLATION
The tool is built using standard web technologies (HTML, CSS, and JavaScript). No server-side installation or specialized backend environment is required as all computations are performed client-side.
1. Extract the `CODE` folder from the `team003final.zip` package.
2. Ensure you have a modern web browser (e.g., Google Chrome, Mozilla Firefox, or Apple Safari) installed on your system.
3. No further dependencies or library installations (e.g., npm, pip) are necessary.

## EXECUTION
To run the ranking tool and view the demo:
1. Navigate to the `CODE` folder.
2. Open the `index.html` file using your web browser (Right-click > Open With > [Your Browser]).
3. **Interactive Features:**
   * Adjust the **Factor Weights** using the sliders in the left panel to see how the rankings change according to your preferences.
   * Use the **Presets** buttons (e.g., Economy first, Health & safety) to instantly apply pre-configured weighting scenarios.
   * Use the **Region Filter** and **Top N** dropdowns in the main panel to refine the country list.
   * Observe the ranking table and Top 3 summary cards update in real-time based on the min-max normalized scoring algorithm.

## DATA SOURCES
For portability, the normalized values of the approximately 40 countries analyzed are embedded directly within the application script. The original raw data can be accessed at the following public sources:
* World Happiness Report (2015): https://worldhappiness.report/ed/2015/
* UNDP Human Development Report (2023/24): https://hdr.undp.org/data-center/human-development-index
* Social Progress Index (2022): https://www.socialprogress.org/

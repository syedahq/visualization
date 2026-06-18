Link: https://open.toronto.ca/dataset/monthly-communicable-disease-surveillance-data/
Data: Month of 2025
    
    > Who is your intended audience? 
    The intended audience icludes public health professionals, policymakers, students and members of the public interested in communicable disease trends in Toronto in the recent year of 2025. I designed the visualization to be understandable by both technical and non-technical audiences, keeping in mind the fact that the audience may have different levels of statistical and epidemiological knowledge. 


    > What information or message are you trying to convey with your visualization? 

    The purpose of the visualization is to show how reported communicable disease cases changed throughout 2025 accross different disease categories in Toronto. By plotting monthly totals for each category, the visualization allows viewers to identify trends, monthly patterns, peaks, declines and differences in disease burden between categories. For example, the graph higlights that Vaccine Preventable Diseases experienced substantial fluctuations throughout the year, while other disease categories remained relatively stable. This encourages viewers to consider how disease incidence changes over time and how different categories contribute to overall public health concerns. 
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    
    Purpose and chart selection: the purpose is to perform a comparison of disease over time, according to in class discussions, choosing appropriate visualizations, such a line graph is well suited for displaying trends across months because it allows viewers to track changes and compare multiple categories simultaneously. 
    
    Visual Hieararchy: The larger flucations in the Vaccine Preventable Diseases naturally draw viewers' attention, helping communicate of the most prominent patterns in the dataset. 

    Percieved factual basis: As discussed in class, 2D graphics, geometric shapes, clean layouts and data sources contribute to perceptions of objectivity. My visualizations follows these conventions through its simple 2D design, use of geometric design, use of geometric lines and markers, and inclusion of clearly labelled axes. 

    Reducing cognitive load: Months are displayed in chronological order, consistent colors and markers used for each disease category, gridlines to help viewers estimate values, descriptive titles and axes labels helping viewers understand purpose of chart. 

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

    I used Rstudio to make this visualization, the data processing steps included aggregating monthly case counts by disease catgeory and generating the line graph. This aligns with the lectures discussion of reproducibility and provenance rhetoric. By citing the dataset source, other researchers can verify the results, reproduce the findings, and update the graph if/when new data becomes available. The data is from Toronto Public Health's Monthly Communicable Disease Surveillance Data, publicly avaialble, this increases transparency which ultimately helps establish trustworthiness. 
    
    > How did you ensure that your data visualization is accessible?  

    Different colors were used to distinguish disease categories while maintaing sufficient constrast between lines. Color is used as an identity channel for categorical data, but I also used different shapes per category for those who may not be able to decipher color, so I moved beyond just color. To improve readability, a descriptive title and axis was added, months are rotated and easily visible, the figure is large to accomodate multiple categories and labels. 

    
    > Who are the individuals and communities who might be impacted by your visualization?  

    Several groups may be affected like Toronto residents, public health officials, healthcare providers, epidemiologists and researchers, policy makers, community health organizations and individuals with communicable diseases. For instance, public health vizualizations can influence how disease risks are understood by the public and how resources are allocated by decision makers. In class, we learned the social impacts of data work, I realize that visualizations can shape public perceptions about health risks and disease prevalance. 
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 

    The original dataset contains monthly surveillance data across multiple communicable disease categories. I seleted month as the temporal variable, disease category as the grouping variable, total monthly case counts as the quantitative measure. I aggregated all reported diseases within each category to create monthly totals. This allowed me to focus on broad disease patterns rather than individual diseases which alone might not have sufficient data and this would increase visual complexity and cognitive load. Overall, this helped me shape the message better. 
    
    > What ‘underwater labour’ contributed to your final data visualization product?

    Healthcare professionals who diagnosed and reported communicable diseases, labs that conducted testing and confirmed cases, public health staff who collected and managed the data, Toronto Public Health analysts who compiled and published monthly reports, government employees who maaintain open data platforms etc. 
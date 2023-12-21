I had a problem getting narrative at the appropriate level of a hierarchy in a monthly financial report with budget vs actual narrative. This is just a simplified version demonstrating key components. 

The Power BI file has two report pages and two tooltip pages. Narrative - Non Hierarchical uses the Layout tooltip page and the Hierarchy Narrative uses the Tooltip page for the tooltip. 

### Narrative - Non Hierarchical: 
This is the working report with the technique I used in production using a measure filtered accordingly to return the correct narrative for each element when scrolled over.

### Hierarchy Narrative:
This simply demonstrates the problem; parent levels return the narrative for the first leaf below them.

The workbook is also included for anyone wanting to play around with it. It's an xlsm file as I included the code to indent the descriptions according to the level in the hierarchy; the actual datasource has way too many to do manually so coding it was much more efficient.

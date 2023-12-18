I have an hierarchical organisational chart against which I want to populate budget vs actual variance analysis in a Power BI report. Each level of the hierarchy has it's own narrative, the parent containing summary analysis of each child. The problem is that I can only get the hierarchy to populate the leaf nodes, specifically, each parent displays the narrative for the first leaf element below it so only the leaf nodes display as required.

The dataset is fairly complex but I have replicated the problem in this simplified *.pbix file that contains hierachical data for country, state and city that demonstrates it perfectly. In this example, I display the narrative both as a value in the matrix and as a tooltip; both display the same problem. In the actual file, I will only be using the tooltip.

Keen to hear if anyone has a workaround or other solution to enable each level of a hierarchy to display its actual narrative, rather than that of the first leaf node.

[Back to Portfolio Home](https://mccarthymorgan.github.io/portfolio/)

# Finding a Graph

For my Critique by Design Assignment I redesigned the graph titled "Productivity Puzzle" in the Wall Street Journal article ["Is a Four-Day Week the Future of Work?"](https://www.wsj.com/articles/is-a-four-day-week-the-future-of-work-11627704011). I selected this graph because I thought the information contained in the graph was extremely interesting, but did not support the article as well as it could have. I also wanted to try to improve a graph that was relatively well done, since we had criquited obviously flawed graphs before. 

The data from the graph comes from the Organization for Economic Cooperation and Development. It utilizes two measurements, the [Average Annual Hours Worked](https://data.oecd.org/emp/hours-worked.htm) and the [GDP Per Hour Worked](https://data.oecd.org/lprdty/gdp-per-hour-worked.htm). The original visualization compares the United States to fifteen other countries, although the data sets contain additional countries not shown in the graph. 

# Critiquing the Visualization

The article asks if companies in the United States could support a four day work week, and compares it to other countries. However, the visualization does not indicate how many hours per year a four- or five-day work week is each year, which makes it difficult to relate the graph to the contents of the article. I also think the graph is quite busy and cramped, without a visual difference to make the United States stand out from the countries that are not discussed in the article. The open and closed points to designate the different years are nice, but since they are a small size and the same color as the line, they tend to blend together. Additionally, the title, while snappy, does not help readers to easily interpret the graph. After a significant amount of time looking at the graph, I realized the United States was one of the only countries that increased the number of annual hours worked from 2009 to 2019, which I think is lost in the business of the graph. I also wanted to try to flip the x- and y-axis to see if that improved reader understanding. We typically think of the y-axis as the dependent variable; since the title of the graph is arguing that productivity is not dependent on hours worked, the productivity should be on the y-axis. 

I think there are several things, however, that the visualization does well that I want to carry on to my final visualization. First, I like the two points, one for 2009 data and one for 2019 data, and the line that connects them. I think it is an effective version of a scatter plot that allows the reader to see change over the past ten years. I think any additional points (like adding a point for 2015, for example) would make the graph way too cluttered and increase the mental load of the reader. I do not intend to switch the type of graph in my final visualization. I also like the countries selected for comparison with the United States. I think they were carefully selected for their similarities to the US economy, which allows for greater comparison. I do not intend to add any countries or take any away. I also like that the graph adds additional context to the article from a trusted data source. I think the numbers the author pulled help readers to compare the productivity vs. hours worked, which is what the article brings into question. 

# Wireframing the Solution

For my wireframe mockups, I tried flipping the x- and y-axis placement, added of lines to designate the hours worked for the 4- and 5-day work week, and tried techniques used to reduce business in the graph (removing all labels besides the United States, only coloring the United States line, and increasing the size). These wireframes are shown below. 

![1](https://user-images.githubusercontent.com/76798733/152893793-94bfcef3-c09b-4eeb-8857-ade3304163e7.jpg)

# Testing the Solution

My first interview was with a grad student in his 20s at Carnegie Mellon who has experience with using technology and reading graphs. He liked the idea of flipping the axis based on the title. He had difficulty understanding the axis labels, and disliked the idea of removing country names since they added context to the graph. He also recommended designating increasing or decreasing hours for each country. He also really liked the type of graph shown, and did not think the values could be captured as simply using a bar chart or line graph. He thought that adding lines for the 4- or 5-day work week might make the graph too cluttered. 

My second interview was with a nursing student in her 20s. Her nursing program involves reading complex charts, but has less reliance on technology. PLACEHOLDER


From their feedback, I decided to keep labels on the graph. Without labels, it was too hard to understand and compare, even if the labels popped up when the mouse hovered over them. I also decided to simplify both the title and axis titles, with more information on the meausrements contained in the subtitles. I also incorporated colors showing if hours worked were increasing or decreasing in my final solution. This graph is intended to be used to compliment the first graph, since it increases the complexity and mental strain of the original graph. However, I do think it is compelling that the US is one of the only countries to increase the number of hours worked from 2009 to 2019. It adds additional depth to the article, even though it does make the graph more complex. 

# Building the Solution

Below are the three graphs I developed for the "Is a Four-Day Week the Future of Work?" article in the Wall Street Journal. I tested using red for increased working hours and green for decreased working hours, but it made the graph too busy. For that reason, I elected to do three seperate visualizations to show the three key takeaways. 

<div class='tableauPlaceholder' id='viz1644277148141' style='position: relative'><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Productivityv_TimeWorked&#47;ProductivitybyHoursWorked' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1644277148141');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';
  vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

<div class='tableauPlaceholder' id='viz1644277313571' style='position: relative'><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Increased&#47;Increased' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>
  var divElement = document.getElementById('viz1644277313571');                    
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';
  vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

<div class='tableauPlaceholder' id='viz1644277399977' style='position: relative'><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Decreased&#47;Decreased' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>
  var divElement = document.getElementById('viz1644277399977');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';
  vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>


I retained the two-point scatter plot contained in the original article, but made the points two seperate colors and the lines grey for decreased mental load. I also kept the countries used for comparison the same, since they made sense with the context of the article. I decreased the font size of the country names, flipped the x- and y-axis, and edited the title and labels for greater clarity. I also added a line to show the average 40-hour work week and 32-hour work week that the article discusses. 

Given more time, I want to explore the story board mode in Tableau. I wanted to step away from Flourish and use a tool with increased functionality and complexity. However, I think with additional practice I could phase through the graphs so I did not have to publish three in a row. I also had to combine two types of graphs to create the scatter and the line plot which reduced my functionality. I was unable to get the second Y axis to disappear without removing the scatter plot.  I also couldn't get the labels to sit exactly above the lines like I wanted them too. I was unable to remove the background lines like I had shown in my wireframe. 

Overall, I really liked redesigning this visualization. It already was strong, but I think flipping the axis and adding better labels and a cohesive storyline makes the Wall Street article stronger. 

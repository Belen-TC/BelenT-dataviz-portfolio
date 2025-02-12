 | [home page](https://belen-tc.github.io/BelenT-dataviz-portfolio/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Critque By Design 
For this assignment, we were tasked with critiquing and redesigning a visualization from [Makeover Monday](https://makeovermonday.co.uk/). The process consisted of five steps designed to guide the creation of an effective visualization. Below is a breakdown of my work through each step.

## Step One: The Visualization
For step one, we had to choose a visualization from Makeover Monday to work with. Makeover Monday is a website that publishes a new visualization every week along with a dataset, allowing participants to create more effective visualizations.

For my project, I selected a visualization featured on the website in April 2023, titled ["Which Country Produces the Most Tomatoes."](https://www.linkedin.com/feed/update/urn:li:activity:7038221922265915394) The original visualization (shown below) was posted in the LinkedIn group "Business Intelligence, Analytics & Data Visualization" and was created using data from the Food and Agriculture Organization of the United Nations.
![gif of visualization](./GIF%20of%20Visualization.gif) 

I chose this visualization because I had never seen an animated bar graph used to show changes over time, making it an interesting challenge to critique and redesign. Since it features animation and various design elements, I considered it outside my usual skill set, which added to the learning opportunity. Additionally, the LinkedIn post provided very little context for the visualization, giving me the chance to rework it in a way that tells a clearer and more compelling story.

## Step two: the critique
For the second step in the process, we were tasked with critiquing the visualization using Stephen Few's ["Data Visualization Effectiveness Profile."](http://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf) This method evaluates a visualization based on seven categories: usefulness, completeness, perceptibility, truthfulness, intuitiveness, aesthetics, and engagement.

Initially, I assessed the visualization within a minute or less, assigning scores on a 1–10 scale based on first impressions. At first glance, I found the graph overwhelming due to unnecessary elements, such as a distracting background image of tomatoes and redundant components like both country names and flags (keeping just the country names would improve clarity). Additionally, while the animated bars effectively showed changes over time, the rapidly changing numbers were difficult to read.

During my second evaluation, some ratings remained the same, while others (such as usefulness) were harder to determine. The visualization is effective for a general audience in illustrating the leading tomato producers and their trends over time. However, for agricultural policymakers, researchers, or professionals, it lacks contextual information on factors influencing production fluctuations, such as global demand, climate change, or policy shifts.

This critique helped me identify key improvements. I would simplify the design by reducing background colors, removing flags, and eliminating unnecessary elements like the donut chart. Furthermore, I would choose the type of visualization based on the intended focus: a line graph for emphasizing trends over time and a bar graph for comparing specific years.

## Step three: Sketch a solution
For the third step in the process, we created sketches to redesign the visualization based on our critiques.

My first sketch (shown below) was a recreation of the animated bar graph in Tableau. Initially, I struggled with the dataset from FAOSTAT because it contained much more information than the original visualization. I had to narrow my focus to specific elements such as, countries, tomato production quantities, and years. Additionally, I had to clean the data by removing duplicate entries, such as redundant listings for "China" and "Mainland China." Once I recreated the visualization without distractions like the background image, it became much clearer how tomato production had changed over time. One key trend stood out: China's production surged rapidly in the 1990s.
![Tableau Gif](./Tableau%20Gif.gif)

Intrigued by this growth, I did some research and discovered that in 1993, private domestic companies began growing tomatoes in China's western highlands. Shortly after, China became the world’s leading producer of processed tomatoes. I decided to center my visualization around this transformation.

For my second sketch (pictured below), I quickly hand-drew a possible line graph. I planned to highlight China’s trend line in red (symbolizing tomatoes) while keeping the other lines gray to make China’s rapid growth stand out. I also believed a line graph would better emphasize the point at which China’s production began accelerating. After sketching this concept, I started building it in Tableau (screenshot of the process shown below).
![Line Graph Sketch](./Line%20Graph%20Sketch.jpg)
![Tableau Line Graph Draft](./Tableau%20Line%20Graph%20Draft.png)

## Step four: Test the solution
For this step, we participated in an in-class critique where we received feedback on our redesign ideas using scripted questions. I used my draft in Tableau during the session. Below are the notes I took from my classmates, labeled as Student 1, Student 2, and Student 3.


| Question | Student 1 | Student 2 | Student 3 |
|----------|-------------|-------------|-------|
| Can you describe what this visualization is telling you?        | "China's tomato production is increasing." Student 1 mentioned that the red line stands out and the color made them think of China. |"The title is catchy and makes you think ooh what's happening." For this student the title helped them see what the story was about. Additionally, they pointed out that to them the red line made them think of the tomatoes. | Student 3 agreed that it was easy to interpret the graph. |  
| After seeing the original design, do you think my interpretation is easier to understand? | Student 1 liked that in my redesign I focused more on a specifc story whereas the original design that have a clear intention. | Student 2 agreed with the other students comments.            | "Oh gosh, there is too much going on." Student 3 thought it was difficult to understand the first graph because of all the elements. He appreciated the simplicity of my interpretation. |
| Do you think the caption is necessary?         | Student 1 agreed with Student 2 and said I should leave the caption. | Student 2 liked the caption because it wasn't necessary to read it to understand the graph but provided more information for those who wanted to learn more.   | Student 3 mentioned that he personally would not read the caption if he came upon the graph. However, he did see how some people would find the information useful.      |
| Is there anything you would change or do differently?         |  Student 1 mentioned that to her it made more sense to have the reference line a little more to the left where the increase of production actually started.            | Student 2 believed the reference line placement line made sense since the title and caption mention that specific year. However, she mentioned she would move the number to be in line with the rest of the x-axis. She also felt that the other country lines should be left grey to highlight China. To help differentiate the other lines she agreed the labels should be on the lines rather than in a separate box/legend.    | Student 3 expressed that he would remove the color legend because it was hard to see which line represented which country since they were all the same color. He recommended that if I wanted to keep the other countries for comparison I should use a different color for each one or add the labels next to the lines.      |

Overall, the feedback confirmed that my visualization effectively highlighted China’s tomato production. However, there were aesthetic elements that could be refined to make the story even clearer. Some critiques conflicted, for example, opinions varied on where to place the reference line and whether to keep all countries in the graph. Understanding the core intention of my design will help me decide which suggestions to implement.

Hearing perspectives from classmates who had not seen the original design or knew the background of the visualization helped me notice aspects I may have overlooked while working on the graph.

## Step five: build the solution
The final step in the process was to create a polished version of our redesign using Tableau, Datawrapper, or GenAI. For this step, I continued refining the draft I had developed in Tableau during steps two and three.

One of the main critiques I addressed was adding country labels at the end of the trend lines. While doing this, I noticed that some countries did not have data for the entire time period shown in the graph. Upon examining the dataset, I realized that the USSR and Russia were listed separately, with one ending in 1991 and the other starting in 1992. To avoid incomplete data, I decided to focus only on the current top tomato-producing countries.

Initially, my graph included ten countries, but labeling all the lines became difficult because they were clustered together. To simplify the visualization while still emphasizing China's rapid rise in production compared to other top producers, I narrowed it down to the top five countries. Additionally, I updated the caption to clarify that the countries shown were the top five producers, ensuring there was no confusion about my selection. After adding the labels, I removed the legend since it was no longer necessary.

One challenge I encountered was aligning the 1993 reference point with the rest of the x-axis. For now, I decided to leave it as is.

Below is my final redesign, illustrating China’s tomato production growth over time. This process reinforced the importance of having a clear story in a visualization. The way data is presented should align with the main message. For example, if my goal had been to highlight the current top producers, a bar graph showing the most recent statistics would have been more effective than a line graph. Going through this process gave me valuable insights and techniques that I can apply to my final project.
<div class='tableauPlaceholder' id='viz1739334211246' style='position: relative'><noscript><a href='#'><img alt='China’s Tomato Boom: The Rise of the World’s Leading Producer After 1993 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;To&#47;TopTomatoProducers&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='TopTomatoProducers&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;To&#47;TopTomatoProducers&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
 var divElement = document.getElementById('viz1739334211246');                    
 var vizElement = divElement.getElementsByTagName('object')[0];                    
 vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
 var scriptElement = document.createElement('script');                    
 scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
 vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

## References
Allen, A. (2007, November 12). Checking out China’s booming tomato business. Slate Magazine. https://slate.com/news-and-politics/2007/11/checking-out-china-s-booming-tomato-business.html

Attaching files - GitHub Docs. (n.d.). GitHub Docs. https://docs.github.com/en/get- started/writing-on-github/working-with-advanced-formatting/attaching-files

FAOSTAT. (n.d.). https://www.fao.org/faostat/en/#data/QCL

LinkedIn. (n.d.). https://www.linkedin.com/feed/update/urn:li:activity:7038221922265915394/

Tutorial: Get Started with Tableau Desktop. (n.d.). Tableau. https://help.tableau.com/current/guides/get-started-tutorial/en-us/get-started-tutorial-home.htm

## AI acknowledgements



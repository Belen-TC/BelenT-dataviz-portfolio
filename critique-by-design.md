 | [home page](https://belen-tc.github.io/BelenT-dataviz-portfolio/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Makeover Monday 
For this assignment, we were tasked with critiquing and redesigning a visualization from [Makeover Monday](https://makeovermonday.co.uk/). The process consisted of five steps designed to guide the creation of an effective visualization. Below is a breakdown of my work through each step.

## Step One: The Visualization
For step one, we had to choose a visualization from Makeover Monday to work with. Makeover Monday is a website that publishes a new visualization every week along with a dataset, allowing participants to create more effective visualizations.

For my project, I selected a visualization featured on the website in April 2023, titled ["Which Country Produces the Most Tomatoes."](https://www.linkedin.com/feed/update/urn:li:activity:7038221922265915394) The original visualization (shown below) was posted in the LinkedIn group "Business Intelligence, Analytics & Data Visualization" and was created using data from the Food and Agriculture Organization of the United Nations.
![gif of visualization](./GIF%20of%20Visualization.gif) 

I chose this visualization because I had never seen an animated bar graph used to show changes over time, making it an interesting challenge to critique and redesign. Since it features animation and various design elements, I considered it outside my usual skill set, which added to the learning opportunity. Additionally, the LinkedIn post provided very little context for the visualization, giving me the chance to rework it in a way that tells a clearer and more compelling story.

## Step two: the critique
For the second step in the process, we were tasked with critiquing the visualization using Stephen Few's ["Data Visualization Effectiveness Profile."](http://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf) This method evaluates a visualization based on seven categories: usefulness, completeness, perceptibility, truthfulness, intuitiveness, aesthetics, and engagement.

Initially, I assessed the visualization within a minute or less, assigning scores on a 1–10 scale based on first impressions. At first glance, I found the graph overwhelming due to unnecessary elements, such as a distracting background image of tomatoes and redundant components like both country names and flags (keeping just the country names would improve clarity). While the animated bars effectively showed changes over time, the rapidly changing numbers were difficult to read.

During my second evaluation, some ratings remained the same, while others (such as usefulness) were harder to determine. The visualization is effective for a general audience in illustrating the leading tomato producers and their trends over time. However, for agricultural policymakers, researchers, or professionals, it lacks contextual information on factors influencing production fluctuations, such as global demand, climate change, or policy shifts.

This critique helped me identify key improvements. I would simplify the design by reducing background colors, removing flags, and eliminating unnecessary elements like the donut chart. Additionally, I would choose the type of visualization based on the intended focus: a line graph for emphasizing trends over time and a bar graph for comparing specific years.

## Step three: Sketch a solution
For the third step in the process, we created sketches to redesign the visualization based on our critiques.

My first sketch (shown below) was a recreation of the animated bar graph in Tableau. Initially, I struggled with the dataset from FAOSTAT because it contained much more information than the original visualization. I had to narrow my focus to specific elements—countries, tomato production quantities, and years. Additionally, I had to clean the data by removing duplicate entries, such as redundant listings for "China" and "Mainland China." Once I recreated the visualization without distractions like the background image, it became much clearer how tomato production had changed over time. One key trend stood out: China's production surged rapidly in the 1990s.
![Tableau Gif](./Tableau%20Gif.gif)

Intrigued by this growth, I did some research and discovered that in 1993, private domestic companies began growing tomatoes in China's western highlands. Shortly after, China became the world’s leading producer of processed tomatoes. I decided to center my visualization around this transformation.

For my second sketch (pictured below), I quickly hand-drew a possible line graph. I planned to highlight China’s trend line in red (symbolizing tomatoes) while keeping the other lines gray to make China’s rapid growth stand out. I also believed a line graph would better emphasize the point at which China’s production began accelerating. After sketching this concept, I started building it in Tableau (screenshot of the process shown below).
![Line Graph Sketch](./Line%20Graph%20Sketch.jpg)
![Tableau Line Graph Draft](./Tableau%20Line%20Graph%20Draft.png)

## Step four: Test the solution

_Before you conduct your interviews, prepare a simple script.  Use this as a guide and as a way to take notes as you go forward. Come up with your own list of questions you want to ask for the selected visualization. Keep the questions broad so you can get the most value out of your feedback. Then, document answers to your questions here._

Questions to ask (modify these for your own interviews): 

- Can you tell me what you think this is?

- Can you describe to me what this is telling you?

- Is there anything you find surprising or confusing?

- Who do you think is the intended audience for this?

- Is there anything you would change or do differently?

Results: 

_Don't identify or share personally identifiable information (PII) about the people you spoke to._


| Question | Interview 1 | Interview 2 |
|----------|-------------|-------------|
|          |             |             |
|          |             |             |
|          |             |             |

Synthesis: 

_What patterns in the feedback emerge?  What did you learn from the feedback?  Based on this feedback, come up with what design changes you think might make the most sense in your final redesign._

## Step five: build the solution

_Include and describe your final solution here. It's also a good idea to summarize your thoughts on the process overall. When you're done with the assignment, this page should all the items mentioned in the assignment page on Canvas(a link or screenshot of the original data visualization, documentation explaining your process, a summary of your wireframes and user feedback, your final, redesigned data visualization, etc.)._

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

## AI acknowledgements
_If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here._


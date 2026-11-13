**Critique by Design**

**Design Selection:**

The design I decided to critique from Make Over Monday was the 
"Best Tacos in San Diego": https://makeovermonday.vercel.app/dataset/2026w18-best-tacos-in-san-diego

I chose this because I love reading food reviews and am always curious to find the best food spots in a city. However, when I started to look at the visual, I found it pretty uninteresting and not as useful as I would have liked. I am not as familiar with San Diego, but I feel pretty sure this visualization (especially the scatterplot of latitude and longitude,) would not be useful even to residents. 

Overall, the visuals are straightforward by keeping the color scheme simple and including titles that quickly describe what you’re looking at. One of the visuals was uninformative; there was a dataset summary statistic included that didn't seem to be telling the audience anything intentional. Another visual was misleading; the “Distribution of Customer Review Scores” graph does not accurately desribe the dataset that was linked. The original design doesn’t include any information that makes me more curious or interested in the topic. I felt interested in creating a visual that hopefully offers more of an interaction from the audience with the dataset provided. 

**Step by Step Methods for Creating New Design**

After selecting the Best Tacos in San Diego design, I followed Stephen Few’s Data Visualization Effectiveness Profile (https://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf) to help me in critiquing the design. I found myself scoring the completeness, perceptibility, truthfulness and engagement low. The scores were low because of the misleading visualizations, the inclusion of the dataset summary, the lack of interactive features and story being told, and because there were a lot of visualizations included. The aesthetics, usefulness, and intuitiveness received average scores. This was because the aesthetics mostly followed some of the lessons we have learned in keeping the graphs simple and straightforward. They had minimal colors and clear descriptive titles. 

The critique exercise was useful, because I found myself starting to understand what I did not want to include in my draft and what I did want to include. I went to Tableau to create my first draft. There, I chose to select a map to visualize the data, because if I were a resident or visiting San Diego, I want to quickly understand how and where I can find the best tacos in the city. 

**Here is the first draft of my design:**
![Critique By Design Draft](https://github.com/pwhalen-lab/TellingStoriesWithData/blob/main/CritiqueByDesign_draft.png)

I met with classmates to get their feedback on my initial design ideas. The following table is a breakdown of key takeaways from our conversations. 

|Feedback         | Things to Keep | Things to Improve   |
|-----------------|----------------|---------------------|
| Student 1, BIDA | Highlight with Review Snippet. The description is really useful | Build a boundary around the area of San Diego. Some of the circles overlap, so maybe do something to make those more distinct. |
| Student 2, MISM | Map with background layer that shows street details |The color scheme was confusing. They thought yellow represented the best taco places, when that was actually the lowest score. Using green when the map already has green isn’t helpful for highlighting the best taco places.  |
| Student 3, MISM | Straight forward title. The map representation was useful for identifying locations.  | The source of the data was still unclear.|
 

Overall, the feedback was positive. I got a sense that I was heading in the right direction. It was useful to hear some nice pointers on how to make an even stronger design for the audience. 

I originally chose green circles to highlight the taco places, because I thought that it would better communicate something positive (great tacos). After receiving feedback from my interviews, I heard that I should choose a color that is higher contrast to the map. I was at first nervous to choose the color red, because I didn’t want it to communicate something negative. However, it is common in food advertising to use yellow and red, because it can make your audience hungry. I thought that maybe going with red would not only stand out & have a good contrast to map colors, but it could also pull the audience in more and potentially get them craving tacos. I selected a black outline for the circles, because one interviewee noted that some of the locations are located close to each other causing the circles to overlap. 

I also heard feedback that the source of the data was still unclear, so I made sure to explicitly note that these reviews were from a local food expert at the food review place “Eater.” 

I made sure to keep the review snippets in the highlights when you toggle over the taco place, because I received a lot of positive feedback that those reviews were useful. 

**Check out my final design below:**

<div class='tableauPlaceholder' id='viz1794515871859' style='position: relative'><noscript><a href='#'><img alt='Highest-Rated Tacos in San DiegoAccording to a Local Food ExpertSource: https:&#47;&#47;sandiego.eater.com&#47;maps&#47;san-diego-best-local-tacos ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Be&#47;BestTaco_MakeoverMonday&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='BestTaco_MakeoverMonday&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Be&#47;BestTaco_MakeoverMonday&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1794515871859');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>


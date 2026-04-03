# Critique by Design

For my data visualization critique, I chose to analyze the data from Gallup's 2024 LGBTQ+ Report. 

## Step 1: Original Visualization 


<a href="https://www.statista.com/chart/18228/share-of-americans-identifying-as-lgbt/" title="Infographic: 7.2 Percent of U.S. Adults Identify as LGBT | Statista"><img src="https://cdn.statcdn.com/Infographic/images/normal/18228.jpeg" alt="Infographic: 7.2 Percent of U.S. Adults Identify as LGBT | Statista" width="100%" height="auto" style="width: 80%; height: auto !important; max-width:760px;-ms-interpolation-mode: bicubic;"/></a>

Source: https://news.gallup.com/poll/470708/lgbt-identification-steady.aspx

I chose this graph because I found the findings intriguing, but I felt the message was getting lost as the original designer was sharing too much data. The more I examined it, the more patterns and stories I saw. I believed it could be improved by focusing on a single narrative. 

## Step 2: The Critique 

The critique of this visualization was completed following Stephen Few's Data Visualization Effectiveness Profile. It is being judged based on seven categories: usefulness, completeness, perceptibility, truthfulness, intuitiveness, aesthetics, and engagement. 

#### Ranking:
- Usefulness: 7/10. The visualization successfully conveys valuable demographic data and patterns. However, it requires some effort from the viewer to understand specific insights.
- Completeness: 7/10. While all necessary data points are present, the lack of visual hierarchy creates a cluttered and disorganized graph. 
- Perceptibility: 6/10. The choice of a bar chart is appropriate for a general audience, but there is too much data, making it difficult to identify patterns quickly or grasp at the main ideas of the graph. 
- Truthfulness: 5/10. The data is technically accurate, but the execution is lacking. 
- Intuitiveness: 6/10. The subject matter is immediately clear, but the layout makes it difficult to track specific trends across the timeline.
- Aesthetics: 4/10. It's not the most enjoyable to look at. The competing colors and crowded elements are distracting. 
- Engagement: 6/10. Despite its flaws, I do think it might inspire people to look more into the data. 

#### Initial Thoughts

What immediately stood out to me about this visualization is the aggressive use of color. It appears the designer attempted to utilize a "rainbow" palette as way to represent the LGBT community. However, this choice prioritized aesthetics over functionality. On a positive note, I think the chart succeeds in making the general ideas easy to understand, specifically the visible growth of the LGBT population over time and the distinct differences between generations.

#### Opportunities for Improvement 

There is room for improvement in both the narrative and the technical execution of the graph. For instance, the “7.2%” figure was repeated twice, which felt unnecessary. The title didn’t do a good job of explaining what the main takeaway of the data seemed to be (that the LGBT population was growing, and that it was mostly growing among the youth). If the objective was to emphasize growth and the generational gap, a slopegraph would have been a better choice.

Other small issues were: 
- Inconsistent Binning: The time intervals are irregular (3 years, 3 years, then 2 years), which can distort the perception of growth speed.
- Granularity Issues: Specific generational percentages are only provided for 2022.
- Visual Clutter: An unnecessary American map icon in the top-right corner that adds no informational value, and the oversized color key at the top takes up valuable real estate that could have been used for the data itself.

#### Redesign Idea

My redesign will focus on narrative clarity. Rather than attempting to convey every available data point, I will aim to identify a single, compelling story and build the visualization around that. I will also move away from the multi-colored palette in favor of a strategic, limited color scheme. This will transform the graphic from a "data dump" into a clear, persuasive narrative that highlights specific trends without overwhelming the viewer.

## Step 3: Sketch a Solution 

![Image](https://github.com/mjpereir/mjpereira-portfolio/blob/main/WhatsApp%20Image%202026-04-02%20at%204.07.42%20PM%20(1).jpeg?raw=true)

For my sketch, I focused on creating a simple, horizontal bar chart with a single narrative. While creating this graph, I kept the principle of less is more in mind. I wanted to ensure that the chart was accesible and didn’t overwhelm the audience as the original one did. My classmates feedback was helpful in pointing out small details, but I was happy to notice that all of them understood my main idea. 

## Step 4: Test the Solution 

|Question | Response | 
| :--- | :---: |
|Can you tell me what you think this is? |This is a horizontal bar chart.| 
|Can you describe to me what this is telling you? |The graph represents the percentage of bisexual people within the LGBT community, divided by generations. |
| Is there anything you find surprising or confusing? | A student expressed confusion about what my x-axis represented. Another student said that my arrows didn’t make sense. | 
|Who do you think is the intended audience for this? | The general US public. | 
|Is there anything you would change or do differently? | A third student suggested moving the percentage numbers from outside the graph to within it, to avoid confusion about what the numbers represented. There was also some discussion about the order of the generations in my sketch, but the consensus was to keep it as it was.| 

This table summarizes the responses my classmates gave me when I presented them with my sketch during Monday's in-class critique. 

## Step 5: Build Your Solution 

<div class='tableauPlaceholder' id='viz1775185983228' style='position: relative'><noscript><a href='#'><img alt='Bisexual Identification Makes Up The Largest Share of LGBT AdultsShare of LGBT adults by generation, 2022 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Assignment34_17751802551010&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Assignment34_17751802551010&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Assignment34_17751802551010&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes'/><param name='language' value='en-US'/><param name='filter' value='publish=yes'/></object></div> <script type='text/javascript'> var divElement = document.getElementById('viz1775185983228'); var vizElement divElement.getElementsByTagName('object')[0]; vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';var scriptElement = document.createElement('script'); scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js'; vizElement.parentNode.insertBefore(scriptElement, vizElement);</script>

I wanted my final graph to closely resemble my sketch because I believed people understood what I was trying to communicate. To create this simple horizontal graph, I cleaned up the data from Gallup's article and pivoted the columns. When creating it, I considered my classmates' feedback: I removed the arrows, eliminated the x-axis to avoid confusion, and moved the percentage numbers inside the bars.

After creating this graph in Tableau, I shared it again with my classmates. Overall, they understood my message, but one of them was confused about the length of the bars. Unlike my sketch, the bars in my final graph exceeded 100%. I explained the reason and added a caption to clarify why in my graph. 

## AI Acknowledgements

I used AI to troubleshoot how to embed images and how to create tables in Github. 


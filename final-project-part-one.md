| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) | 

# Outline 
With a focus on 2024, this project focuses on identifying high need counties in New York specific to health conditions and nutrition. The goal is to provide New York legislators with actionable information on which counties require high financial resources. This is a resource legislators can utilize to advocate for bills and more funding of mobile health clinics or meal delivery organizations in high need counties.  

Effect of Conditions on Health and Finances -- Problem Definition
> This is the reality of seniors ages 50 and older living in New York. The goal is to highlight the negative effects of cardiac, obesity, and injury conditions on senior health. These conditions effect expected life length, quality of life, and costs this state tax payer money that could be spent elsewhere. The audience is New York legislators so they understand which counties have higher counts of each condition and are higher need.
> The problem will first be defined. Brief statistics of large bolded numbers will be provided to introduce and emphasize the effect of cardiac, obesity, and injury conditions on senior health. This is an introduction and discussion of why this topic is important. Because this focus is on New York and their legislators, death rates, health effects, and financial costs of these diagnosis' will be provided.

Effect by Race -- Population Need Identification 
> The goal is also to understand differences between White and Black New Yorkers in order to identify if different races have different needs. This allows legislators to specifically tailor condition and population specific financial and health resources where they are needed most.
> A contrast and comparison barplot between White and Black New Yorkers and their counts of these different conditions will be provided to understand if there is a race population that requires greater focus.
> 
County Analysis of Obesity/Cardiac Health and Meals Delivered -- County Specific Need Identification
> By understanding the correlation of obesity and cardiac counts to meals delivered per county, we can understand if higher delivered meals in a county are associated with less conditions. This, as well as population data, can highlight which counties are high need for conditions and meals delivery. 

>
> Second, 
>
> Lastly, two maps will be created. One will tell describe the population in each county, number of hospitals, and hospital factored count of conditions. The second will utilize joined data of a condition specific data source and meal delivery data source to understand the correlation or overlap of obesity and cardiac counts to meals delivered per county. 



## Initial sketches
The draft focuses on diagnosis count of African Americans because this population is typically negatively disproportionately affected in regards to health results. This is a draft that isolates race to tell a story of effect to a specific population. A similar graph of these diagnosis for white seniors will also be created for a contrast. 

> <div class='tableauPlaceholder' id='viz1795060142235' style='position: relative'><noscript><a href='#'><img alt='ForAfrican American Seniors Ages 50+, Heart Failure is has the Highest Count of Hospital Admissions ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bl&#47;BlacckSeniorsDiagnosis&#47;Sheet2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='BlacckSeniorsDiagnosis&#47;Sheet2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bl&#47;BlacckSeniorsDiagnosis&#47;Sheet2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1795060142235');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

# The data
> Data Source 1
> The data source is from Health.Data.NY.Gov. This contains admission data for health service areas, counties, and facilities for 2024. For seniors 50 and older, the information that will be focused on are the gender, race, ethnicity, length of stay, type of admission, patient disposition[type of daily care they have], and diagnosis. [Data Source](https://catalog.data.gov/dataset/meals-served-by-the-office-for-the-aging-beginning-1974?from_hint=eyJxIjoic2VuaW9yIGhlYWx0aCIsInNvcnQiOiJyZWxldmFuY2UifQ%3D%3D)
>
> For diagnosis, abdominal pain, cardiac conditions, injury, and obesity conditions will be focused. Because county data is available, the county level rates will be analyzed to emphasize areas of high need.
>
> Data Source 2
> Specific to obesity and cardiac conditions, because nutrition effects these conditions, the data source detailing the meals delivered per county will be utilized for a better understanding of counties' meal deliveries in correlation to the cardiac and obesity condition counts.
> [Data Source](https://catalog.data.gov/dataset/meals-served-by-the-office-for-the-aging-beginning-1974?from_hint=eyJxIjoic2VuaW9yIGhlYWx0aCIsInNvcnQiOiJyZWxldmFuY2UifQ%3D%3D)

# Method and medium

> I will utilize Tableau to create the bar plot, maps, and table. 


## References
_[Meals Delivered Data Source](https://catalog.data.gov/dataset/meals-served-by-the-office-for-the-aging-beginning-1974?from_hint=eyJxIjoic2VuaW9yIGhlYWx0aCIsInNvcnQiOiJyZWxldmFuY2UifQ%3D%3D)
[County Conditions Data](https://health.data.ny.gov/Health/Hospital-Inpatient-Discharges-SPARCS-De-Identified/sf4k-39ay/about_data)._

 this assignment here._

## Chloe Florit's Portfolio

---

### Fake News Classification Model

<p>
In this project, I developed a machine learning model to classify news articles as real or fake based on the content of their title, text, or a combination of both.
</p>
<p>
I build three models using TensorFlow:
</p>

<ol>
  <li><strong>Title-Only Model:</strong> Used only the article title as input, applied a text vectorization layer, embedding, dropout, and dense layers.</li>
  <li><strong>Text-Only Model:</strong> Focused solely on the article text, incorporating similar preprocessing and layers as the title model.</li>
  <li><strong>Combined Model:</strong> Used both title and text features, which were concatenated and processed through additional dense layers.</li>
</ol>
<p>
Each model was trained over multiple epochs, with accuracy metrics recorded to compare effectiveness. The combined model, using both title and text, demonstrated superior accuracy in detecting fake news.
</p>
<p>
Model Evaluation: The final model's performance was evaluated on a separate test dataset, achieving strong predictive accuracy (98%). Additionally, I created an embedding visualization of frequently associated words in fake news, with notable terms like “liberal,” “conspiracy,” and “terrorists” clustering closely. This insight reveals thematic word patterns characteristic of fake news content.
</p>

<div class="display">
    {% include interactive_graph4.html %}
</div>
<p>
  
</p>

<p>
  <strong>
    <em>Technical skills:</em>
  </strong>
  Tensorflow, deep learning, natural language processing
</p>
<p>
  <strong>
    <em>Tools:</em>
    
  </strong>
  Python
</p>

[![Open Code](https://img.shields.io/badge/Jupyter-Open_Files-red?logo=Jupyter)](https://github.com/chloe-florit/chloe-florit.github.io/tree/f6bd62295cb70581bc0ab6dd1fe33f49e27cc8bb/fake_news_classification)

---

### NOAA Climate Data

<p>
  <strong>Project overview:</strong>
  In this project, I used NOAA climate data to analyze temperature trends across various global weather stations and developed a database to support interactive data visualizations. Using Python, SQL, and Plotly Express, I structured the data and crafted a database that enables users to query specific temperature records by country, date range, and month.

</p>
<p>
  After organizing the data, I wrote a query function to retrieve temperature data and a function to estimate yearly temperature increases at different stations. This function calculates linear temperature trends using linear regression on historical temperature data, producing a geographic scatter plot with points representing weather stations. The color intensity of each point reflects the estimated yearly increase in temperature at each station, creating a visual summary of warming trends over the specified period.

</p>

<p>
  The final output is an interactive map that allows users to observe temperature changes across various regions, effectively highlighting the impact of climate change through localized temperature trends.
</p>

<div class="display">
    {% include india-example.html %}
</div>
<p>
  
</p>

<p>
  <strong>
    <em>Technical skills:</em>
  </strong>
  regression
</p>
<p>
  <strong>
    <em>Tools:</em>
    
  </strong>
  SQL, Python
</p>


[![Open Code](https://img.shields.io/badge/Jupyter-Open_Files-red?logo=Jupyter)](https://github.com/chloe-florit/chloe-florit.github.io/blob/3c16fd1eaaad101f7579699ea4572db1448f4789/noaa_climate_data.ipynb)


### Dynamic Dashboard: Precipitation and Wind Patterns

Here is the interactive dashboard showing the relationship between ENSO and MJO phases, as well as the analysis of precipitation and wind patterns.

<div class='tableauPlaceholder' id='viz1739757168929' style='position: relative'>
  <noscript>
    <a href='#'>
      <img alt='Precipitation and Wind Patterns: Analyzing ENSO and MJO Phase Relationships' src='https://public.tableau.com/static/images/Bo/Book1_17395109845670/Dashboard2/1_rss.png' style='border: none' />
    </a>
  </noscript>
  <object class='tableauViz' style='display:none;'>
    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
    <param name='embed_code_version' value='3' />
    <param name='site_root' value='' />
    <param name='name' value='Book1_17395109845670/Dashboard2' />
    <param name='tabs' value='no' />
    <param name='toolbar' value='yes' />
    <param name='static_image' value='https://public.tableau.com/static/images/Bo/Book1_17395109845670/Dashboard2/1.png' />
    <param name='animate_transition' value='yes' />
    <param name='display_static_image' value='yes' />
    <param name='display_spinner' value='yes' />
    <param name='display_overlay' value='yes' />
    <param name='display_count' value='yes' />
    <param name='language' value='en-US' />
    <param name='filter' value='publish=yes' />
  </object>
</div>

<script type='text/javascript'>
  var divElement = document.getElementById('viz1739757168929');
  var vizElement = divElement.getElementsByTagName('object')[0];
  if (divElement.offsetWidth > 800) {
    vizElement.style.width = '100%';
    vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';
  } else if (divElement.offsetWidth > 500) {
    vizElement.style.width = '100%';
    vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';
  } else {
    vizElement.style.width = '100%';
    vizElement.style.height = '827px';
  }
  
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>


This is my interactive precipitation Tableau dashboard. Below is the embedded visualization:

<div class='tableauPlaceholder' id='viz1739756238808' style='position: relative'>
  <noscript>
    <a href='#'>
      <img alt='Dashboard 1' src='https://public.tableau.com/static/images/pr/precipitation_17397550273630/Dashboard1/1_rss.png' style='border: none' />
    </a>
  </noscript>
  <object class='tableauViz' style='display:none;'>
    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
    <param name='embed_code_version' value='3' />
    <param name='site_root' value='' />
    <param name='name' value='precipitation_17397550273630/Dashboard1' />
    <param name='tabs' value='no' />
    <param name='toolbar' value='yes' />
    <param name='static_image' value='https://public.tableau.com/static/images/pr/precipitation_17397550273630/Dashboard1/1.png' />
    <param name='animate_transition' value='yes' />
    <param name='display_static_image' value='yes' />
    <param name='display_spinner' value='yes' />
    <param name='display_overlay' value='yes' />
    <param name='display_count' value='yes' />
    <param name='language' value='en-US' />
    <param name='filter' value='publish=yes' />
  </object>
</div>

<script type='text/javascript'>
  var divElement = document.getElementById('viz1739756238808');
  var vizElement = divElement.getElementsByTagName('object')[0];
  if (divElement.offsetWidth > 800) {
    vizElement.style.minWidth = '420px';
    vizElement.style.maxWidth = '650px';
    vizElement.style.width = '100%';
    vizElement.style.minHeight = '587px';
    vizElement.style.maxHeight = '887px';
    vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';
  } else if (divElement.offsetWidth > 500) {
    vizElement.style.minWidth = '420px';
    vizElement.style.maxWidth = '650px';
    vizElement.style.width = '100%';
    vizElement.style.minHeight = '587px';
    vizElement.style.maxHeight = '887px';
    vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';
  } else {
    vizElement.style.width = '100%';
    vizElement.style.height = '727px';
  }

  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>
<p>
  <strong>
    <em>Tools:</em>
    
  </strong>
  Tableau
</p>

---

<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->

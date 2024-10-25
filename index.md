## Chloe Florit's Portfolio

---

### Category Name 1 

[NOAA Climate Data](/sample_page)
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


---
[Fake News Classification Model](/pdf/sample_presentation.pdf)

<p>
In this project, I developed a machine learning model to classify news articles as real or fake based on the content of their title, text, or a combination of both. Using a custom dataset, I implemented a function to preprocess the text by removing stopwords, producing a dataset with two inputs (title and text) and one output (fake or real label). The data was split into training and validation sets, with 20% reserved for validation, and a base rate of 53% was calculated as a benchmark.
</p>
<p>
Three models were built using TensorFlow:
</p>

<ol>
  <li><strong>Title-Only Model:</strong> Used only the article title as input, applied a text vectorization layer, embedding, dropout, and dense layers.</li>
  <li><strong>Text-Only Model:</strong> Focused solely on the article text, incorporating similar preprocessing and layers as the title model.</li>
  <li><strong>Combined Model:</strong> Utilized both title and text features, which were concatenated and processed through additional dense layers.</li>
</ol>
<p>
Each model was trained over multiple epochs, with accuracy metrics recorded to compare effectiveness. The combined model, using both title and text, demonstrated superior accuracy in detecting fake news.
</p>
<p>
Model Evaluation: The final model's performance was evaluated on a separate test dataset, achieving strong predictive accuracy. Additionally, I created an embedding visualization of frequently associated words in fake news, with notable terms like “liberal,” “conspiracy,” and “terrorists” clustering closely. This insight reveals thematic word patterns characteristic of fake news content.
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


---
[Project 3 Title](http://example.com/)
<img src="images/dummy_thumbnail.jpg?raw=true"/>

---

### Category Name 2

- [Project 1 Title](http://example.com/)
- [Project 2 Title](http://example.com/)
- [Project 3 Title](http://example.com/)
- [Project 4 Title](http://example.com/)
- [Project 5 Title](http://example.com/)

---




---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->

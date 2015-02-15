# Backend

The backend module is responsible for the scraping, feature decomposition and metric extraction for each article. 

Top down description of arcitecture: 

1. Each stroy is a word cloud, a bag of words with weights. 
2. Stories get disected for teh following metrics: 
  1. The amount of headline (property on page)
  2. position on page
  3. Normalized font size
  4. Number of pictures attached
  5. Number of link to 
  6. Number of links from
3. 

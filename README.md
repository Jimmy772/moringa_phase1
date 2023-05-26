# Microsofts's New Movie Studio


## Overview
### Problem 
- Okay, so Microsoft sees other big companies making cool video content and wants to join in. They're starting their own movie studio, but they're clueless about making movies. That's where I come in. I have to find out which types of films are doing well at the box office and translate that into actionable insights for the head of Microsoft's studio. This will help them decide what kind of films to create.
### Data Understanding 
- The data I have available to me come from a variety of movie databases, most of it is from TMDb.
- The data represents various movie attributes. Key among them being revenue generated, popularity and ratings which will serve as our success metrics in this analysis.
#### Questions to consider
- Does expensive mean successfull?
- Is studio important to success?
- Are some genres more successful than others?
### Methods
This project uses correlation coefficients as well as visualizations to answer the questions above.
### Results
- Budget and rating have a low positive linear relationship. Therfore it seems that more expensive films don't always result in a good reception by the audience. It should be noted that majority of the highest rated films have a high budget.
<img src="images/budget vs. rating.png" alt="budget vs rating" width="50%" height="50%"/>

- Budget and profit have moderate positive linear relationship. It seems that more expesive films make more profit but doesn't mean that expensive films are more profitable.
<img src="images/budget vs. profit.png" alt="budget vs profit" width="50%" height="50%"/>

- This trend of spend more make more extends to genre and studio.
<img src="images/profit by genre.png" alt="profit by genre" width="50%" height="50%"/>

### Conclusions
The following are the key takeaways from this analysis:
1. Diversify Film Budgets: While budget does have some impact on a film's success, it is not a guarantee of high ratings or profitability. It is recommended to diversify the film budgets and not solely rely on expensive productions. Microsoft should consider a mix of high-budget and moderate-budget films based on the genre, target audience, and expected reception.
2. Focus on Profitable Genres: The analysis suggests that certain genres, such as animation and adventure, tend to be more profitable. Microsoft should prioritize these genres in their film production strategy. However, it is also important to consider market trends, audience preferences, and competition within each genre to create unique and engaging content.
3. Invest in Popular Genres: As the analysis indicates, genres with higher investment tend to be more profitable. Microsoft should allocate resources to genres that have proven to be successful in terms of box office revenue. However, careful consideration should be given to balancing investment with market demand and audience preferences to ensure a positive return on investment.
4. Emphasize Audience Appeal: While the rating of a film is not significantly influenced by its genre, it is crucial to focus on creating content that appeals to a wide audience. Conduct market research and audience segmentation to understand the target demographic's preferences, interests, and trends. This will help Microsoft tailor their films to meet the expectations and needs of their target audience, increasing the chances of success.
5. Collaborate with Established Studios: The analysis suggests that studio success in terms of revenue and profit is influenced by budget. Microsoft's movie studio can consider collaborating with established production studios that have a track record of success in the film industry. This collaboration can provide valuable expertise, resources, and distribution channels to enhance the chances of success for Microsoft's films.
6. Continuous Monitoring of Industry Trends: The film industry is constantly evolving, and trends can shift quickly. It is recommended for Microsoft to stay updated on market trends, emerging genres, and audience preferences through regular market research and monitoring of industry reports. This will enable them to adapt their film production strategy accordingly and stay competitive in the market.
### For More Information
See the full analysis in the [Jupyter Notebook](index.ipynb)
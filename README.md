# AI Versus Human: Whose Digital Paintings are More Popular on Instagram?

## Context
In the past few years, AI has rapidly advanced, influencing various sectors of society, including education, healthcare, logistics, and even artistic creation. Within artistic creation, AI-generated art has gained great popularity and sparked many debates on the comparison of AI-generated art with human-created art. In a study titled *AI-generated vs. Human Artworks: A Perception Bias Towards Artificial Intelligence?* the authors conducted a large-scale empirical study involving 565 participants, discovering that people generally prefer human-generated artworks (Ragot, M., Martin, N. & Cojean, S., 2020). Another study, titled *Humans versus AI: whether and why we prefer human-created compared to AI-created artwork*, utilized experimental and quantitative analysis methods to compare the evaluations of 150 participants on artworks randomly labelled as either human-created or AI-created and found that individuals prefer human-created artworks (Bellaiche et al., 2023). Both studies noted a phenomenon: participants show a preference for artworks created by humans over those generated by AI.

However, the participants in these studies were selected based on research needs, and the sample size was relatively small. This time, I want to broaden the sample size and compare the popularity of AI-generated paintings and human-created digital paintings within the enviroment of social media. Instagram is one of the most popular social media platforms with abundant digital photos posted everyday, so I want to choose Instagram as the data source.  

## Hypothesis:
Human-created Digital Paintings are more popular than AI-generated Paintings on Instagram

## How to Explore?
### Sample: 
10,000 posts of AI-generated art and 10,000 posts of human-created digital art posts in different styles and themes between October 1st 2022 and October 1st 2023. 
### Method: Comparative Study
The popularity is going to be assessed by comparing the number of likes, shares, positive comments, and negative comments between 10,000 posts of AI-generated works and 10,000 posts of human-created works.
### Data Collection and Analysis:
#### Variables (columns):
| Variable        | Variable Description                   | Data Type  |
|----------------------|----------------------------------------|------------|
| post_id              | Unique identifier for each post        | String     |
| pics of each post| Images associated with each post        | Image URLs |
| post_time            | When the post was made        | DateTime   |
| post_type            | AI or Human            | String     |
| likes_num  | Count of likes received on the post     | Numeric    |
| shares_num | Count of times the post has been shared | Numeric    |
| comments             | comments of each post | String    |


#### Source: 
Instagram API
#### Tools and Methods: 
Python, Web Scraping, Data Visualization, Natural Language Processing… 



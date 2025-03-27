# Pandas-DataFrames-and-Data-Exploration 

---
## Project Overview
This project entailed analyzing a dataset that contains posts of articles, the article titles and their URLs, the number of comments an article received after posting, and the total points the post has accumulated since its creation date. 
Pandas was used in the process to explore the data set in order to find out key data aspects such as: 
- The nature of the rows and their values
   - Getting the first five rows
   - Getting the last five rows
  
-  Geting the title column as pandas series and identifying the parameters in the dataset
-  Sourcing the number of rows and columns in the file
-  Other data exploration activities including
   -  Checking out for Duplicates and null values
   -  Getting the summary statistics for the dataframe
### Summary Statistics
| Description  | num_points   | num_comments   |
|--------------|--------------|----------------|
|count         |20,099        |20,099             |
|mean          |50.30         |24.80               |
|std           |107.11        |56.11           |
|min           |1             |1              |
|25%           |3             | 1               |
|50%(median)   |9            |   3             |
|75%           |54           |    21            |
|max           |2,553        |      1,733          |
        
### Explanation of Findings
- The dataset contained 20,099 rows and 7 columns ('id', 'title', 'url', 'num_points', 'num_comments', 'author','created_at') detailing the id number of a post, the title of the post, post's url, number of points the post recieved, the total comments under that post, author of the post, and creation date of the post. 

- All posts received engagement from viewers and the post with the least number of comments and points had one point and one comment.

- Some of the posts got to viral status and others received very high levels of engagement in the comments with the maximum number of points achived by a post being 2,553 and the most commented for post achieving 1,733 comments. However, with the average points and comments per post being 9 and 3 respectively, the statistics show that a majority of the posts received very low engagement levels with regard to the points and the comments they received. 

- Posts that surpassed the top quartile level had high potential for becoming viral and attracting massive engagement.

- Understanding the factors that contributed to a post becoming viral (by performing in-depth analysis of the similarities in posts that get viral) would help improve the engagement among the less performing posts. 











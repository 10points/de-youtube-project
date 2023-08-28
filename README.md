# de-youtube-project

create data pipeline 

## Trending YouTube Video Statistics

![This is an image](https://cdn.marketingoops.com/wp-content/uploads/2018/10/youtube-logo.png.webp)

 *  **About dataset**

    
        This dataset includes several months (and counting) of data on daily trending YouTube videos. 
        Data is included for the US, GB, DE, CA, and FR regions (USA, Great Britain, Germany, Canada, 
        and France, respectively), with up to 200 listed trending videos per day.


        EDIT: Now includes data from RU, MX, KR, JP and IN regions 
        (Russia, Mexico, South Korea, Japan and India respectively) over the same time period.


        Each region’s data is in a separate file. Data includes the video title, 
        channel title, publish time, tags, views, likes and dislikes, 
        description, and comment count.


        The data also includes a category_id field, which varies between regions. 
        To retrieve the categories for a specific video, find it in the associated JSON. 
        One such file is included for each of the five regions in the dataset.


 * **Task**
    - Build a data lake in Amazon S3
    - ETL in AWS Glue Spark jobs
    - SQL using Amazon Athena and Spark SQL
    - Join semi-structured (json) and structured (csv) data
    - Visualize data on Quicksight

 * **Method**

      1. Store data in S3 bucket (Data lake) via AWS CLI in
         >> aws_s3_cli.txt










References

1. [Kaggle: Trending YouTube Video Statistics](https://www.kaggle.com/datasets/datasnaek/youtube-new)

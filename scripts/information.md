Bronze Bucket:
yt-data-pipeline-bronze-manshi

Silver Bucket:
yt-data-pipeline-silver-manshi

Gold Bucket:
yt-data-pipeline-gold-manshi

Script Bucket:
yt-data-pipeline-scripts-manshi

Athena Results Bucket:
yt-data-pipeline-athena-results-manshi

glue databases---

Bronze Database:
yt-data-pipeline-bronze-manshi

Silver Database:
yt-data-pipeline-silver-manshi

Gold Database:
yt-data-pipeline-gold-manshi

Glue Tables---

Bronze Table:
raw_statistics

Silver Tables:
clean_statistics
clean_reference_data

Glue Jobs----
Bronze → Silver:
youtube-data-pipeline-quality

Silver → Gold:
youtube-data-pipeline-silver-to-gold


lambda function----
YouTube Ingestion:
yt-data-pipeline-youtube-ingestion

JSON → Parquet:
yt-data-pipeline-json-to-parquet-dev

Data Quality:
yt-data-pipeline-quality

dq configuration----
DQ Database:
yt-data-pipeline-silver-manshi

DQ Tables:
clean_statistics
clean_reference_data

Athena Output:
s3://yt-data-pipeline-athena-results-manshi/athena-results/

SNS_TOPIC_ARN: arn:aws:sns:ap-south-1:766696031020:yt-data-pipeline-sns-alert

# Two Sample T-test project
The goal of this project is to find out whether unverified users and verified users’ data is statistically different in order find out the details of their relationship. In this project, the variable “video view counts” for users was used to indicate the difference between the users’ type. 

# Methodology:
Two sample t-test method was used in this project to identify the significance of the difference between the average video view counts of different user types.

# Executive Summary
The file "Executive summary.pptx" contains an executive summary of the results of this project ("Activity_Course 4 TikTok project lab.pynb").

# Data Dictionary
This project uses a dataset called `tiktok_dataset.csv`. It contains synthetic data created for this project in partnership with TikTok.

## Dataset Details

- **Number of Rows:** 19,383
- **Columns:** 12

## Column Details

| Column Name | Type | Description |
| --- | --- | --- |
| # | int | TikTok assigned number for video with claim/opinion. |
| claim_status | obj | Whether the published video has been identified as an “opinion” or a “claim.” In this dataset, an “opinion” refers to an individual’s or group’s personal belief or thought. A “claim” refers to information that is either unsourced or from an unverified source. |
| video_id | int | Random identifying number assigned to video upon publication on TikTok. |
| video_duration_sec | int | How long the published video is measured in seconds. |
| video_transcription_text | obj | Transcribed text of the words spoken in the published video. |
| verified_status | obj | Indicates the status of the TikTok user who published the video in terms of their verification, either “verified” or “not verified.” |
| author_ban_status | obj | Indicates the status of the TikTok user who published the video in terms of their permissions: “active,” “under scrutiny,” or “banned.” |
| video_view_count | float | The total number of times the published video has been viewed. |
| video_like_count | float | The total number of times the published video has been liked by other users. |
| video_share_count | float | The total number of times the published video has been shared by other users. |
| video_download_count | float | The total number of times the published video has been downloaded by other users. |
| video_comment_count | float | The total number of comments on the published video. |

Note: Each row represents a different published TikTok video in which a claim/opinion has been made.


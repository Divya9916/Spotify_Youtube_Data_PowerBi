# Spotify & YouTube Music Data Evaluation 

## Project Overview
This project involves the comprehensive cleaning, transformation, and validation of a combined Spotify and YouTube Music dataset using Power BI (Power Query). The objective was to resolve data quality issues—such as missing values, inconsistent formats, and invalid entries—to create a reliable foundation for analyzing artist engagement and audio features across both platforms.

# Repository Structure
<img width="558" height="279" alt="image" src="https://github.com/user-attachments/assets/e2d2056a-8238-43da-8d76-c3a17b0e0b06" />


## Technical Workflow
1. Data Ingestion & Audit
Dataset Exploration: Identified key attributes including track details, artist info, engagement metrics (views, likes, streams), and audio features (danceability, energy, etc.).
Issue Detection: Located null values in critical engagement columns and inconsistent formatting in the "Duration" and "Channel" fields.

2. Power Query Transformations (ETL)
Handling Missing Values:
Engagement metrics (Views/Likes) were analyzed and filled using artist-level averages or removed where data was irrecoverable to maintain statistical integrity.
Addressed nulls in "Official Video" and "Licensed" columns to ensure categorical consistency.

Data Standardization:
Column Renaming: Renamed fields to be more descriptive and user-friendly.
Type Conversion: Corrected data types for numeric audio features and engagement counts.
Text Cleaning: Standardized artist and track names for uniform grouping.

Structural Optimization:
Removed redundant or unnecessary columns to improve dashboard performance.
Reordered columns logically: Identification (Track/Artist) -> Qualitative (Album Type) -> Quantitative (Audio Features) -> Engagement (Streams/Views).

3. Data Validation
Performed final checks to ensure no duplicate records remained.
Validated that audio feature ranges (e.g., Energy, Valence) were within standard 0-1 parameters.

## Key Features Analyzed
Cross-Platform Metrics: Comparison between Spotify Streams and YouTube Views/Likes.
Audio Attributes: Analysis of "Danceability," "Liveness," and "Speechiness" across different track types.
Content Engagement: Evaluating the impact of "Official Videos" and "Licensed" content on total reach.

## Final Deliverables
Cleaned Dataset: A fully processed .pbix file ready for high-level visualization.

Project Documentation: A detailed PDF report outlining the specific cleaning steps, challenges faced, and the methodology used to ensure data reliability.

## Tools Used
Power BI / Power Query: For data cleaning, transformation, and validation.

## Author
Divya Sharma Email: divya649sharma99@gmail.com 
LinkedIn: www.linkedin.com/in/divya9916

## License
This project is open source and available under the MIT License.

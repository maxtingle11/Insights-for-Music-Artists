# Insights for Music Artists
![Insights for Music Artists](images/01_title.jpg)

I am a graduate of the Flatiron School's Data Science Fellowship program. I completed the Washington, DC-based 15-week intensive data science bootcamp in December of 2019. "Insights for Music Artists" is the last in a series of projects where I worked with data retrieved from Spotify's API to practice hypothesis testing, regression and classification analyses, and tuning machine learning algorithms to make predictions. 

For this project, I conducted market segmentation analysis for ~300,000 artists retrieved from Spotify’s Web API using unsupervised learning (clustering and dimensionality reduction) and distance-based clustering. I then developed a Flask web app (deployed via Heroku) that finds artists who share similar audio profiles.


## The Problem: New Artists Have Minimal to No Data
![Spotify Dashboard](images/02_spotify_dashboard.jpg)

Currently, music artists have access to data-backed insights from companies like Spotify, Apple Music, and YouTube (to name a few). The insights provided are derived from listener engagement data (as pictured in the Spotify dashboard above), listener demographic data, streaming data, as well as earned revenue data. 

The problem, however, is that new artists are highly unlikely to have a substantial listenership, meaning that majority of their songs have been streamed under 1,000 times. Therefore, **new artists do not yet have enough data** to fuel the insights provided by these companies, leaving them with minimal insights to inform their marketing efforts.


## The Solution: Artist Insights Web App
![Artist Insights Web App](images/03_web_app.jpg)

I developed a model and subsequent web app that returns useful insights for artists at any point in the development of their listenership, especially for new artists with minimal to no data. The web app does the following:

  1. Returns the name, genre tags, popularity score, and follower count of the entered artist.
  
  2. Finds artists who share similar audio profiles as the entered artist and stratifies the results by popularity score.

  3. Suggests genre tags for the entered artist based on the frequency of the similar artists' genre tags.
  

## Example: Andrew Marks - DJ, Producer, Dance Music Artist
![Andrew Marks](images/04_andrew_marks.jpg)


## To Use the App, Copy Artist's Spotify URI
![Copy Spotify URI](images/05_copy_uri.jpg)


## Sample Artist Insights Report
![Artist Insights Report](images/06_artist_insights_report.jpg)


## Why find similar artists and suggested genre tags?

### Facebook Ads Targeting: Lady Gaga
![Facebook Ads Targeting: Lady Gaga](images/07_facebook_ads_lady_gaga.jpg)

### Facebook Ads Targeting: EDM
![Facebook Ads Targeting: EDM](images/08_facebook_ads_edm.jpg)


## Why stratify similar artists by popularity score?

![Product Adoption Curve](images/09_product_adoption_curve.jpg)

![Target Early Markets](images/10_target_early_markets.jpg)

## Next Steps
![Next Steps](images/11_next_steps.jpg)

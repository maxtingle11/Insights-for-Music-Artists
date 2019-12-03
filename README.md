# Insights for Music Artists
![Insights for Music Artists](images/01_title.jpg)

I am a graduate of the Flatiron School's Data Science Fellowship program. I completed the Washington, DC-based 15-week intensive data science bootcamp in December of 2019. "Insights for Music Artists" is the fourth in a series of projects where I worked with data retrieved from Spotify's API to practice hypothesis testing, regression and classification analyses, and tuning machine learning algorithms to make predictions. 

For this project, I conducted market segmentation analysis for ~300,000 artists retrieved from Spotify’s Web API using unsupervised learning (clustering and dimensionality reduction) and distance-based clustering. I then developed a Flask web app (deployed via Heroku) that finds artists who share similar audio profiles.


## The Problem: New Artists Have Minimal to No Data
![Spotify Dashboard](images/02_spotify_dashboard.jpg)

Currently, music artists have access to data-backed insights from companies like Spotify, Apple Music, and YouTube (to name a few). The insights provided are derived from listener engagement data (as pictured in the Spotify dashboard above), listener demographic data, streaming data, as well as earned revenue data. 

The problem, however, is that new artists are highly unlikely to have a substantial listenership, meaning that majority of their songs have been streamed under 1,000 times. Therefore, **new artists do not yet have enough data** to fuel the insights provided by these companies, leaving them with minimal insights to inform their marketing efforts.


## The Solution: Artist Insights Web App
![Artist Insights Web App](images/03_web_app.jpg)

I developed a model and subsequent web app that returns useful insights for artists at any point in the development of their listenership, especially for new artists with minimal to no data. The web app does the following:

  1. Returns the name, genre tags, popularity score, and follower count of the entered artist.
  
  2. Finds artists who share similar audio profiles to the entered artist and stratifies the results by popularity score.

  3. Suggests genre tags for the entered artist based on the frequency of the similar artists' genre tags.

Web App Link: **<.heroku.com>**


## App Demonstration: Andrew Marks (DJ, Producer, Dance Music Artist)

For a live demonstration of the Artist Insights web app, open Spotify via the desktop or website and log-in to your account. The following process will not work when using the Spotify mobile app. Once logged in, use the search bar at the top to find "Andrew Marks."

![Andrew Marks](images/04_andrew_marks.jpg)

Then, you will need Andrew's Spotify URI to run the Insights Developer. A URI is a unique code that Spotify assigns to each artist, track, album, user, and playlist. To copy Andrew's Spotify URI, click the circle with three dots under his name, hover over the "Share" option, and click on "Copy Spotify URI" to copy his URI (... > Share > Copy Spotify URI).

![Copy Spotify URI](images/05_copy_uri.jpg)

After copying the URI, proceed back to the Artist Insights web app and paste the URI into the text field and click the "Run Insight Developer" button.

![Artist Insights Web App](images/03_web_app.jpg)

The Insights Developer will take about 20 seconds to develop a report, like the one pictured below. 

![Artist Insights Report](images/06_artist_insights_report.jpg)

In the screenshot above, you can see that the app: 

  1. Returned Andrew Marks' name, genre tags (blank because he has not yet been taged by Spotify), popularity score, and follower count;
  
  2. Found 5 artists for each popularity score range who share similar audio profiles to Andrew Marks; and

  3. Suggested 5 genre tags for Andrew Marks based on the genre tags of the similar artists.


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

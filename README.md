# 🎶 Spotify Tracks Analysis: Key Features & Trends

This repository contains an analysis of Spotify track features, exploring the characteristics and trends within a large dataset of songs.

---

## 🚀 Project Overview

The goal of this project was to analyze various Spotify audio features to identify patterns, popular genres, and the overall distribution of song attributes such as **danceability**, **energy**, and **acousticness**. The insights are summarized in the visualizations below.

---

## 📊 Key Findings from the Dashboard

The attached dashboard provides a high-level summary of the dataset's characteristics.

### 1. Feature Distribution (Acousticness & Energy)

* **Acousticness:** The distribution is heavily skewed towards the lower end, suggesting a large number of tracks have **low acoustic qualities** (i.e., they are more synthesized or produced).
* **Energy:** The energy distribution is slightly **left-skewed**, with a peak in the mid-to-high range (around **0.6 to 0.9**). This suggests a tendency toward tracks with **moderate to high perceived intensity and activity**.

### 2. Popularity & Explicit Content

The visualization shows an analysis of **Popularity** against the presence of **Explicit Content**:
<img width="848" height="320" alt="image" src="https://github.com/user-attachments/assets/eb7b6f5f-129c-41d5-a89c-55648dd0d715" />


### 3. Avg Popularity by Genres

The chart displaying the Avg Popularity by genres indicates the most represented categories by track count.

<img width="857" height="318" alt="image" src="https://github.com/user-attachments/assets/41a13413-0591-4353-9a05-025b3c9f9c45" />


---

## 💾 Data Source & Features

The data used for this analysis is sourced from the file `Extension_Task_SpotifyFeatures.xlsx - in.csv`.

### Data Fields

The dataset includes the following key audio features:

| Feature | Description |
| :--- | :--- |
| `genre` | The genre of the track. |
| `artist_name` | The name of the artist. |
| `track_name` | The name of the track. |
| `popularity` | A measure of how popular the track is (0-100). |
| `acousticness` | A confidence measure from 0.0 to 1.0 of whether the track is acoustic. |
| `danceability` | How suitable a track is for dancing (0.0 to 1.0). |
| `duration_ms` | The track's duration in milliseconds. |
| `energy` | A measure of intensity and activity (0.0 to 1.0). |
| `instrumentalness` | Predicts whether a track contains no vocals. |
| `liveness` | Detects the presence of an audience in the recording. |
| `loudness` | The overall loudness in decibels (dB). |
| `speechiness` | The presence of spoken words in the track. |
| `tempo` | The overall estimated tempo of the track in BPM. |
| `valence` | A measure from 0.0 to 1.0 describing the musical positivity conveyed by the track. |

---

## 🖼️ Dashboard Visualization

The following image represents the key findings and distributions analyzed:

![Spotify Dashboard Visualization](https://public.tableau.com/views/SpotifyfeauturesDashboard/SpotifyfeaturesDashboard?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## 🛠️ Repository Structure
<img width="1591" height="735" alt="Screenshot 2025-11-18 153126" src="https://github.com/user-attachments/assets/90c03e71-23cf-4b90-9955-763dcd6bc150" />

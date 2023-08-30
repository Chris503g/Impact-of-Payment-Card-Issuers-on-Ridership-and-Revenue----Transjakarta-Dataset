# Impact-of-Payment-Card-Issuers-on-Ridership-and-Revenue----Transjakarta-Dataset
Transjakarta, a public transportation company based in Jakarta, uses payment cards as tickets for passengers. These payment cards may be issued by various banks or financial institutions. The objective is to investigate whether the choice of payment card issuer influences ridership patterns and revenue generation for Transjakarta.
# Transjakarta Analysis Project

## Overview

This project involves the analysis of transaction data from Transjakarta, a public transportation company based in Jakarta, Indonesia. The dataset contains information about payment card usage, ridership, and revenue for different routes and card issuers.

The primary objectives of this analysis are:

1. **Analyzing the Impact of Payment Card Issuers on Ridership and Revenue**: Investigating how different payment card issuers affect ridership and revenue.

2. **Ridership Patterns**: Examining ridership patterns, including the popularity of routes and card issuers.

3. **Revenue Analysis**: Exploring revenue generation and identifying trends in revenue over time.

4. **Demographic Analysis**: Assessing if demographic factors such as gender and age influence ridership and payment card preferences.

## Data Description

The dataset contains the following columns:

- `transID`: Unique transaction ID
- `payCardID`: Customer's main identifier
- `payCardBank`: Customer's card issuer
- `payCardName`: Customer's name
- `payCardSex`: Customer's gender
- `payCardBirthDate`: Customer's birth year
- `corridorID`: Corridor ID (route ID)
- `corridorName`: Corridor name (route name)
- `direction`: Route direction (0 for Go, 1 for Back)
- `tapInStops`: Tap-in (entrance) stop ID
- `tapInStopsName`: Tap-in (entrance) stop name
- `tapInStopsLat`: Latitude of tap-in stop
- `tapInStopsLon`: Longitude of tap-in stop
- `stopStartSeq`: Stop sequence related to direction
- `tapInTime`: Time of tap-in
- `tapOutStops`: Tap-out (exit) stop ID
- `tapOutStopsName`: Tap-out (exit) stop name
- `tapOutStopsLat`: Latitude of tap-out stop
- `tapOutStopsLon`: Longitude of tap-out stop
- `stopEndSeq`: Stop sequence related to direction
- `tapOutTime`: Time of tap-out
- `payAmount`: Payment amount

## Analysis Steps

This project involves the following analysis steps:

1. **Data Cleaning**: Cleaning the dataset by handling missing values and removing unnecessary columns.

2. **Exploratory Data Analysis (EDA)**: Conducting EDA to gain insights into ridership patterns, payment card distribution, and demographics.

3. **Ridership Analysis**: Analyzing ridership by payment card issuer, route, and demographics.

4. **Revenue Analysis**: Exploring revenue by payment card issuer and trends over time.

5. **Demographic Analysis**: Assessing the influence of gender and age on payment card preferences and ridership.

6. **Geographic Analysis**: Investigating the popularity of card issuers in specific geographic locations.

7. **Correlation Analysis**: Examining correlations between payment card preferences, ridership, and revenue.

8. **Statistical Testing**: Conducting statistical tests (e.g., ANOVA) to identify significant differences in ridership and revenue among card issuers.

## How to Use This Repository

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/transjakarta-analysis.git

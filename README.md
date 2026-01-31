## Hackathon SQL – Criminal Track
## Data Detective – Crime Stories via SQL
## Project Overview

The SQL Analyst Hackathon project, part of the nytk Bootcamp, focuses on analyzing crime data to understand the nature of crimes and the influencing factors. The project aims to help law enforcement and decision-makers improve crime prevention strategies and enhance community safety.

## Domain Overview

The criminal domain is concerned with studying and analyzing crime data to understand its nature and influencing factors, which enables designing innovative solutions and improving crime prevention strategies.

## Data Sources

Local Data (crime_data): Details about victims and perpetrators (age, gender, ethnicity), crime type, and report status.

Global Data (World Crime Index): Crime and safety indicators for 199 cities worldwide, such as Crime Index and Safety Index.

## Why We Chose These Data:

Local data provides an accurate individual-level view to understand crime characteristics.

Global data offers a comparative perspective between cities to classify them by risk and safety.

## The Problem

It is difficult to identify factors associated with high crime rates at both local and global levels, in addition to data challenges such as missing values and duplicates, which complicate direct analysis.

## Analysis Goals

Identify populations most vulnerable to crime locally.

Classify cities globally according to risk and safety levels.

Detect missing data and calculate comprehensive metrics to support security decision-making.

## Key Queries

Crime types associated with high-crime cities (FULL OUTER JOIN, ORDER BY, WHERE).

Age distribution of offenders across cities globally (CROSS JOIN).

Classification of cities into high/medium/low risk (CASE, WHERE, THEN).

Number of victims with unrecorded age (IS NULL, COUNT).

Sum/average/min/max crime index per city (SUM, AVG, MIN, MAX, GROUP BY, HAVING).

Ranking the safest cities (ROW_NUMBER, GROUP BY, HAVING, ORDER BY).

Ranking cities by crime index density (DENSE_RANK, ORDER BY).

Offender characteristics linked to specific crimes (BETWEEN, IN).

Similarities between certain cities (SELF JOIN, LIKE).

## What We Learned from the Analysis

Cities with Crime Index > 83.97 are considered high-risk globally.

Some cities have the same Crime Index, but DENSE_RANK clarified their ranking.

Cities with Safety Index > 52 are safer.

Dividing cities by first letter and RANK showed significant differences between closely ranked cities.

Sum, average, min, and max analysis revealed very high averages for some cities.

## What the Numbers Tell Us

Classification of cities by risk levels.

Identifying populations most associated with specific crime types.

Revealing clear differences between cities and countries.

Supporting predictive models to estimate the likelihood of future crimes.

## Still Unclear

Some missing data affects analysis accuracy.

Similar safety levels do not imply similar crime types.

Need to improve data collection and include important variables such as economy, unemployment, and population density.

## Proposed Solutions

Smart platforms for accurate and real-time data recording.

Interactive city system: heatmaps of safety levels.

Predictive analysis using AI to anticipate crime zones and target populations.

Innovative youth awareness campaigns to promote positive behaviors.

Smart monitoring: cameras and alarms linked to real-time analysis.

## Real-World Examples

“Community Safety” program by the Ministry of Interior.

Smart surveillance cameras in Riyadh and Jeddah.

Digital awareness initiatives for youth via social media.

Smart police centers for rapid report analysis and patrol allocation.

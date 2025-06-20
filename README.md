# Enhancing-Brand-Reputation-with-Social-Media-Monitoring

### Project Overview
AfriTech Electronics Ltd., a leading innovator in the global consumer electronics market, has established a strong presence through its cutting-edge smartphones, tablets, and wearable technologies. Despite its notable revenue performance and growing workforce, the company is now facing reputational challenges that threaten its market standing.
This project focuses on using data analytics to enhance brand reputation by implementing a robust social media monitoring system. The aim is to track online conversations in real time, analyze customer sentiment, identify emerging issues, and respond proactively to protect and improve the brand’s image. The approach integrates data from social media platforms to generate insights that inform crisis management, improve customer engagement, and support marketing and customer service strategies.

#### Business Problem Statement
AfriTech Electronics Ltd. is facing a wave of negative customer sentiment due to recurring complaints about product quality, delayed support responses, and recent product recalls. These issues have fueled negative conversations on social media, reduced customer trust, and opened the door for competitors to gain ground.
Currently, the company lacks an effective system for monitoring social media trends and responding to brand-related issues in a timely manner. Without real-time insights, AfriTech struggles to detect warning signs, prioritize critical customer concerns, or adapt its messaging strategy.
To protect its market share and rebuild customer confidence, the company needs a robust social media monitoring and analytics framework that supports early intervention, improved service delivery, and more effective brand communication.

#### Tech Stack:
- PostgreSQL: Used to create, store, clean, and manage a structured database of large volumes of social media and customer service data.
- Power BI: Developed dashboards showing sentiment trends, complaint categories, crisis alerts, and customer satisfaction metrics.
- PowerPoint: Created stakeholder-friendly presentation summarizing insights and strategic recommendations.

#### Data Source
The dataset for this project is from Amdari website.

####  Database Design and Data Management with PostgreSQL
#### PostgreSQL Scrpit
- [Download Full Code block here](https://github.com/yiadomboakye/Enhancing-Brand-Reputation-with-Social-Media-Monitoring/blob/main/PostgresSQL%20Script.ssmssln)
``` CREATE DATABASE AfriTechDB;
CREATE TABLE StagingData(
CustomerID INT,
CustomerName TEXT,
Region TEXT,
Age INT,
Income NUMERIC(10,2),
CustomerType TEXT,
TransactionYear TEXT,
TransactionDate DATE,
ProductPurchased TEXT,
PurchaseAmount NUMERIC(10,2),
ProductRecalled BOOLEAN,
Competitor TEXT,
InteractionDate DATE,
Platform TEXT,
PostType TEXT,
EngagementLikes INT,
EngagementShares INT,
EngagementComments INT,
UserFollowers INT,
InfluencerScore NUMERIC(10,2),
BrandMention BOOLEAN,
CompetitorMention BOOLEAN,
Sentiment TEXT,
CrisisEventTime DATE,
FirstResponseTime DATE,
ResolutionStatus BOOLEAN,
NPSResponse INT
);






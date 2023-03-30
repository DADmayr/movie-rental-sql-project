# Rockbuster Stealth Data Analysis Project
Project concluded in the framework of the *CareerFoundry Data Analytics Programme*

## The Project
The fictional movie rental company *Rockbuster Stealth LLC* wants to launch an online video rental service. An analysis of Rockbuster's rental data is supposed to inform the launch strategy for this service. The business intelligence (BI) department of the fictional company wants to see the following questions answered:
+ Which movies contributed the most/least to revenue gain?
+ What was the average rental duration for all videos?
+ Which countries are Rockbuster customers based in?
+ Where are customers with a high lifetime value based?
+ Do sales figures vary between geographic regions?

## The Data
The dataset provided by *CareerFoundry* in the context of its *Data Analytics Programme* contains information about Rockbuster's film inventory, customers, payments etc. It is stored in a relational database management system comprised of 15 tables. The *[Rockbuster Data Dictionary](https://github.com/DADmayr/movie-rental-sql-project/files/11066476/2023-01-14_Data.dictionary.pdf)* contains the dataset's entity relationship diagramme as well as an overview of all tables in the dataset. The data was analysed using SQL. This repository makes a selection of SQL queries available that were written to analyse the data.

## The Results of the Analysis
The analysis concluded with the following recommendations: 
1. Data on revenue distribution over time suggest that there are several gaps of ca. 2 weeks with no revenue at all. It is highly recommended to check whether there are gaps in the data. If there aren’t, Rockbuster needs to look into other explanations, e.g. whether it ran special offer campaigns when there was revenue or whether competitors made substantial revenues during times when Rockbuster didn’t.
2. Distribution of revenue across ratings and categories does not suggest Rockbuster should focus on any movie ratings or categories in particular except for “Thriller” which does not appear to be profitable.
3. As the top 10 countries with the highest number of customers and the top 10 countries with the highest revenue are identical, Rockbuster should focus its launch campaign on these countries. 
4. It should however craft targeted launch campaigns for each market. This not only, but specifically applies to India. The country’s large population offers immense potential which currently does not seem to be fully exploited as no customer from India is among Rockbusters top 5 customers with highest lifetime value. 
5. If Rockbuster wants to narrow the focus of its launch campaign(s) further down, it could concentrate on the four countries with a revenue >3.000 US$: India, China, United States, and Japan.
6. If it is looking for guinea pigs on which to test its campaing before launch, it could try targetting the top 5 customers with the highest lifetime value as they’re distributed across 5 of the top 10 countries.

Visualisations supporting these recommendations are available [on my tableau account](https://public.tableau.com/app/profile/daniela.dietmayr/viz/Movierentalanalysis/Customerlocationandrevenuepercountry) as well as in the [PowerPoint presentation prepared for the BI department](https://github.com/DADmayr/movie-rental-sql-project/files/11066488/2023-01-17_Presenting.SQL.Results.pdf).

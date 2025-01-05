# UK TOURISM
![](https://images.pexels.com/photos/672532/pexels-photo-672532.jpeg)

Source: Pexels

Tourism is a crucial part of the global economy, generating significant revenue and creating employment opportunities. VisitBritain Director Patricia Yates said: “Tourism is one of the UK's most valuable export industries. It is also a fiercely competitive global industry and these results not only demonstrate Britain’s continued ability to compete internationally for visitors, they are testament to tourism’s importance as a driver of economic growth.

This project aims to use the UK dataset from UK goverment to analyze the tourism situation in the UK over a 5-year period from 2018 to 2023, including the number of visitors, total revenue, average length of stay, etc. Through this analysis, readers can gain a comprehensive overview of the tourism industry and identify key areas for potential development and growth.

## Dataset

**Source**: Public dataset from UK Goverment website (https://www.ons.gov.uk/peoplepopulationandcommunity/leisureandtourism/datasets/travelpac)

**Description:**

This dataset contains 150,117 observations for a UK residents and Overseas residents. The data was collected from 2018 to 2023 through each quaters.

**Structure:**

- Year: The year of the interview is recorded as a four-digit number.
- Quarter: The four quarters of the calendar year are recorded as a single digit.
- UKOS: Where contact lives i.e. either a UK or an overseas resident
- Mode: The main method of travel is recorded as either air, sea or tunnel.
- Purpose of visit: A single main purpose of visit is recorded for all contacts.
- Package: This identifies whether the contact travelled as part of an inclusive tour package or travelled independently.
- Sex: Sex, or gender, is recorded for all contacts.
- Age: The age group of the contact is asked and recorded for all contacts.
- Duration: The length of stay of the visit is recorded in nights. This is only available for overseas residents’ departures and UK residents’ arrivals.
- Country: Place of residence for overseas residents or of visits for UK residents.
- Visits : A visit is defined as a complete round trip. For a UK resident, it represents a departure from and a return to the UK. For an overseas resident, it represents an arrival in and a departure from the UK. Those who came to the UK or went abroad on more than one occasion are counted on each visit they made.
- Nights: Nights relates to the total number of nights spent whilst on a visit.
- Spend: Spend shows the total expenditure made abroad (for UK residents) or in the UK (for overseas residents) during the visit. 

## Data exploration
  
### Exploratory Data Analysis (EDA)

![image](https://github.com/user-attachments/assets/b79163a7-1108-4ad6-ae67-e8bfbb44d4b3)

![image](https://github.com/user-attachments/assets/63581276-0594-49dd-894f-a019abf9d42c)

Over a period of 5 years (from 2018 to 2023), the total number of inbound and outbound trips from the UK amounts to 529.32 million trips. The number of inbound trips to the UK from foreign tourists is approximately 161.78 million, while the number of UK residents traveling outbound is double that of inbound tourists, at 367.55 million trips. The high demand for travel among UK residents is clearly evident in the line graph depicting the number of trips by both overseas and UK residents over each year

The graphs provide information about the number of round trips made by overseas residents traveling to the UK and UK residents traveling to other countries over a span of 6 years from 2018 to 2023. 2018 and 2019 stand out as the two years with the highest number of visits, with 91 million and 93 million visits respectively.

Clearly, the visits of UK residents to other countries were higher and more than 2 times those of overseas residents. In 2019, the number increased slightly and reached a peak at 93 million visits. However, in the next two years (2020 and 2021), due to the effects of the Covid-19 pandemic and shutdown policies, there was a dramatic decrease for both groups (UK residents dropped from 93 million to 14 million, and overseas residents fell from 41 million to 7 million in 2020). After Covid-19, the situation changed. By 2023, the number of visits increased sharply and nearly matched the number of visits in 2019.

From January to March is a period when people travel less compared to other times of the year. By 2020, the number of travelers was only recorded in the first three months. After March 2020, everyone had to adhere to social distancing measures, so travel occurrences were not documented. In 2021, the situation improved, and the number of travelers slightly increased in the last six months of the year. In 2022 and 2023, the numbers increased rapidly and significantly. Similar to previous years, the majority of travelers are still concentrated in the last six months of the year. The number of travelers in the first and second quarters increased quite rapidly, while there were signs of a decrease in the fourth quarter.

![image](https://github.com/user-attachments/assets/360fd3ef-986b-409c-b382-e2c40bf51026)


 ![image](https://github.com/user-attachments/assets/2f549b3a-2e4a-4842-85ae-2359db0caa2e)

The revenue of the tourism industry in the UK is £389.59 billion. The amount includes revenue from inbound tourism at £120.12 billion and from outbound tourism at £269.47 billion.

Looking at the chart on the left, we can see that there are three most common types of transportation: air, tunnel, and boat. It is noticeable that air travel is the preferred choice over other modes of transportation, accounting for about 80% for foreign tourists and 83% for UK residents. The number of trips by boat and by car represents only a small portion (less than or equal to 10%).

In the chart on the right, it illustrates the number of trips by gender and the type of travel service they choose. It is easy to see that the number of male travelers tends to be higher than female travelers (56% for males and 44% for females). Most of them choose independent travel rather than through a third party (travel agent). For males, the proportion choosing independent travel is 46%, while selecting travel through organized tours accounts for only 10%. This also applies similarly to females. Their preference for independent travel is significantly higher compared to non-independent travel, being 5.2 times for females and 4.6 times for males."

![image](https://github.com/user-attachments/assets/1f5f52ed-92fa-4adf-95a0-794f7c36e16d)

The table above shows the number of visits and total spend for both inbound and outbound trips according to different lengths of stay. Most individuals tend to choose stays within 3 specific time ranges: 1-3 nights, 4-13 nights, and 14-27 nights for their trips. The time range where both inbound and outbound travelers spend the most is 4-13 nights, with overseas visitors spending 58.2 billion (28k visits) and UK residents spending 141.3 billion (31k visits). Although the number of visits for both groups does not differ significantly, the total spend varies considerably (2.4 times for 4-13 nights and nearly 3.5 times for 14-27 nights). Additionally, the number of visits from overseas is 1.5 times that of UK residents, yet the total spend of UK residents is only slightly lower than that of overseas visitors by approximately 1 million.

![image](https://github.com/user-attachments/assets/6051cb4e-2c69-404f-adb8-295f1c5113fe)

Inbound visits in 2023 remained below 2018 levels but the number of nights stayed equalled 2018 levels. The number of visits in 2023 was 8.9% down on pre-pandemic levels, while the volume of international visitor nights was higher than 2018. Visitors spent a total of £29.8bn in 2023 (up 13.2% vs 2018 in nominal terms). Visitor spend was higher in 2023 than in 2018, but in real terms fell by 10% compared with 2018 when inflation is taken into account. 

Similarly to inbound, outbound travel from the UK also shows a decreasing trend. The number of outbound visits drecreased from 90.5 million (2018) to 82.5 million (2023). Although the number of nights decreased 856 million nights away from home on a trip in Britain (down 4.9% vs 2018), the spend increased around 10 million (18% vs 2018 in nominal terms).

![image](https://github.com/user-attachments/assets/ebfbf9e2-599d-4924-bd80-5c0f30ccc045)

In general, the reasons for travel for both overseas residents and UK residents are quite similar. The three main reasons for both are: holiday (38.42%), visiting relatives and friends (VFR) (35.31%), and business (15.87%).

With nearly 26,000 selections, VFR is the most chosen reason for travel by overseas residents, followed by holiday (around 24,000), and finally business (around 13,700). For UK residents, holiday is the primary reason for their travels (around 33,600), followed by VFR with 27,000, and business with over 100,000. Additionally, there are other similar reasons for travel on both sides such as miscellaneous and study. Particularly for overseas residents, the UK serves as a transit point for flight connections.

![image](https://github.com/user-attachments/assets/b337e7e7-cff5-41dc-a920-2b04344ef562)

Looking at the two tables above, we can better observe the changes in the number of nights and the amount spent for their trips through the two most chosen reasons in the years 2018 and 2023. For inbound trips, overall, over the 5-year period, all factors show a decreasing trend. The average nights for a holiday trip slightly decreased, leading to a decrease in AVG spend per night and AVG spend per visit. Regarding VFR trips, AVG night per visit and AVG spend per visit also show a decreasing trend, but the average amount spent per night increased (from 76.93 to 88.57). Despite more people coming to the UK to visit relatives than for tourism purposes, the AVG spend per visit for holiday is higher than for VFR and for any purpose.

In contrast to inbound trips, the indicators for outbound trips show an increasing trend. Although the AVG night per visit for VFR is significantly higher than for holiday, the average amount spent per night by UK residents for each trip is 1.8 times higher than for VFR. Consequently, the AVG spend per visit for holiday increased by 1.3 times over 5 years and was 1.6 times higher than for VFR in 2023. Similarly to inbound trips, although the average number of nights for a holiday trip is the lowest, the average amount spent by UK residents is higher than for all other reasons. It is 1.6 times higher than for VFR and nearly 1.2 times higher than for any purpose in 2023.

![image](https://github.com/user-attachments/assets/4175225e-0143-40aa-a438-ae972e065585)

The top inbound market for visits and spend was the USA, which surpassed pre-pandemic visit levels by 14%. Other key markets were France, Germany, the Irish Republic and Spain, but these all remained below 2019 visit levels. In total, visits from Europe accounted for 65% of total inbound visits to the UK.

![image](https://github.com/user-attachments/assets/450a6424-cc5b-4a31-98f8-71a42f0b06ab)

The two tables above display the top 15 countries with the highest number of tourists visiting the UK and the top 15 countries most chosen by UK residents for the years 2018 and 2023.

For inbound travel, the USA is the country with the highest number of visitors to the UK. The number of inbound visits from the USA was 4.6 million in 2018 and 4.9 million in 2023 (an increase of 6.5%). Additionally, European countries account for a significant portion of tourist visits, such as France, Germany, Spain, Italy, etc. However, the majority of visits from European countries have seen significant decreases compared to 2018, with France decreasing by 13.9%, Italy by 23.8%, etc. Furthermore, the number of tourists from Asia has decreased the most, with "Other Asia" decreasing by 40% and notably China decreasing by 60% and dropping out of the top 15 countries with the most visits to the UK in 2023. On the other hand, the number of visitors from some countries to the UK has increased rapidly, such as Australia (10%), Canada (11%), Switzerland (12.5%), and the highest increase being Other Central & South America with 16.7%. Despite the decrease in numbers, Europe remains the market with the highest number of visitors to the UK. Additionally, the market in some South American countries is also a potential market for the future.

Regarding outbound travel, UK residents tend to visit countries close to the UK, specifically European countries, with Spain being the most popular choice. However, similar to inbound travel, the number of UK residents traveling to European countries has seen a significant decrease. Nevertheless, some countries are attracting more UK residents for travel, such as Portugal (increasing by 15.2%), Greece (37.9%), and the most significant increase is seen in Turkey (82.4%). Additionally, countries from Asia and Africa are gradually attracting more UK visitors, such as India (26.7%) and Other Africa (7.7%).

## Conclusion

Based on the data provided, the following observations can be made about the tourism industry in the UK:
- The peak tourist season in the UK is typically from July to September each year, and air travel is the most preferred mode of transportation for tourism.
- The average duration of a trip ranges from 3 to 13 days, depending on the purpose of the trip.
- The UK attracts a significant number of tourists from European countries, and in recent years, there has been a rapid increase in the number of tourists from Asian, African, and American countries.
- Following the Covid-19 pandemic, although the tourism industry has shown signs of recovery, it has not yet reached the levels seen before the outbreak of the disease (total visits have decreased).
- Holiday and visiting relatives and friends (VFR) are the two most popular reasons for travel, with holiday trips especially generating higher revenue compared to other reasons.





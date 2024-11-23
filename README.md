# UK TOURISM
![](https://images.pexels.com/photos/672532/pexels-photo-672532.jpeg)

Source: Pexels

Tourism is a crucial part of the global economy, generating significant revenue and creating employment opportunities. VisitBritain Director Patricia Yates said: “Tourism is one of the UK's most valuable export industries. It is also a fiercely competitive global industry and these results not only demonstrate Britain’s continued ability to compete internationally for visitors, they are testament to tourism’s importance as a driver of economic growth.

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

![image](https://github.com/user-attachments/assets/63581276-0594-49dd-894f-a019abf9d42c)


The graphs provide information about the number of round trips made by overseas residents traveling to the UK and UK residents traveling to other countries over a span of 6 years from 2018 to 2023. 2018 and 2019 stand out as the two years with the highest number of visits, with 91 million and 93 million visits respectively.

Clearly, the visits of UK residents to other countries were higher and more than 2 times those of overseas residents. In 2019, the number increased slightly and reached a peak at 93 million visits. However, in the next two years (2020 and 2021), due to the effects of the Covid-19 pandemic and shutdown policies, there was a dramatic decrease for both groups (UK residents dropped from 93 million to 14 million, and overseas residents fell from 41 million to 7 million in 2020). After Covid-19, the situation changed. By 2023, the number of visits increased sharply and nearly matched the number of visits in 2019.

From January to March is a period when people travel less compared to other times of the year. By 2020, the number of travelers was only recorded in the first three months. After March 2020, everyone had to adhere to social distancing measures, so travel occurrences were not documented. In 2021, the situation improved, and the number of travelers slightly increased in the last six months of the year. In 2022 and 2023, the numbers increased rapidly and significantly. Similar to previous years, the majority of travelers are still concentrated in the last six months of the year. The number of travelers in the first and second quarters increased quite rapidly, while there were signs of a decrease in the fourth quarter.

 
![image](https://github.com/user-attachments/assets/f3df5368-2b71-4a58-b612-eced552c7124)

Có 3 loại di chuyển phổ biến nhất là air, tunnel và boat. Có thể thấy được việc di chuyển bằng máy bay được lựa chọn nhiều hơn hẳn những loại phương tiện di chuyển khác, chiếm khoảng 80% đối với du khách nước ngoài và 83% đối với UK residents. Số lượng đi du lịch bằng thuyền và bằng xe chỉ chiếm 1 phần nhỏ (nhỏ hơn hoặc bằng 10%).

số lượng nam giới có xu hướng đi du lịch nhiều hơn là nữ giới (56% với nam và 44% với nữ). 

![image](https://github.com/user-attachments/assets/ebfbf9e2-599d-4924-bd80-5c0f30ccc045)

Top những lí do họ chọn để đi đến nơi khác bao gồm:... Trong đó VFR chiếm số lượng nhiều nhất vs 34.62% ở oversea residents và ... ở UK residents. Đứng thứ 2 là holiday với 31.94%

Age:
![image](https://github.com/user-attachments/assets/ea4022b7-461f-4c0c-86d2-019530cf4e40)


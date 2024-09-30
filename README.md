# Aviation Business Venture
![image](https://github.com/user-attachments/assets/df7993c9-481b-45fa-890f-a74188b2be62)

With the interest that has emerged recently from our company to expand and diversify its portfolio particularly in the Aviation Industry. I, Stephen Mulingwa, as the senior Data analyst of the Company, analyzed the aviation accident data from the National Transportation Safety Board, covering civil aviation accidents from 1948 to 2022. Hence, through this project I will provide you with the actionable insights to guide the company in selecting the lowest-risk aircrafts for commercial and private enterprises. This project seeks to minimize operational risks and enhance decision-making in the company’s venture into the aviation industry by assessing aircraft safety through historical accident trends. I have used data-driven analysis to identify aircraft makes and models with the least incidence of accidents or incidents, ultimately delivering key recommendations to support safe and strategic aircraft purchases.

### Objectives
The objectives for this project aviation business venture are:
* To assess Aviation Accident Risk: I will analyze historical aviation accident data to identify aircraft models with the lowest incidence of accidents or incidents, ensuring the selection of the safest options for the company’s venture.
* To minimize Operational Risk: I will provide actionable insights that will guide the company in minimizing operational risks as it expands into the aviation industry by focusing on safety metrics.
* I will offer Strategic Decisions: I will deliver data-driven recommendations that will assist the head of the aviation division in making informed decisions regarding aircraft purchases for both commercial and private operations.

## Business Understanding
The company is expanding into the aviation industry and aims to make informed decisions on purchasing and operating aircraft for commercial and private use. The primary stakeholder is the Head of the Aviation Division, who oversees the selection and operation of aircraft for commercial and private ventures. The key business questions to address in this project are:

* Which aircraft Makes and Models have the lowest risk of accidents or incidents?
This question focuses on identifying the safest aircraft based on historical data, ensuring the company invests in Makes and models with proven safety records, and avoiding unsafe ones.

* What major factors contribute to aviation accidents, and how can the company mitigate these risks?
By understanding the common causes of accidents, the company can make informed choices about aircraft maintenance, pilot training, and operational protocols.

* How has the frequency of accidents been over the years?
This question seeks to uncover patterns and trends in the aviation industry and determine whether it is a safe venture.

The answers to these key questions will enable the company to make data-driven decisions in the new aviation venture, reducing risk and ensuring safe and strategic aircraft purchases.


## Data Understanding and Analysis
### Source of data
The dataset for this analysis comes from the National Transportation Safety Board (NTSB) and contains information on aviation accidents and selected incidents involving civil aviation in the United States and international waters. The data spans from 1948 to 2022 and includes various details related to accident occurrences, the purpose of the flight, the aircraft involved, and weather conditions at the time of the incidents.

### Description of Data
The dataset contains 90,348 records with 31 columns, covering various aspects of aviation accidents, including:
* Event Date: The date when the aviation accident or incident occurred.
* Location: The geographic location where the incident took place.
* Aircraft Make and Model: The manufacturer and specific model of the aircraft involved in the accident.
* Aircraft Category: The type or category of the aircraft (e.g., commercial, private).
* Aircraft Damage: Details about the severity of the aircraft damage (e.g., Destroyed, Substantial, Minor, Unknown).
* Injury Severity: The injuries sustained (e.g., fatal, non-fatal, incident).
* Weather Conditions: Information on the weather conditions at the time of the incident.
* Probable Cause: The identified or suspected cause(s) of the accident.
* Purpose of flight (e.g., personal, instructional, business)

### Table Plot
![Notorious Makes and Models based on Accidents (1)](https://github.com/user-attachments/assets/6300b24e-12cd-4e9d-879d-3b5bdb35bd4b)

`From the table plot looking at the make and Models, Cessna and Piper Makes have high frequencies of accidents which could be due to malfunctions of the airplanes. Thus, as the Company purchases new airplanes it should avoid purchasing this Makes and go for makes and Models with low accident levels, such as Air Tractor, Bell, and Grumman American.`

### Bar Graph
![image](https://github.com/user-attachments/assets/022b4cb5-d40b-4fa2-a47e-e8035440c26e)

`The above bar graph shows that Personal, Instructional, and Unknown are the leading causes of accidents.
Thus, the company must restrict its airplane offering and opt for low-use flights with minimal accidents.`

### Time-series Plot
![image](https://github.com/user-attachments/assets/2073411f-3f28-42c7-8e65-ea2ccefa133d)

`As seen in the time series graph the number of accidents has been on the decline over the years hence air travel is becoming more and more safe means of transport and good venture for our company.`

### Bubble Plot
![image](https://github.com/user-attachments/assets/45291ae7-95f7-452b-9885-9778ab15ad52)

`From the bubble plot most of accidents leading to fatalities occur during takeoff, landing, cruise, maneuvering, and approach. Hence, this necessitate continuous training of our company’s pilots to ensure safety of the airplanes thus avoiding accidents.`

## Summary

In summary, the findings reveal that accidents leading to fatalities are most frequent during critical flight phases, such as takeoff, landing, and approach. Continuous and enhanced pilot training will be essential to mitigate these risks. Furthermore, aircraft involved in personal and instructional flights are more prone to accidents, suggesting the company should prioritize business, ferry, and aerial observation flights, which have lower accident rates.

The analysis also highlighted specific aircraft makes and models, such as Cessna and Piper, which have higher accident frequencies, possibly due to mechanical issues. The company should avoid these makes and instead focus on safer alternatives like Air Tractor, Bell, and Grumman American.

Lastly, the trend of declining accidents over the years and the safe nature of air travel presents a promising opportunity for the company to expand into the aviation industry. The company can successfully minimize risks and thrive in this new venture by focusing on safer aircraft models, implementing rigorous training programs, and targeting low-risk flight operations.

## References

Tableau Visualizations: [Tableau](https://public.tableau.com/app/profile/stephen.mulingwa8804/viz/AviationDataVisualization_17276866896030/AviationDataVisualization?publish=yes)

Slides Presentation Link: [Presentation.pdf](https://docs.google.com/presentation/d/1p9Vrm6vmiBRkkRiR2_G9xcrYpl8ryqaYFOiQaIxSpq4/edit#slide=id.g1e122c60b65_0_13)

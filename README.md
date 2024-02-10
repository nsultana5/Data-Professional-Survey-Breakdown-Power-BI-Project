# Data-Professional-Survey-Breakdown-Power-BI-Project

# The Survey includes inquiries on the following aspects:
1. **Career Transition:**
  -Did you transition into a Data-related career?
2. **Annual Salary:**
 -What is your current annual salary?
3. **Satisfiction Levels:**
 -Please rate your satisfiction levels on the following aspects:
  - Salary
  - Work/Life balance
  - Management
  - Co-Workers
  - Upward mobility
  - Opportunity to learn
4. **Difficulty in Entering Data Field:**
    -How challenging do you find breaking into the data field?
5. **Preferred Progrmming Language:**
    -What is your preferred programming language among the options (Python, R, SQL, Java, JavaScript, and others)?
6. **Current Job Title:**
    -Which Job title best characterizes your current role?

# Data Cleaning in Power BI
The Survey results were exported into Power BI ,  and the data was stored in excel file . Specifically , for the question "Which title best describes your current role, " there were seven predefined options, including one for 'other (please specify)."
## Handling 'Other' Titles
The inclusion of the "other" option led to a diverse range of titles,making analysis and visualization challenging. To address this, the follwoing steps were taken:

1. **Data Separation:**
   -The response marked as "other" were separated from the main dataset.
2. **Splitting Columns:**
 -The 'split column' function in Power BI was employed to break down the "other" responses into distinct titles.
3. **Custom Delimiter:**
   -A custom delimiter was specified during the split operation to effectively categorized and organized the varied titles.
By implementing these steps, the data was prepared for meaningful analysis and visualization, ensuring a clearer representation of the diverse job titles within the survey responses.

![image](https://github.com/nsultana5/Data-Professional-Survey-Breakdown-Power-BI-Project/assets/98044004/9336e322-fd5f-4a01-a62b-1f74909a0ada)


This was repeated for the 'What is your favorite programming language' as well specifying colon as the delimiter.
  
![image](https://github.com/nsultana5/Data-Professional-Survey-Breakdown-Power-BI-Project/assets/98044004/2819aea8-9227-4480-a7bc-d171e180671a)


In order to determine the average salary, the data contained a 'Current Yearly Salary' field provided as a range (e.g., 60k — 70k). To address this, three duplicate columns were created: the first for the lowest values of the range, the second for the highest value of the range, and the third to calculate the average. This approach enabled a more accurate representation of salary data for subsequent analysis and visualization.

![image](https://github.com/nsultana5/Data-Professional-Survey-Breakdown-Power-BI-Project/assets/98044004/aa82ddb3-6087-4854-b696-e037005fff98)

# Visualization using Power BI
![image](https://github.com/nsultana5/Data-Professional-Survey-Breakdown-Power-BI-Project/assets/98044004/92437439-627c-4222-8383-f01ed1d74073)

630 people took the survey with the average age of the survey taker being 29.87.

![image](https://github.com/nsultana5/Data-Professional-Survey-Breakdown-Power-BI-Project/assets/98044004/8229cf15-5994-46fd-a17d-1c962074ac4b)

The survey was taken by 630 individuals from 78 different countries around the world, with 41% of the participants being from the United States and 11% being from India. The average of our survey takers is 30 years, with a gender split of 74 % Male and 26% Female. A bachelors degree is the most popular among our professionals with 56% holding it as their highest level of education and an impressive 33% holding a Masters degree.

![image](https://github.com/nsultana5/Data-Professional-Survey-Breakdown-Power-BI-Project/assets/98044004/52ed869b-c468-496a-b11c-4173f616c6ae)

Most of the  survey taker prefer Python as a programming language over all other languages , with R being the second favourite with 101 selections.

![image](https://github.com/nsultana5/Data-Professional-Survey-Breakdown-Power-BI-Project/assets/98044004/dfe33b7c-fcdc-45c1-bb5a-ed9b47a38383)

Data scientist are the best earner according to the survey, followed by data engineer.

![image](https://github.com/nsultana5/Data-Professional-Survey-Breakdown-Power-BI-Project/assets/98044004/6ec898c2-e888-4de9-bed1-8923bd9f9e17)

According to the survey, 11.11% argue it was difficult to break into Data while 16.03% argue it was neither easy nor difficult.

![image](https://github.com/nsultana5/Data-Professional-Survey-Breakdown-Power-BI-Project/assets/98044004/85ead2a6-e1e9-41d5-917c-541eba8ce226)

Shows how survey takes are happy with work life balance.

![image](https://github.com/nsultana5/Data-Professional-Survey-Breakdown-Power-BI-Project/assets/98044004/955ef8f6-1de4-4fdc-b4fd-112b7a9a1dfc)

Show the score of how happy people are with the salary with the maximum score being 10 and minimum being 0.

# Dashboard

![image](https://github.com/nsultana5/Data-Professional-Survey-Breakdown-Power-BI-Project/assets/98044004/c55acae1-64ef-4ca3-a544-935840f4f141)

















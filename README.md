 ML-EDA
Dataset Summary
This dataset captures users' app usage patterns, demographics, preferences, and challenges related to dating applications. It includes information on users' primary and secondary app choices, frequency of use, satisfaction levels, and desired features.

| Column Name                   | Data Type  | Description |
|--------------------------------|-----------|-------------|
| User_ID                   | int       | Unique identifier for each user |
| Age                        | int       | User's age |
| Gender                     | category  | User's gender identity |
| Location                   | category  | User's city of residence |
| Education                  | category  | Highest completed education level |
| Occupation                 | category  | Job role or employment status |
| Primary_App                | category  | User's preferred dating app |
| Secondary_Apps             | category  | Other dating apps the user engages with |
| Usage_Frequency            | category  | Frequency of dating app usage (e.g., daily, weekly) |
| Daily_Usage_Time           | category  | Time spent on apps in hours/minutes format |
| Reason_for_Using           | category  | User's motivation for using dating apps (e.g., serious relationship, casual dating) |
| Satisfaction               | category  | User satisfaction rating (e.g., scale of 1-5) |
| Challenges                 | category  | Common issues faced on dating apps (e.g., privacy concerns, time-wasting) |
| Desired_Features           | category  | Features users want in dating apps |
| Preferred_Communication    | category  | Most preferred communication method (e.g., text, voice notes, video calls) |
| Partner_Priorities        | category  | Factors prioritized in a partner (e.g., values > personality > appearance) |
| Daily_Usage_Time_in_Minutes| int       | Numeric representation of daily usage time in minutes |

Data Cleaning Process
- Handled Missing Values: Used mode imputation for balanced data distribution, preventing bias from rare values.  
- Ensured Data Type Consistency: Converted object-type columns to categorical, including the "Satisfaction" column.  
- Checked for Duplicates: Verified dataset integrity and found no duplicate entries.  
- Standardized Gender Categories: Ensured uniformity in gender labels to avoid inconsistencies.

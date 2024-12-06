# apstat-influenza-project
This is a small project about influenza (the flu) that I completed for my statistics class. The main question being answered is "Why do influenza symptoms vary?" I surveyed a total of ~90 participants and gathered information about various factors that may contribute to experiencing more severe flu symptoms. For this project, however, I focused on one's vaccination status, sleep, and mean symptom severity (an average of the severity of each flu-like symptom)

# Sampling Procedure
Please note that the sampling procedure I used is really scuffed and heavily relied on self-reports from those who participated in my survey.

My population for this project was my school. To conduct the survey, I separated the school into stratas. I then made each classroom in each stranum its own cluster.
From each stranum, I randomly selected n number of clusters where n is the number of grades in the stranum (i.e. if a stranum included the 7th and 8th grade, I would randomly select 2 clusters. After I selected which classes I would survey, I decided to randomly select which grade from each class would be surveyed. This way, each cluster would have a roughly homogenous group of participants. Depending on your population, these processes may vary and in some cases be omitted; It's only crucial that each cluster behaves as a representative for a chunk of the population.

The survey was given to everyone on paper. The questions were more of a self-evaluation where they listed their flu-like symptoms they have experienced within the last month and rate the severeness of it on a scale of 1-10. After I received the results, I compiled all of the data in a Excel spreadsheet.

# Results
**A: Is there a significant difference between the symptom severity of those who are and are not vaccinated against the influenza vaccine?**
The mean symptom severity distribution of Group Alpha (vaccinated) and Group Beta (unvaccinated) was right-skewed. This can be solved by transforming the data. In my case, I took the nth root of the data. Although a Square Root and a Cube Root transformation would both create a more normal distribution, I decided to ultimately use a Square Root Transformation to avoid overtransforming the data.

![Screenshot 2024-12-06 at 12-48-47 AP Statistics Semester Project Report pdf](https://github.com/user-attachments/assets/14a5681e-6940-4277-8087-64e7f8eedec5)

Now that our mean severity of both Group Alpha and Beta follows an approximately normal distribution, we can conduct a 2-Sample t-Test.

![Screenshot 2024-12-06 at 12-54-20 AP Statistics Semester Project Report pdf](https://github.com/user-attachments/assets/ab7248b0-65fd-45d8-af84-71939a3f5025)

Since 0.05 < 0.5436, we fail to reject the null hypothesis. *There is not enough statistical evidence to prove that there is a difference between Group Alpha and Group Beta's mean symptom severities.*

**B: Is there significant evidence that getting less sleep can lead to more severe flu symptoms?**
I was very surprised to see that the distribution of sleep was normal. I conducted a simple 1-Sample t-Test.

![Screenshot 2024-12-06 at 12-59-21 AP Statistics Semester Project Report pdf](https://github.com/user-attachments/assets/17412cb2-3c79-43f3-918a-3a963f5208da)

Since 0.05 < 0.10155, we fail to reject the null hypothesis. *There is not enough statistical evidence to prove that sleeping less can lead to more severe flu symptoms.*

# Conclusions and Closing Remarks
There is not enough statistical evidence to prove A nor B true. I believe that the results from Question B are still noteworthy, though. 0.05 and 0.10155 are relatively close to one another. Even though it isn't statistically proven, it should still be remarkable regardless.

This project was just something I put together for my class, but I found every step of the process interesting. In the future, I hope to do something similar but with a must more efficient and practical sampling method. Since this was just for a high school class, relying on self-reports is alright but it isn't practical. I beleive that a redesign of my experiment would lead to more accurate results.

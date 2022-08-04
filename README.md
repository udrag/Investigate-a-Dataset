# Investigate-a-Dataset

Analysis of a dataset that has been collected from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up
for their appointment. A number of characteristics about the patient are included in each row:

• ‘ScheduledDay’ tells us on what day the patient set up their appointment.
• ‘Neighborhood’ indicates the location of the hospital.
• ‘Scholarship’ indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.

## Conclusions 

At this stage, we can split the conclusions into two groups based on:

1. How do the two patient characteristics (scholarship and received SMS) compare between the patients who received each of them and those who didn't?
2. Determinant characteristics at the neighbourhood clinics based on four levels of attendance; 

In the first part, the results of the data comparison between the patients who received an SMS and attended their appointments and the ones who didn't show us that receiving an SMS is not necessarily a determinant factor to increase the attendance rate. Almost 30% of patients who received an SMS did miss their appointment whilst almost 20% of patients who did not receive an SMS missed their appointment. 

Equally, having a scholarship did not prove to be a determinant factor as well. Around 25% of patients with a scholarship will miss an appointment whilst 20% of the patients without a scholarship will miss an appointment.

On the other hand, in the second part of this analysis, the data was grouped slightly different. We saw the comparison between the neighbourhoods with a lower 25% attendance rate and the ones with a higher 75% one. This comparison revealed the following characteristics for the patients of the latter category:

- are older by 9%;
- have been awarded fewer scholarships by 45%;
- have a lower rate of hypertension by 15%;
- are less affected by diabetes by 11%;
- are less affected by alcoholism by almost 40%;
- no significant difference in handicap;
- no significant difference in the number of SMS received;
- have booked the appointment in advance by 11% fewer days.

At this point, compiling the information from both questions we can sketch the conclusions around the points:

- Age is not a determinant factor related to attendance rate;
- Scholarship is an important factor to influence the attendance rate: those with fewer will attend more;
- Hypertension will relatively predict who will generally attend an appointment, however, based on the patient's neighbourhood, some factors will influence patients to miss more of their appointments.
- Diabetes is a relatively important predictor of a patient attending the appointment, however, this is dependent on other factors related to each particular neighbourhood;
- Alcoholism is not an overall predictor of attendance, however, based on particular neighbourhoods, patients that are not affected by alcoholism will attend more;
- Handicap is not a determinant factor related to attendance rate;
- SMS received are not of extreme importance in predicting the attendance rate;
- Booking the appointment in advance is an important factor that predicts the attendance rate by a high margin.

## Limitations

In addition, it is important to mention, that the conclusions related to some of the characteristics could have been more accurate with an additional column that shows if the appointment has been rescheduled or cancelled. Also, attended information could further be split into two: 'attended with no reschedule' and 'attended following x reschedules'.

Also, we saw limitations related to the reason behind an SMS being sent to a specific patient. This would have helped us when we were interpreting the data of patients who received an SMS but did not attend the appointment compared with those who also received the SMS, but attended the appointment. For example, if the clinics will send an SMS because a patient has a history of missing appointments, then a new group is delineated and namely patients with a tendency to miss appointments. Around a 70% attendance rate would be considered a great success. 

Similarly to the above, previous history of attendance would have been useful to better understand the impact of scholarships on the patient's attendance rate. Since this information is missing, we can't tell for sure if missing an appointment was due to a financial issue that the patient had, which would require working more hours per day, or not.

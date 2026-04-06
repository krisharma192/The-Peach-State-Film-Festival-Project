# Group Information
Group A-5

Group Leader - Krish Sharma

Conceptual Modeler - Winston Chung

Database Designer - Nila Karunakaran

Data Wrangler - Malak Hamid

SQL Writer - Jude Zekra

# Case Description 
The Peach State Film Festival (PSFF), a week-long film festival held at multiple cinemas across Atlanta, is planning and implementing a database to handle the main aspects of their business, such as the films submitted for the festival, the timing of film screenings, customer reservations, cinema and auditoriums, as well as assigning shifts to the many different volunteers. The business rules for the film submissions and screenings include: 
- a film can be in only one category, (un-identifying 1 to many relationship)
- a film is submitted by one submitter, (1:m)
- there are a primary and assistant director for each film, (2PK’s of Director Cat)
- in each screening there is only one film in one screening room, and (1:M identifying)
- no two screenings can be scheduled in the same screening room at the same date and time. 
In addition, the business rules for the paired films, customer reservations and for the shifts assigned to the many different volunteers are also provided. (Ven to Shift 1:m identifying, shift to volunteer assignment (1:M identifying).

New features (extensions) were added to improve the system in general. Some features that were added include restaurants and menus for the different venues, and director awards. We also added VIP packages for the customers. The data in the database is becoming more realistic, moving away from the simplicity of just movies and towards the actual festival experience, including food for audience members and other director accolades in addition to director awards.

# Data Model 
## Explanation of Data Model
<img width="1465" height="1050" alt="Peach State_Updated" src="https://github.com/user-attachments/assets/83305e97-01b4-4c19-ad13-7b03ec472f3a" />


# Data Dictionary
<img width="732" height="581" alt="Screenshot 2026-04-06 at 3 58 57 PM" src="https://github.com/user-attachments/assets/3287b5e0-3f5e-47c2-a067-e08e06718255" />
<img width="725" height="791" alt="Screenshot 2026-04-06 at 3 59 26 PM" src="https://github.com/user-attachments/assets/8c8dea14-0fe3-4051-bcbe-b6ffd112d605" />
<img width="732" height="580" alt="Screenshot 2026-04-06 at 3 59 50 PM" src="https://github.com/user-attachments/assets/a0f1432e-c232-477f-8b0c-b509a1bca1f6" />
<img width="729" height="674" alt="Screenshot 2026-04-06 at 4 00 11 PM" src="https://github.com/user-attachments/assets/150877f2-fcac-4d11-a527-a3b66ee610e1" />
<img width="731" height="666" alt="Screenshot 2026-04-06 at 4 00 32 PM" src="https://github.com/user-attachments/assets/4399d9e0-c045-4d93-8335-aeb3b2938034" />
<img width="728" height="553" alt="Screenshot 2026-04-06 at 4 00 57 PM" src="https://github.com/user-attachments/assets/988d95b1-f7e1-4bf5-8638-99dcb2014df3" />
<img width="728" height="687" alt="Screenshot 2026-04-06 at 4 01 30 PM" src="https://github.com/user-attachments/assets/0b1e2ab9-0b4d-44e2-b3ca-6e969a967f08" />
<img width="730" height="404" alt="Screenshot 2026-04-06 at 4 01 51 PM" src="https://github.com/user-attachments/assets/01576264-bc16-4651-b1ce-f4883b7789cd" />







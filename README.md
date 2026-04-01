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
<img width="1465" height="998" alt="Peach_State_Finalized" src="https://github.com/user-attachments/assets/684e1228-9ad2-4864-bd4b-18efc9178400" />

# Data Dictionary
<img width="813" height="635" alt="Screenshot 2026-04-01 at 2 30 44 PM" src="https://github.com/user-attachments/assets/c45cfdb0-2e32-4773-9f1d-91222a0c4929" />
<img width="812" height="859" alt="Screenshot 2026-04-01 at 2 31 46 PM" src="https://github.com/user-attachments/assets/e94db0ce-4807-4214-8536-7e3a18766fcc" />
<img width="817" height="654" alt="Screenshot 2026-04-01 at 2 32 29 PM" src="https://github.com/user-attachments/assets/3699668c-9eaa-4a9a-8711-b0c93070b162" />
<img width="815" height="754" alt="Screenshot 2026-04-01 at 2 33 08 PM" src="https://github.com/user-attachments/assets/3d3906ef-dbce-4aed-aea7-e1fbe747a0e3" />
<img width="817" height="732" alt="Screenshot 2026-04-01 at 2 33 48 PM" src="https://github.com/user-attachments/assets/bbde784e-9766-41e1-9184-65b908bd950d" />
<img width="710" height="798" alt="Screenshot 2026-04-01 at 2 34 33 PM" src="https://github.com/user-attachments/assets/222376cc-5f05-428a-93c6-afc9de2f123f" />
<img width="726" height="768" alt="Screenshot 2026-04-01 at 2 35 17 PM" src="https://github.com/user-attachments/assets/0f3d2129-d0f5-4d41-b993-575bea0581e6" />



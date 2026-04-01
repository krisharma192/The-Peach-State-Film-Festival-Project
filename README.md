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

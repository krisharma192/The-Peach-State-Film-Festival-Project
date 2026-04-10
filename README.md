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

# Queries 
1. Query 1 lists the film ID, country of origin, and run time of films whose directors have won the award "Best Leadership Award." Ordered by count in descending order.
<img width="828" height="595" alt="image" src="https://github.com/user-attachments/assets/0da58ca9-ae71-4dc2-a763-bab2cf022873" />

Query 1 allows the PSFF to gain insight into trends of award-winning directors and the choices do they make in film length. If longer runtimes correlate with winning the most prestigious awards, this finding could help directors in choosing future film lengths. This is especially true in the modern world, where attention spans are constantly declining. 

2. Query 2 lists the volunteer role, first name, last name, and training requirements for all volunteers assigned as either an Usher or Ticketing volunteer. 

<img width="838" height="633" alt="image" src="https://github.com/user-attachments/assets/68c6885f-ac7f-4b09-a179-6a04ec1ee4ff" />

Query 2 allows managers to identify which volunteers are staffing two of the most critical guest-facing roles at the festival (ushers and ticketing). These volunteers tend to be most in contact with the attendees, making it essential for managers to know what kind of training they have and to keep up with them to ensure customer experience is excellent.

3. Query 3 lists the menu ID, allergens, and nutritional information for each orginal/standard menu item side by side its counterpart menu item. This query specifically looks at menus containing gluten, ordered by menu ID.

<img width="1165" height="500" alt="image" src="https://github.com/user-attachments/assets/53164435-7f37-4593-9826-fe01b588e569" />

Query 3 allows managers to directly compare allergens and the nutritional profile of gluten-containing menu items against their matched alternatives. Accommodating guests with dietary restrictions like gluten is essential for guest safety and satisfaction. This view allows managers to see if their offerings are sufficient or whether they need to improve their offerings and make smarter menu planning choices.

4. This query lists the screening room ID, venue name, seating capacity, close capition availability, and ADA accessibility status for all screening rooms that do not offer ADA accessibility, ordered by seating capacity.

<img width="858" height="623" alt="image" src="https://github.com/user-attachments/assets/9fa82176-9903-4c97-8356-bee7c7e37af4" />

This allows the managers at the PSFF to identify which screening rooms are not ADA-compliant. This is critical in complying with legal standards whilst also ensuring all attendees are appropriately accommodated. It also helps identify where to begin making upgrades to screening rooms.

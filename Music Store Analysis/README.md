# Music Store Analysis
## Project Objective
The Music Store is an E-commerce music selling company. They wants to generate some interesting insights for 2023 so that the owner of Music Store can understand their customers, employees and sales patterns.

## Database and Tools
- Postgre SQL
- PgAdmin4

## Schema-Music Store Database
-![image.alt](https://github.com/Amit-Y20/SQL-Projects/blob/caa1b1f0731c9113dbe6cbaf70eadbee443a3a4c/Music%20Store%20Analysis/MusicDatabaseSchema.png)

## Database Used

## Questions(KPI)
### Question Set 1 - Easy
1. Who is the senior most employee based on job title?
2. Which countries have the most Invoices?
3. What are top 3 values of total invoice?
4. Which city has the best customers? We would like to throw a promotional Music 
Festival in the city we made the most money. Write a query that returns one city that 
has the highest sum of invoice totals. Return both the city name & sum of all invoice 
totals
5. Who is the best customer? The customer who has spent the most money will be 
declared the best customer. Write a query that returns the person who has spent the 
most money
### Question Set 2 – Moderate
1. Write query to return the email, first name, last name, & Genre of all Rock Music 
listeners. Return your list ordered alphabetically by email starting with A
2. Let's invite the artists who have written the most rock music in our dataset. Write a 
query that returns the Artist name and total track count of the top 10 rock bands
3. Return all the track names that have a song length longer than the average song length. 
Return the Name and Milliseconds for each track. Order by the song length with the 
longest songs listed first
### Question Set 3 – Advance
1. Find how much amount spent by each customer on artists? Write a query to return
customer name, artist name and total spent
2. We want to find out the most popular music Genre for each country. We determine the 
most popular genre as the genre with the highest amount of purchases. Write a query 
that returns each country along with the top Genre. For countries where the maximum 
number of purchases is shared return all Genres
3. Write a query that determines the customer that has spent the most on music for each 
country. Write a query that returns the country along with the top customer and how
much they spent. For countries where the top amount spent is shared, provide all 
customers who spent this amount

## Project Insights
### Easy
1. Mohan Madan, Senior General Manager at L7 posted in Edmonton, Canada is the senior most employee.
2. The top 5 countries with most invoices are-
   - USA-131
   - Canada-76
   - Brazil-61
   - France-50
   - Germany-41
3. The top 3 values of total invoices are- 23.76, 19.8 and 19.8
4. Prague having all invoices of 273.24 is the city having best customers
5. R. Madhav is the best customer spent in total $144.54

### Moderate
1. The top 5 customers of all Rock music genre are
   - Aaron Mitchell
   - Alexander Rocha
   - Astrid Gruber
   - Bjorn Hasen
   - Camille Bernard
2. Led Zeppelin have written maximum Rock Songs having 114 songs in total
3. The top 3 songs having song length larger than average song length
   - Occupation/Precipice-5286.95sec
   - Through a Looking Glass-5088.83sec
   - Greeting from Earth,Pt-1-2906.29sec

### Hard
1. Hugh O' Reilly have maximum spent on most popular artist Queen
2. The most famous genre as per countries
   - Argentina- Alternate & Peak
   - Australia- Rock
   - Brazil- Rock
   - Canada- Rock
   - India- Rock
3. The top customers as per country
   - Diego Geutierez- Argentia
   - Mark Taylor- Australia
   - Astrid Greber- Austria
   - Dran Peters- Belgium
   - Lousi Gocales- Brazil

## Final Conclusion
- To improve the employee retention rate, recognition to senior most employee Mohan Madan
- To improve sales, we should focus on top countries lika USA, Canda, Brazil, France and Germany. It would also provie that Rock Music is one of the best selling genre so it will better to increase the catalogue of Rock Music

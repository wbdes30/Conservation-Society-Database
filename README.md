# Conservation Society Database
### Project background: 
The South African Conservation Society has moved to relational databases. You have been tasked with constructing and implementing the database, and writing queries for common searches. The database contains the following tables:
- Reserve: Including location and size.
- Vehicle: Means of transportation to the Reserve.
- Tour: Including cost and duration.
- Staff: Employees of the Reserve and Tour provider.
- Visitor Group: Including visitors' country of origin and number of members.
- Booking: Visitor groups' booking details.
- Organisation: Information about bodies that funded the Reserves.
- Partnership: Details on the funding.
- Tour Package: One is created by the combination of several separate tours.

### Tasks:
1. Write	a	query	to	print	all	details	of	the	tours.	The	cost	of	the	tour	should	be	prefixed	with ‘$’	and	the	duration should	end	with ‘hours’.	Sort	the	records	from	the	highest	to	the lowest based	on	the	cost	of	the	tour
2. Write	a	query	to	print	out	the	details	of	the	booking:	the	booking	ID	along	with	its	start	and	end	times.	Rename	the	columns	as	‘Tour	Start	Time’	and	‘Tour	End	Time’.
3. Write	a	query	to	retrieve	the	details	of	the	booking:	the	booking	ID	along	with	the	booking	date, and	the	reserve	name.	Display	only	the	records	where	the	booking	has	been	made	at	a reserve larger than	 300	 hectares,	 with a vehicle capable of accommodating at least	seven passengers,	 and the booking is scheduled for more than six months from the	current	date.
4. Using	a	SUBQUERY,	print	the	name	and	size	of	each	reserve	that	has	a	vehicle	with	the	letter	‘b’	appearing	in	the	Rego	Number	(not	case-sensitive).	All	sizes	should	be	displayed	with	‘	hectares’	and	the	result	should	be	sorted	from	the	largest	to	the	smallest reserve.
5. Write	a	query	to	display	the	total	number	of	bookings	for	each	reserve	(Include	just	the	IDs	of the	Reserve) that	were	made	before	10:00	AM.	There	should	be	no formulas	as	column	names.	Order	the	results	by	ReserveID	in	ascending	order.
6. Write	a	query	to	print	the	name	of	staff	members	along	with	the	dates	of	the	booking,	if	the	bookings	were	made	in	October	of	any	year,	and	only	if	the	staff	members	are	either	reserve	managers	or	senior tour	guides	earning	at	least	 $70,000.	Order the results	by	Staff	Name	in	ascending	order. Additionally,	include	staff	members	who	do	not	have	any	bookings,	and	represent	any	null	values	as	'No	Booking'.
7. Write	a	query	to	display	the	country	of	the	visitor	group	and	the	name	of	the	staff	member	assigned to the	group for the	booking,	where the tour	duration	is	over two	hours,	 the	assigned	staff	member	has	two	or	more	bookings,	and	their	salary	is	less	than	or	equal	to	the	average	staff	salary.
8. Write	a	query	to	display	the	name	of	the package	tours	along	with	their	component	tours.	Include	only	packages	that	consist	of	more	than	two	component	tours.	The	column	names	should	indicate	whether	each	entry	is	a	package	or	a	component.
9. Write	a	query	to	display	the	ID,	name,	and	cost	of	all	package	tours.	Include	a	column	that	shows	the	total	cost	of	all	the	component	tours	within	each	package	and	another	column	that calculates the savings provided by the package tour.	 Ensure that all prices are	prefixed	with	'$’.	Note:	The	query	should	only	include	records	for	package	tours.
10. Write a query to display the name of the reserve and	its partnering	organization,	 the	duration	of	the	partnership	in	years,	and	the	amount	funded.	Include	only	records	where	the first digit	in the	organization contact	number	is	 '9'	 (excluding the area code),	 the	amount	funded	exceeds	the	average	funding	across	all	organizations,	and	the	reserve	has	no	package	tours	booked.	The	funded	amount	should	be	prefixed	with	“$”.

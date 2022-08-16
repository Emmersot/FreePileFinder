FreePileFinder API
Build an API that allows users to GET and POST reviews about various travel destinations around the world. Here are some user stories to get started. Note that you will have to create custom endpoints for some of these user stories.

As a user, I want to GET and POST reviews about travel destinations.
As a user, I want to GET reviews by country or city.
As a user, I want to see the most popular travel destinations by number of reviews or by overall rating.


As a user, I want to PUT and DELETE reviews, but only if I wrote them. (Start by requiring a user_name param to match the user_name of the author on the message. You can always try authentication later.)
As a user, I want to look up random destinations just for fun.

As a user, I want to be able to GET all messages related to a pile Description.
As a user, I want to be able to POST messages.
As a user, I want to be able to see a list of all groups.
As a user, I want to input date parameters and retrieve only messages posted during that timeframe.
As a user, I want to be able to PUT and DELETE messages, but only if I wrote them. (Start by requiring a user_name param to match the user_name of the author on the message. You can always try authentication later.)


Create a webpage that can be accessed via our API that that lets users GET and POST free pile finds, and lets others find free piles near them


PileID PileTitle Description Latitude Longitude Zip City State Photo Available (true/false) UserID DateTime

 PileId 	 UserId 	 Title 	 Description 	 PostTime 	Availability	 State 	 City 	 LongLat 	 Zipcode 


  PileId  = 1,	 UserId  = 4,	 Title  = Roommate cleanout,	 Description  = Entire contents of bedroom,	CreatedDate = 2022-16-08 13:47:33,	ModifiedDate = null,	Availability = TRUE,	 State  = OR,	 City  = Portland,	Lat = 45.58868933,	Lng = -122.56404786,	 Zipcode  = 97211
 PileId  = 2,	 UserId  = 3,	 Title  = Dog figurine collection,	 Description  = Looks like 100+ figurines of all types,	CreatedDate = 2022-15-08 12:47:34,	ModifiedDate = null,	Availability = TRUE,	 State  = WA,	 City  = Vancouver,	Lat = 45.65467058,	Lng = -122.53756002,	 Zipcode  = 98682
 PileId  = 3,	 UserId  = 3,	 Title  = Sports equipment,	 Description  = Sports equipment,	CreatedDate = 2022-14-08 13:47:34,	ModifiedDate = null,	Availability = TRUE,	 State  = OR,	 City  = Portland,	Lat = 45.48192877,	Lng = -122.5580511,	 Zipcode  = 97266
 PileId  = 4,	 UserId  = 2,	 Title  = Metal junk,	 Description  = Metal junk,	CreatedDate = 2022-13-08 12:47:33,	ModifiedDate = null,	Availability = TRUE,	 State  = WA,	 City  = Vancouver,	Lat = 45.67403396,	Lng = -122.74122815,	 Zipcode  = 98660
 PileId  = 5,	 UserId  = 1,	 Title  = Books,	 Description  = Books,	CreatedDate = 44903.5747106482,	ModifiedDate = null,	Availability = TRUE,	 State  = OR,	 City  = Portland,	Lat = 45.57305467,	Lng = -122.64396572,	 Zipcode  = 97211
 PileId  = 6,	 UserId  = 4,	 Title  = Dresser furniture,	 Description  = looks useable,	CreatedDate = 44903.5330555556,	ModifiedDate = null,	Availability = TRUE,	 State  = WA,	 City  = Vancouver,	Lat = 45.70731546,	Lng = -122.70110881,	 Zipcode  = 98685
 PileId  = 7,	 UserId  = 1,	 Title  = Shoes,	 Description  = 4 pairs, size men's 10,	CreatedDate = 44873.5747222222,	ModifiedDate = null,	Availability = TRUE,	 State  = OR,	 City  = Portland,	Lat = 45.48733436,	Lng = -122.76339164,	 Zipcode  = 97225
 PileId  = 8,	 UserId  = 5,	 Title  = Box of women's clothes,	 Description  = slze medium,	CreatedDate = 44873.5330671296,	ModifiedDate = null,	Availability = TRUE,	 State  = OR,	 City  = Portland,	Lat = 45.34753517,	Lng = -122.66505906,	 Zipcode  = 97068
 PileId  = 9,	 UserId  = 6,	 Title  = Garden tools,	 Description  = 2 shovels, 1 hoe, 1 hose,	CreatedDate = 44842.5747337963,	ModifiedDate = null,	Availability = TRUE,	 State  = OR,	 City  = Portland,	Lat = 45.60441824,	Lng = -122.8296801,	 Zipcode  = 97231
 PileId  = 10,	 UserId  = 2,	 Title  = Kids toys,	 Description  = Looks well loved, but has some more life in them,	CreatedDate = 44842.5330787037,	ModifiedDate = null,	Availability = TRUE,	 State  = OR,	 City  = Portland,	Lat = 45.57066628,	Lng = -122.59853484,	 Zipcode  = 97218
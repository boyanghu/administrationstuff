NAME:		STUDENT NUMBER: 	LAB ID:		GITHUB ID:
Min-Woo Kim	- 55466106		- w0q7		- rkaalsdn
David Xue	- 24184095		- q8i8		- xiayth
Bo Yang Hu	- 38903118		- j2c8		- boyanghu
MIA		- ?			- ?		- ?


TeamSoAsian <- team Name


Team Project Goal - plot the nearest water fountains to bike lanes and link them

What the system must do
	- 	
	- plot bike lanes
	- plot water fountains based on location of bike lanes
	- list out bike lanes for user to select
	- plot the nearest water fountains (within reasonable distances)
	- display that in map and table form

Existing systems
	- http://water.tylorsherman.com/
	- http://vancouver.ca/files/cov/map-cycling-vancouver.pdf
		- our project will be a combination of the two that links both together

StakeHolders
	- us the programers
	- the bikers
	- the city of vancouver 
 	- commuters in general

User Stories
	- As a biker I want to know where the nearest water fountain is to my everyday bike route to get water
	 	- parse and display geographical information on a map
			- toggle display information
		- click on bike lane and the nearest water fountain location (<5km) is highlighted 
			- an opinion to display nearest route to water fountain is visible
		- search history is persisted on google account and can be accessed later
		- Test:
			- sign in and sign out 
			- works within 5 km 
			- shows warning when no locations are within 5km

	- As a citizen I want to find the nearest water fountain to any location to get water
		- input any location in Vancouver
		- shows the nearest water fountain	
		- plots route to water fountain from input location
		- Tests:
			- test standard case (within Vancouver)
			- test false case (outside Vancouver)


	- As a citizen I want to find the nearest bike route to bike on
		- input any location in Vancouver
		- shows the nearest bike route	
		- plots route to bike route from input location
		- Tests:
			- test standard case (within Vancouver)
			- test false case (outside Vancouver)
 
	- As a Facebook user I would like to share, like, and comment on my experiances at certain Vancouver waterfountains
		- when a POI(this time a water fountain) is clicked a facebook "like" button is visible 
		 	- Also a comment box is avaliable 
		- Test:
			- Test with a psudo-profile 
			- Test when signed in
				- should go smoothly
			- Test when signed out 
				- program should redirect to facebook site to sign in and then redirect back

	- As a programer, I want to be able to patch any new information at will to insure the best possible user experiance.
		- create administrator previlages
		- Test:
			- try to edit the software with a normal account
			- test editting with administrator account
 






  

# Ameya-Python-Project
Wrote a python program that fetches movie information for the top 500 most popular movies from Metacritics.com
On this websites, there is an option to show the top movies. 
On Metacritics, it is called “Movies of All Time”
I used webscrapping to collect the movie information for the top 500 movies from each website and store them in a comma separated file (called [your name]_movies.csv). 

Next, from the movie information that I have collected, extract 2 pieces of information: The director, and the cast (actors/actresses). Build a dictionary of the movies that contain these information. Arrange them in any way you prefer but make sure we can access the information we need at any time. 
Example: 
Which movie do you want to check?
input: Saving Private Ryan
What information about this movie do you want to check? (Choose director or cast)
	input: Cast

Output:
	The cats of the movie Saving Private Ryan includes Matt Damon as Pvt. James Francis Ryan, Tom Hanks as Captain Miller, Adam Goldberg as Pvt. Stanley Mellish, Barry Pepper as Pvt. Daniel Jackson, Dennis Farina as Lt. Col. Anderson, Dylan Bruno as Toynbe, Edward Burns as Pvt. Richard Reiben, Giovanni Ribisi as T-5 Medic Irwin Wade, Jeremy Davies as Cpl. Timothy P. Upham, Joerg Stadler as Steamboat Willie, Max Martini as Cpl. Henderson, Paul Giamatti as Sgt. Hill, Ted Danson as Captain Hamill, Tom Sizemore as Sgt. Mike Horvath, Vin Diesel as Pvt. Adrian Caparzo

Then there are 3 tasks you need to complete:

1. Analyzed how many times has each actor/actress appeared in these top 500 movies, analyze how many times has each director appeared in these top 500 movies, what can that tell you about their career?

2. Created a dictionary of actors/actresses that the directors have worked together with in each movie, then calculated their cosine similarity, which directors work with similar groups of actors/actresses? Used director name as the dictionary name, actor/actress name as the key, and the times they have worked together in a movie as the value. For example: Michael Bay = {‘ Bruce Willis’: 50, ‘Ben Affleck’:20, ‘Liam Neeson’:10}, Steven Spielberg = {‘Liam Neeson’: 30, ‘Tom Hanks’:20, ‘Denzel Washington’:15}
Your program should show the similarity score between the directors. (An example is given below).

3. Picked 5 favorite actors/actresses from this list of top 500 movies. Then created a dictionary of all the actors/actresses that they have collaborated with in a movie. Following similar method as above in task 2, created the dictionaries, and compared these 5 actors,and decided who is the most popular supporting actor/actress among them all?



Example 2:
Michael Bay = Transformer: [Bruce Willis, Ben Affleck, Liam Neeson], Batman:[ Ben Affleck,  Liam Neeson]

Steven Spielberg = Schindler's List:[ Liam Neeson, Tom Hanks], American Gangster:[ Denzel Washington]

Michael Bay = {‘Bruce Willis’: 1, ‘Ben Affleck’:2, ‘Liam Neeson’:2}
Steven Spielberg = {‘Liam Neeson’: 1, ‘Tome Hanks’:1, ‘Denzel Washington’:1}

Common vector = (Bruce Willis. Ben Affleck, Liam Neeson, Tom Hanks, Denzel Washington)
Michael Bay vector = (1,2,2,0,0)
Steven Spielberg vector = (0,0,1,1,1)



 



### First things first: 

The values for the ratings are string values. We can use the ```VLOOKUP``` function in google sheets to give them a value from 1 to 4, 1 being ```BRONZE``` and 4 being ```SUPER GOLD```.
Let's create a quick values table in a new sheet: 

![values_table](https://user-images.githubusercontent.com/125606674/220447363-fd8f1e0c-bb5d-4d37-b580-55c4884d1873.png)

Now we can enter ```=VLOOKUP(D2, Sheet2!A:B, 2, FALSE)``` in the column right next to the string values to filter the ratings easier and get our answers quicker. 

After using the ```FILTER``` function, we can easily inpute ```4``` and quickly see the highest rated cheeses in each category: 

![cheese_table](https://user-images.githubusercontent.com/125606674/220450498-719dee7a-f4ae-4a3a-ac2b-f20416777e6f.png)

This isn't even half of the data returned! I have hid some columns that we can use their information for later, but for now, I have narrowed it down a bit to make it a little more readable. 

## What country collected the most Super Gold awards? 

This is a great opportunity for a **pivot table:**


![top_country](https://user-images.githubusercontent.com/125606674/220454109-f10a47da-719c-440e-97c2-63d0fa6ecf19.png)

Wow! This really surprised me- Spain was the most awarded in Super Gold, and more than doubled Italy's awards overall!
France coming in third overall, with less than half that of Italy's award count. 

Let's expand the table a bit to see the awards overall: 


![top_country_overall](https://user-images.githubusercontent.com/125606674/220462497-3f60c4fb-a168-46ca-8581-d57c6ea28a9d.png)

![most_awarded_country_pie](https://user-images.githubusercontent.com/125606674/220480193-6535b3d7-a105-41b4-83d5-a236e2b23f7b.png)


Spain, Italy, and France staying in the top 3 most awarded countries aren't surprising at all to me! It's really interesting to see how each ranked.

## What's the most awarded cheese overall?

I have a hunch already that it is Parmigiano-Reggiano. Let's see if I'm right! 

![most_awarded_cheese](https://user-images.githubusercontent.com/125606674/220465226-ab487667-40ec-48fb-9428-06e1e0cae261.png)

Just as I thought, the King of Cheese! 

*but wait, I thought Spain took home the most awards?*

Yes, they did. They won more **categorically**, meaning they raked in awards in a much broader array of cheeses, while Italy maintained the most awards in the category of Hard Cow's milk cheese.
Italy is known for their Parmigiano Reggiano across the world. They take it very seriously, and it is one of their largest exports in food. 
Coincidentally, 2021 was a record breaking year for them, exporting over 163,000 *tonnes* of Parmigiano! 


## What country won the most awards in each category?

*We will be using the filter function to then use that data to create some visualizations.*

# Bronze Category: 🥉


![bronze_awards](https://user-images.githubusercontent.com/125606674/220483510-c4cba07e-2b2b-4957-a58f-c663ed670b80.png)

- Spain is the winner by a longshot! 

# Silver Category: 🥈

![silver_awards](https://user-images.githubusercontent.com/125606674/220483581-36e35eaf-d432-4ed6-8028-c05926361b3c.png)

- Spain does it again! 

# Gold Category: 🥇

![gold_awards](https://user-images.githubusercontent.com/125606674/220483853-13c341c0-5375-41b2-8fb1-c631fc4b4328.png)

- Italy made a pretty big jump here, but Spain still remains on top.

# Super Gold Category: 🏆

![super_gold_awards](https://user-images.githubusercontent.com/125606674/220484163-1bf012fb-ceac-4acf-8768-4cb0b271cd8f.png)

Spain has consistently taken home the most awards in each category for the year 2021. Go Spain! 🎊

### Final thoughts:

This was a super fun dataset to explore, with some interesting findings! 

While Spain took the most awards home for 2021, 
Parmigiano Reggiano was the most awarded cheese. 
With my previous experience, this isn't too surprising. 
Spanish cheeses, such as Manchego, is an incredibly popular cheese. 
Spain has the advantage of sharing a border with France, which allows them to have more biodiversity, and in turn, making more diverse cheeses.

France coming quite far behind both countries is what surprised me the most! France is notorious for all of their delicious different kinds of cheeses and making them extremely well, and with care.
Seeing the United States fall short is par for the course, since U.S cheesemakers are a little late to the game, but there are some excellent cheeses to be considered! 


These insights have important implications for cheese producers and consumers alike. 
For example, producers may wish to focus on developing products in highly awarded categories in order to increase their chances of success at future competitions. 
Meanwhile, consumers can use this information to inform their purchasing decisions and discover new and highly acclaimed cheese products.

Of course, there are some limitations to our analysis, such as the fact that our data only covers a single year of the competition. 
Nonetheless, our findings offer valuable insights and suggest that further research into the cheese industry could be highly beneficial, such as expanding exposure to different kinds of cheeses from Europe and the U.S. to gain more recognition!


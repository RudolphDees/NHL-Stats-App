# NHL-Stats-App
A C# Windows Form application that pulls current data from the NHL Open API and visualizes it. 

I started this project just because I was curious to see if the NHL Open API was too good to be true. After breaking into some of the JSON and seeing the copious amounts of data I started working on a proof of concept to see if extracting the data from the API to my database was realiztic. It turned out to be easier than I thought so now im focusing on the visualization aspect and improving the interface and speed of the application. I am excited to see where this project can go and hope that anybody who stumbles on this enjoys it.

To any employers I urge you too look at all the different versions descriptions to see the progress I've made and keep in mind that I have no formal training in C#, SQL, JSON, or any technology used in this project. I used google, stack overflow, reddit, git hub, and other resources to gain the base knowledge and used trial and error, logic I have gained through college, and previous experience from other projects I have done to expand on that knowledge. I have grown very comfortable with all of the technologies and languages I have used and look forward to applying that to any future position I am in.

Version 1.0.0 (11/30/2021)

This was the first iteration of the application that was connected to my Azure SQL server. Previously It was connected to my MS SQL server which didnt allow remote connection.
After transfering to a cloud based SQL solution the speed of the application slowed down considerably so the next update will be focusing on optimizing how the application interacts with my database.

Version 2.0.0

I transfered my project to a WPF format on .NET Core since it looks better, is more customizable, and more relevant to potential employers. The transfer only took a few hours and has been much more interesting to use.

After Transitioning to WPF I put in 15-20 hours over the weekend to add the feature I've been working toward from day 1. While it still has some bugs, I added the Shot Map Page which allows you to plot out all of the shots that happened in any game in the 2021-2022 season. It is fully color coded to the team colors and displays the points on an image of a hockey rink. I thought getting to this point would take me a month or two and not a few weeks so I am excited to continue to expand and improve the application.

Along with the Shot Map page I also set it to automatically update most of the data if it hasnt been updated in the last 24 hours. I will be improving this as well in the near future.

My goals for the next update are working out the bugs of the shot map page, adding a help button for people that have never used the application before, and expanding the team stats page to reflect top scorers on the team. 

# beercation

Beercation is a web application designed for users to plan their vacations around the best brews in town. The initial concept of the site was to allow users to select a city, then select a hotel, and then see the nearby breweries.

We wanted the users to be able to choose their hotel based off the location, price range, and ratings. Due to CORS issues we weren’t able to use our initial API which would’ve allowed price and ratings to be included. The initial webpage that has been launched currently just generates hotels based off user’s location choice.

The current product utilizes google maps and google places library. The user picks a town or city and the site automatically generates a list of options for hotels. When the user selects a hotel of interest a new list appears with all the nearby bars. A second API also pulls a list of coupons for bars and restaurants in the area.

Future goals of the project will be to allow the user to specify parameters for their hotel like price, rating, etc. We would also like to limit the surrounding bars in the area to solely breweries or at least give the user the option to select what they want to see is nearby.
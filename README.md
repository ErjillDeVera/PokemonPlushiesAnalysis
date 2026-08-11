# PokemonPlushiesAnalysis

This project will analyse the Pokemon Plushies line up provided in the Pokemon Centre UK's website to uncover critical insights that will improve Pokemon's commercial success.

Insights and recommendations are provided on the following key areas:
- **Plush Category Trend**: Which category of Pokemon Plush is positively well recieved. The categories on the website include Ditto Plush, Spring Plush, Pikachu Plush, Poke Plush, Comfy Friends, Sitting Cuties, Large Plush, Keychains, Pokemon Dolls, Comfy Cuddlers, Eevee Evolutions, Plush Bags and Hats and Pokemon Squishmallows. This would allow us to see which category of plush is well recieved. 
- **Correlation with Review Ratings**: Understanding whether there is a correlation between reviews with factors such as size of plush and price range.
- **Pokemon & Region Analysis**: Determining which Pokemon's and Region has the highest positive ratings. 

From these insights, we can determine if there is a gap in the market for a specific Pokemon in a specific Plush category that could potentially increase revenue.

## Pokemon Plushies Dataset
The dataset was manually gathered from the Pokemon UK Website. In this observation I have noted down the following attributes:
- **Primary Key (Integer)**: Used to uniquely identify each item
- **Item Name (String)**: Name of the product
- **Width (2f float)**: Width of plushie in cm
- **Height (2f float)**: Height of plushie in cm
- **Length (2f float)**: Length of plushie in cm
- **Country of Origin (String)**: This is the country where the plush was made.
- **Plush Category (String)**: Category of the plushie (e.g. Ditto Plush, Spring Plush, Pikachu Plush, Poke Plush, Comfy Friends, Sitting Cuties, Large Plush, Keychains, Pokemon Dolls,, Comfy Cuddlers, Eevee Evolutions, Plush Bags and Hats and Pokemon Squishmallows).
- **Price (2f float)**: Price of product in British Pounds (£).
- **Pokemon (String)**: Pokemon Name of the plush
- **Region (String)**: Pokemon's origin region (e.g. Kanto, Johto, Hoenn, Sinnoh, Unova etc.)
- **5 star Review (Int)**: Number of 5 star reviews
- **4 star Review (Int)**: Number of 4 star reviews
- **3 star Review (Int)**: Number of 3 star reviews
- **2 tar Review (Int)**: Number of 2 star reviews
- **1 star Review (Int)**: Number of 1 star reviews


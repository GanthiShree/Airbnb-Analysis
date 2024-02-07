![alt tag](https://github.com/ruchigupta19/Gupta_Ruchi_Spring2017/blob/master/final/extra/airsmall.png)

### **Domain** : **Travel Industry, Property management and Tourism**

### Dashboard link : [Click to view my Dashboard](https://public.tableau.com/shared/RDRW8DDY3?:display_count=n&:origin=viz_share_link)
### **Problem Statement :**
  This project aims to analyze Airbnb data using MongoDB Atlas, perform data cleaning and preparation, develop interactive geospatial visualizations, and create dynamic plots to gain insights into pricing variations, availability patterns, and location-based trends.

### Workflow :
   Establish a connection to the MongoDB Atlas database and retrieve the Airbnb dataset. 
   Clean the Airbnb dataset by handling missing values, removing duplicates, and transforming data types as necessary. 
   Prepare the dataset for EDA and visualization tasks, ensuring data integrity and consistency.

## WHAT CAUSES DIFFERENCE IN PRICES OF LISTINGS?
  - I categorized different listings based upon their room type, property type.
  - Analyzing the prices for different room type and property type
  - Recognizing the significance of unique words provides hosts with insights into guest preferences.
  - The analysis of listting price using Amenities.
  - Finally the Reviews based on the price listing.

## 1. Data Point:
  - People show a stronger inclination towards listing their entire property compared to private rooms or shared rooms.
  
  - Property Type Impact:
    - The type of property also plays a crucial role in listing preferences.
  
  - Popular Property Types:
    - Not surprisingly, Apartments and houses dominate the majority of all listings.
    - These property types are the preferred choices for Airbnb hosts.

  - Diversity in Residencies:
    - While Apartments and houses are prevalent, there are instances of less common residencies in the listings.

  - Overall Trend:
    - The overall trend suggests a preference for offering entire properties, with Apartments and houses being the preferred choices among hosts.
   

## 2. Data Point:

- **Analysis Summary:**
  - With the increase in the number of bedrooms, the price of the listing tends to increase.
  - Prices of listings on Airbnb depend on several factors, including room type, property type, and the number of bedrooms.

- **Key Findings:**
  - Property with type as Apartment tends to have higher prices.
  - Listings with the type 'Entire House' and the maximum number of bedrooms command the highest prices.

- **Detailed Analysis:**
  - *Room Type Impact:*
    - The type of room (Entire House, Private Room, Shared Room) influences the listing price.
  
  - *Property Type Impact:*
    - Apartments show a noticeable correlation with higher prices.
  
  - *Number of Bedrooms Impact:*
    - Prices tend to increase with the number of bedrooms.
    - Listings with the maximum number of bedrooms, especially in the 'Entire House' category, have the highest prices.
  
## 3. Data Point:

- **Key Observations:**
  - Unique words commonly used by hosts in their Airbnb listings include:
    - Accommodation
    - Pool
    - Bedroom
    - Floor
    - Kitchen
    - Restaurant
    - Spacious
    - Shopping
    - Private
    - Tv

- **Analysis:**
  - The presence of these specific words indicates that hosts focus on highlighting certain features and amenities to attract potential guests.
  - Each word reflects a distinct aspect of the accommodation that hosts consider important for travelers.

- **Strategic Implications for Hosts:**
  - Hosts seeking to enhance the attractiveness of their listings may strategically incorporate these keywords in their summaries.
  - Emphasizing features like a private space, spaciousness, access to a pool, and proximity to shopping areas can capture the attention of potential guests.

- **Conclusion:**
  - Recognizing the significance of these unique words provides hosts with insights into guest preferences.
  - Aligning property descriptions with these keywords can potentially lead to increased visibility and interest from travelers seeking specific amenities and features.


## Factors Influencing Listing Prices:
  - Amenities:
    - Listings with higher prices often include extra amenities like Air conditioning, washer/dryer, Kid-friendly, Heating, hair dryer, buzzer, etc.
    - The presence of extra amenities is associated with increased prices.

  - Room Type:
    - Prices depend on the type of room chosen by travelers, with Entire property bookings costing the most, followed by private rooms and shared apartments.

  - Property Type:
    - Townhouses and houses tend to have higher prices, while apartments and houses dominate the majority of listings.

  - Number of Bedrooms:
    - Prices vary based on the number of bedrooms in the property.

  - Summary Section:
    - The content in the summary section, a private space, spaciousness, access to a pool, and proximity to shopping areas tends to attract more travelers.

  - Price and Amenities Correlation:
    - Higher prices are associated with an increase in the amenities provided by hosts.

- **Conclusion:**
  - The analysis reveals a nuanced understanding of the multiple factors influencing Airbnb listing prices.
  - Hosts can optimize their listings by considering these factors to attract a broader audience and maximize their property's appeal.
 
## Reviews based on the price listing:

- **Insight:**
  - The scatter plot reveals a clear trend where listings with prices in the range of $100 to $500 tend to receive the highest number of reviews.
  - As prices increase beyond this range, the number of reviews rapidly declines.

- **Observation:**
  - Listings priced around $100 - $500 attract more bookings, resulting in a greater number of reviews.

- **Conclusion:**
  - The data suggests that a more reasonable price range, approximately $100 to $500, is associated with a higher likelihood of bookings and, consequently, a greater number of reviews.

- **Implication:**
  - An expensive listing does not necessarily guarantee a large number of reviews, highlighting the importance of considering the optimal pricing strategy for attracting bookings.





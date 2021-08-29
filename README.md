# Zomato_EDA
This project is an initial exploratory data analysis for the Zomato website in Bengaluru the 3rd biggest city in India.
>for more details with video explaination here is the drive link for the dataset used [Project explanation drive link](https://drive.google.com/file/d/1Tk4rOX8UWU0pgZyvfrArGQ4F4s6oDfXe/view?usp=sharing)

dataset features description 

- `url`: contains the url of the restaurant in the zomato website

- `address `: contains the address of the restaurant in Bengaluru

- `name`: contains the name of the restaurant

- `online_order`: whether online ordering is available in the restaurant or not

- `book_table`: table book option available or not

- `rate`: contains the overall rating of the restaurant out of 5

- `votes`: contains total number of rating for the restaurant as of the above mentioned date

- `phone`: contains the phone number of the restaurant

- `location`: contains the neighborhood in which the restaurant is located

- `rest_type`: restaurant type

- `dish_liked`: dishes people liked in the restaurant

- `cuisines`: food styles, separated by comma

- `approx_cost(for two people)`: contains the approximate cost for meal for two people

- `reviews_list`: list of tuples containing reviews for the restaurant, each tuple consists of two values,rating and review by the customer
  
- `menu_item`: contains list of menus available in the restaurant

- `listed_in(type)`: type of meal

- `listed_in(city)`:contains the neighborhood in which the restaurant is listed

**Geographical analysis** 
Here is the heat map of the restaurants in Bengaluru.
 ![the heat map of the resaurants in Bengaluru](https://github.com/NourhanHassanEid/Zomato_EDA/blob/main/restaurants%20heatmap.PNG)

It is clear that restaurants tend to concentrate in central bangalore area. The clutter of restaurants lowers are we move away from central.

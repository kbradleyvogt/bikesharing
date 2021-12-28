# Bikesharing: How New Yorkers use the Citi Bikes 

## Purpose 

In order to understand if bike sharing in Des Moines is a worthwhile investment - we will explore the avalible data from the New York program, specifically August of 2019. This data will be used to answer question about the typical bike ride and the average user of the service. 

## Results 

The full [tableau story can be found here](https://public.tableau.com/app/profile/kayleigh.bradley.vogt/viz/CitiBikeDataReview/CitiBikeDataPresentaion?publish=yes), but included below is an overview of the findings. 

## Trip Duration 
Here we break down the amount of rides taken and how long the ride lasts. We can see a strong peak around the ten minutes long. The spike from 0 to 20 minutes shows that riders are using the bikes for trips nearby, not pleasure riding. 

![Checkout times](https://user-images.githubusercontent.com/86968320/147589751-54115654-bbd3-4e61-bbeb-0d0b9074a9de.png)

## Trip Duration by Gender 

Digging into the trip duractions deeper, we have segemented by gender. The two charts below show us two things. First the gender breakdown of users; more than 65% of the total riders are male. Second, we can see from the checkout times by gender chart, that while the female ridership doesn't display the same sharp peak at the 10 minute mark, the trend of trips under 20 minutes hold.

![Gender and checkout ](https://user-images.githubusercontent.com/86968320/147590092-6d940935-493c-4446-adf2-12accac4ac81.png)

## Peak Checkout Times by Hour 

Peak checkout tiems in August were between 5 - 7 p.m. with a spike at 7 a.m. as well. this is likely linked to worker commute times. 

![august peak hours](https://user-images.githubusercontent.com/86968320/147590316-a05e9414-8629-431c-a459-f0ceff95a639.png)

## Stop Times by Day of the Week and Hour

The peak hours of useage hold across the weekdays (Monday - Friday) but we can see a wider rage of use times on the weekend (Saturday and Sunday). We can assume this is linked to weekend recreation. A next step for analysis would be to map where people are travling on the weekend vs weekday to understand how to balance bike placement for commuters and tourists. 

![trips by hour](https://user-images.githubusercontent.com/86968320/147590720-c28af693-8719-4dac-a16d-545759f8cb51.png)

When we break the data down by gender, the trend holds across all categories. The only interesting item here is that our unknown users are more likely to be weekend rider, with little to know use during commuting times. 

![image](https://user-images.githubusercontent.com/86968320/147590797-1338f928-bd60-420d-8c5d-353b211f3d87.png)

# User Trips by Gender and Day of the Week 

The biggest users of the citibikes are the make subscribers. With the strongest usage showing at the end of the work week. Looking at customers we can see a stronger use during the weekend. This data begs the question of which bike station coorispond in popularity for these different types and user groups. 

![user v customer](https://user-images.githubusercontent.com/86968320/147591539-8346a8cc-b942-45ea-8236-91f0f0dbc86a.png)


# Next Steps 

The data analysed thus far provide a picutre of two main user segments:
- The male, subscribing, commuter 
- The weekend recreationist

In order to better understand and serve these groups there are at least two more items to understand:
- Where are people going? Mapping where people are travling on the weekend vs weekday to understand how to balance bike placement for commuters and tourists. Using the starting and stoping locations in the data and use a day of the week filter to find varied trends for the weekday vs weekend.
- What stations are being used? Visualizing what bike stations are in high demand and which ones are under utilitzed can help us build a more optimized bike station setup in Des Moines. 





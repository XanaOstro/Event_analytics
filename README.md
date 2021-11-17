# Event analytics
## Collecting project_2. Exploration the results of an A / A / B experiment.

Reposiitory contains both Russian ang English versions.

## Project goals:

It is necessary to analyze users behavior in the mobile application. Examine the sales funnel and find out how and how many users make a purchase.

Explore the results of an A / A / B experiment to see if it is worth changing the fonts in the application.

Users are divided into 3 groups: 2 control groups with old fonts and one experimental group with new ones.

## Libraries: 
pandas, numpy, seaborn,, sweetviz, matplotlib, plotly, math, scipy.

## Conclusions:

1. The following chain of events was considered: MainScreenAppear -> Tutorial -> OffersScreenAppear -> CartScreenAppear -> PaymentScreenSuccessful.

2. At the offer stage, 62% of users remain, at the cart stage - 50% from viewing the main screen and 81% from the cart stage. 95% of users go from shopping cart to successful checkout. All the way from app launch to purchase was completed by 48% of users.

3. At the offer stage, 38% of users are lost, at the cart stage - another 19%, at the checkout stage - another 14%. Thus, most of the users are lost in the OffersScreenAppear stage.

4. The differences for each event between all groups are not statistically significant, i.e. there is no reason to consider the ratios to be different. This means that the division into groups was done correctly, and also that changing the font in the mobile application does not affect customer behavior.

**Data provided by**: Practicum by Yandex

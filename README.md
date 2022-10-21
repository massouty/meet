# Meet APP 

It uses for defining date of meeting  and city of user .

# How  we can use this application :

enter to  Google calendar  then   find it  adding list .

_______________________________________________________________
# Feature  : Show /hide an event's details.

As a user , I should be able to Show /hide an event's details so that I can show or hide  event's details .

## ☁️ Scenario 1:

Collapsed by Default.

Given user is on the main page.

When nothing is selected.

Then the even details will be 'collapsed'.

## ☁️ Scenario 2:

Expanding the details.

Given user wants to see more about an event.

When the user clicks clicks on that event.

Then the details for that event will expand.

## ☁️ Scenario 3:

Collapse the details.
Given user has seen the details and wants to collapse.
When the user clicks on the expanded details.
Then the details will collapse again.

# Feature: Specify number of Events

As a user I should be able to choose the number of events I want to see.

## ☁️ Scenario 1:

When the user hasn’t specified a number, 32 is the default number.
Given: the user searched for event results for a city.
When: the user chooses no specific amount of search results.
Then: the default amount of search results per city will be 32.

## ☁️ Scenario 2:

The user can change the number of events they want to see.

Given: the user opened the search results query.

When: the user changes the default number.

Then: the default number of results will be changed to what the users select.

# Feature: Use App even when offline

As a user I would like to be able to access events even when offline

## ☁️ Scenario 1:

Show cached data when there’s no internet connection.

Given: the app has no internet connection.

When: the data is cached.

Then: that data will be shown.

## ☁️ Scenario 2:

Show error when user changes the settings (city, time range).

Given: the user opened the settings tab.

When: the user changes the settings.

Then: an error will show.

# Feature: Data Visualization

As a user I would like to see charts with the number of upcoming events in my city

## ☁️ Scenario 1:

Show a chart with the number of upcoming events in each city.

Given: the user selected a city.

When: the user clicks on the city’s upcoming events button.

Then: a chart will list the upcoming events taking place in the city.


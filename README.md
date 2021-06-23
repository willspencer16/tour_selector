# Tour Selector

A simple React project to practice fetching and displaying data from an API, following a tutorial by ```freeCodeCamp.org```.

The app fetches data from an API and displays it:

![Screenshot 2021-06-23 at 11 16 09](https://user-images.githubusercontent.com/77449895/123080457-d8ffa880-d414-11eb-9df4-17c1c6145f78.png)

The API is provided by ```freeCodeCamp.org``` and consists of an array of objects, specifically tours populated with id, image, info, price and name. The app fetches this data and displays it using the tours component, which iterates over the tours data to display each.

## See More / Show Less

The User can now see more / less information about each tour by clicking the Read More / Show Less button respectively:

![Screenshot 2021-06-23 at 11 16 16](https://user-images.githubusercontent.com/77449895/123080625-0a787400-d415-11eb-9161-9545c0cdf80e.png)

To create this I used with state value in conditional rendering.

## Not Interested

The User can also remove a tour by clicking on 'Not Interested':

![Screenshot 2021-06-23 at 11 16 26](https://user-images.githubusercontent.com/77449895/123080756-2aa83300-d415-11eb-988a-364f525492df.png)

This works by setting the id-specific state value to zero.

## Refresh

If all tours are removed, the app displays a 'Refresh' button to retrieve all tours again:

![Screenshot 2021-06-23 at 11 16 35](https://user-images.githubusercontent.com/77449895/123080889-4e6b7900-d415-11eb-9ef6-26b6d82409c6.png)

For this I used conditional rendering again, which checks if all tours have been removed and renders a separate message and button accordingly. The button then fetches all tours again.



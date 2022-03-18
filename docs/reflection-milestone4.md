# Reflection for Milestone 4

## Function:

#### For both R and Python Dashboards:
The main functions for both R and Python Dashboard are similar. They both consist of:

* 4 plots: 3 histograms for athletes' `Age`, `Weight`, and `Height` distribution that can zoom in or out with two colors to distinguish genders, and a map for number of athlete per country.
* 5 filters on the left side bar: a slider for `year` range selection, two drop-down menus for `sports` and `countries`, and two radio buttons to select `medal` and `season`.

#### For Python:
Owing to the time schedule and available reviews, we made more optimization on our Python Dashboard, namely:
* 1 more filter: to show whether we can animate the world map by year.
* 1 more tab: there are two tabs in Python Dashboard. All the plots are on the "Plots" tab, the "Data Table" tab shows the clean data based on the selected filters.
* Tooltips on filter: to better guide users to use filters properly.
* A help button: to briefly explain what this dashboard does and guide users.
* 1 alert: to show a warning "No Available Data For Search Parameters" on the left side bar when users select some specific combination with no available data, such as Alpine Skiing in Summer Olympics.

## Further Improvement:
There are currently no major bugs in our dashboard. But we can have optimizations as follows:

#### For both Dashboards:
* Adjust the `year` filter to fit the Quadrennial cycle of the Olympics.
* Change the colors and style to be in line with the Olympic theme, for example, using the colors of the Olympic rings.

#### For R:
* Finish all the functions and detail adjustment we did in Python Dashboard, especially the alert.

#### For Python:
* Optimize the text in tooltips to be more brief. And now the tooltips will be flashing if we put the mouse pointer near the filter title instead of over it, we need to fix this.

## Inspirations
Through the reviews and our development process, we think one of the inspirations is thinking as a user who knows **NOTING** about the dashboard. This will lead us to find more details to optimize or bugs we didn't notice before. Besides, always remembering the purpose is vital as well.

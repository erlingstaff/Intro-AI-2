**OBLIG 2**

Erling Mathias Staff - S354344

Ole Jørgen Knoph - s354371

Kristian Smedsrøud - 

<hr>

We chose use case #2, predict the amount of passengers in a bus on a specific day

For this use case, we chose a regression(forest) algorithm. We intially completed the task with a classificationforest, but after testing with a regression-algorithm, we achieved a ~25% drop in our MAE (Mean Absolute Error) score, from 4.04 -> 3.39. Lower is better in this case.

<hr>


To guess the amount of passengers on a specific day for bus *150*, edit the "year", "month", and "day" variables in the second to last cell

MAE (Mean Absolute Error) with test-size 0.25 and a dataset of 96 entries: **3.39** 

*Example-tree in the forest:*

![output](https://user-images.githubusercontent.com/38101463/137980063-b8ec7424-e626-4e2a-8b90-644da4952213.png)

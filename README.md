# NYC-Citi-Bike-Demand-Location-Prediction-and-Analysis
README.md
### Team Members

Stanley H. Gu: shgu2@illinois.edu

Yandong Luo: yandong2@illinois.edu

Jingwei Bao: jb52@illinois.edu

Weichen Liu: wl45@illinois.edu

## Problem Summary

Our project focuses on New York City’s Citi Bike bicycle sharing services. Lyft company want to determine where exactly more Lyft Bikes should be placed at what times of the day, since oftentimes, the start and end stations differ in location, so that we are aiming to train a neural network algorithm to predict the popular Lyft Bike destination stations in NYC. The parameters we currently consider as feather are as follows, based on them the algorithm will be designed to predict the end station name as results.

  • Start Station name (one hot vector)

  • Rideable Type (classic bike, electric bike, docked bike)

  • Date (month, day of the week)

  • Start time

  • End time

  • Trip Duration (seconds)

  • Start latitude/longitude

  • End latitude/longitude

  • Weather (currently precipitation, will add snowfall and temperature in the future) 

  • User Type (casual or member)

## License

Copyright (c) [2022] [Stanley H. Gu, Yandong Luo, Jingwei Bao, Weichen Liu]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is

furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

## dataset 

Our dataset is provided by Lyft Bikes and Scooters, LLC(“Bikeshare”) which operates New York City’s Citi Bike bicycle sharing service. As part of that commitment, Bikeshare makes certain Citi Bike system data (“Data”) available to the public.

Bikeshare grants to us a non-exclusive, royalty-free, limited, perpetual license to access, reproduce, analyze, copy, modify, distribute in your produc

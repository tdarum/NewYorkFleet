# New York Data

New York merupakan salah satu kota tersibuk di dunia. Trasnportasi yang paling sering digunakan sebagai transpotasi sehari - hari adalah taxi. Project ini akan akan berfokus pada melakukan analisa terhadap data dan memberikan insight berdasarkan data taxi NYC trip sehingga dapat melihat pattern, melakukan optimalisasi service, dan provide      
Project ini bertujuan untuk melakukan

Initially appeared on
[gist](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2). But the page cannot open anymore so that is why I have moved it here.
##  Garis besar Project
The steps applied in this project will include but are not limited to these highlighted below.

### 1. Data Preprocessing and Cleaning
        - Handle missing values 
        - Convert date-time fields into an appropriate format and then extract relevant features from the date: hour, weekday, month.
        - Handle outliers in trip_distance and fare_amount-for instance, extremely high values for fare_amount.
        - Map location IDs to known NYC boroughs/zones for better insights.
### 2. Exploratory Data Analysis
        - Find peak hours, days of the week, and seasonal trends.
        - Map hot zones for pickups and drop-offs based on PULocationID and DOLocationID.
        - Look at fare vs. trip distance based on Rate Codes.
        - Check different usage patterns among different payment methods.
### 3. Feature Engineering
        New features to be created are as follows:
        - trip duration : Time difference between dropoff and pickup.
        - Trip Speed: The trip distance divided by the trip time .
        - Rush Hour: Provides an indicator flag on whether it is rush hours.


## Project Use Case
In this capstone project there are some question that needs to be answered:

1. Driver and fleet optimization : How to optimize fleet operations by increasing efficiency and reducing idle time

2. How to identify the busiest times and predict the amount of demand at a given time When and where taxi demand increases

3. Payment Preferences and Driver Income Impact Which payment methods are most popular, and how do they impact driver income

4. Relationship between Trip Fare and Distance Is there a correlation between trip distance and fare amount?

5. Trip Duration and Zone Analysis Which zones (PULocationID, DOLocationID) experience the longest travel times?
6. Impact of Surcharges on Total Fare How do surcharges (MTA taxes, surcharges, tolls) affect total fare?
7. Detecting Fraudulent Trips Are there any unusual trips that could indicate data entry errors or fraud?
8. Comparison between vendor performance Is there a difference between the average trip distance, time and cost of vendor 1 and 2

Lorem Ipsum

### Library

Requirements for the software and other tools to build, test and push 
- [Example 1](https://www.example.com)
- [Example 2](https://www.example.com)

### Installing



## Running the tests

Explain how to run the automated tests for this system

### Sample Tests

Explain what these tests test and why

    Give an example

### Style test

Checks if the best practices and the right coding style has been used.

    Give an example

## Deployment

Add additional notes to deploy this on a live system

## Built With

  - [Contributor Covenant](https://www.contributor-covenant.org/) - Used
    for the Code of Conduct
  - [Creative Commons](https://creativecommons.org/) - Used to choose
    the license

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code
of conduct, and the process for submitting pull requests to us.

## Versioning

We use [Semantic Versioning](http://semver.org/) for versioning. For the versions
available, see the [tags on this
repository](https://github.com/PurpleBooth/a-good-readme-template/tags).

## Authors

  - **Billie Thompson** - *Provided README Template* -
    [PurpleBooth](https://github.com/PurpleBooth)

See also the list of
[contributors](https://github.com/PurpleBooth/a-good-readme-template/contributors)
who participated in this project.

## License

This project is licensed under the [CC0 1.0 Universal](LICENSE.md)
Creative Commons License - see the [LICENSE.md](LICENSE.md) file for
details

## Acknowledgments

  - Hat tip to anyone whose code is used
  - Inspiration
  - etc

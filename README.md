# Home_Sales
In this challenge, use the knowledge of SparkSQL to determine key metrics about Home Sales data. Then use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

## Respond to the requirements:

[1] A Spark DataFrame is created from the dataset. 

<img width="908" alt="Screenshot 2024-05-31 at 12 37 41 PM" src="https://github.com/hatkiet/Home_Sales/assets/154276115/bc11036c-92b3-4468-9c50-be43d91f52b9">

[2] A temporary table of the original DataFrame is created. 

<img width="909" alt="Screenshot 2024-05-31 at 12 38 57 PM" src="https://github.com/hatkiet/Home_Sales/assets/154276115/871451c4-2323-4fb2-96dd-c0d9bce9ce50">

[3] What is the average price for a four-bedroom house sold for each year? 

<img width="831" alt="Screenshot 2024-05-31 at 12 43 12 PM" src="https://github.com/hatkiet/Home_Sales/assets/154276115/beaec277-66e9-424a-9e37-d2b677986b97">

[4] What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

<img width="660" alt="Screenshot 2024-05-31 at 12 44 05 PM" src="https://github.com/hatkiet/Home_Sales/assets/154276115/a85f5b47-7d74-49f6-b91e-4bbdcd47600f">

[5] What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

<img width="736" alt="Screenshot 2024-05-31 at 12 46 40 PM" src="https://github.com/hatkiet/Home_Sales/assets/154276115/d95a3688-99bb-49b0-b12f-ad5a0886ad23">

[6] What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places. (The output shows the run time for this query.) 

<img width="814" alt="Screenshot 2024-05-31 at 12 47 41 PM" src="https://github.com/hatkiet/Home_Sales/assets/154276115/fb7651a8-02d4-4fb5-ad02-6337239a331a">

[7] A cache of the temporary "home_sales" table is created and validated. 

<img width="719" alt="Screenshot 2024-05-31 at 12 49 46 PM" src="https://github.com/hatkiet/Home_Sales/assets/154276115/59ed703a-e23b-4c61-afe0-15a009fb6ffd">

[8] The query from step 6 is run on the cached temporary table, and the run time is computed. 

<img width="642" alt="Screenshot 2024-05-31 at 12 50 44 PM" src="https://github.com/hatkiet/Home_Sales/assets/154276115/f903e57b-5bf0-442f-ab51-ad3f9966669c">

[9] A partition of the home sales dataset by the "date_built" field is created, and the formatted parquet data is read. 

<img width="784" alt="Screenshot 2024-05-31 at 12 51 51 PM" src="https://github.com/hatkiet/Home_Sales/assets/154276115/a54c2bec-ab9f-42b2-b9c6-51ba3fb48399">

[10] A temporary table of the parquet data is created. 

<img width="501" alt="Screenshot 2024-05-31 at 12 52 13 PM" src="https://github.com/hatkiet/Home_Sales/assets/154276115/ccd9281c-dbf7-4cc1-be15-4079e4ac2c9b">

[11] The query from step 6 is run on the parquet temporary table, and the run time is computed. 

<img width="642" alt="Screenshot 2024-05-31 at 12 53 01 PM" src="https://github.com/hatkiet/Home_Sales/assets/154276115/dae64eed-eee5-4b85-9c30-6ef0a9d5d74b">

[12] The "home_sales" temporary table is uncached and verified.

<img width="493" alt="Screenshot 2024-05-31 at 12 53 28 PM" src="https://github.com/hatkiet/Home_Sales/assets/154276115/9d27f140-1cb6-4c39-8ec5-e8bcbcaa858a">


[Note]: I have used our knowledge of SparkSQL and Big Data (activities from Day 1 to Day 3 in class) to answer key metrics for Home Sales challenge. 

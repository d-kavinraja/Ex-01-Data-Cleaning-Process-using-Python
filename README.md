# Exno:1
Data Cleaning Process

# AIM
To read the given data and perform data cleaning and save the cleaned data to a file.

# Explanation
Data cleaning is the process of preparing data for analysis by removing or modifying data that is incorrect ,incompleted , irrelevant , duplicated or improperly formatted. Data cleaning is not simply about erasing data ,but rather finding a way to maximize datasets accuracy without necessarily deleting the information.

# Algorithm
STEP 1: Read the given Data

STEP 2: Get the information about the data

STEP 3: Remove the null values from the data

STEP 4: Save the Clean data to the file

STEP 5: Remove outliers using IQR

STEP 6: Use zscore of to remove outliers

# Coding and Output
```
DEVELOPED BY : Kavinraja D
REG NO : 212222240047
```
1.Read and Display Dataframe

![308787257-17bfa5f0-8e3e-4788-9fa6-b30ec1fa2d6e](https://github.com/charumathiramesh/exno1/assets/120204455/a841edb6-2148-426d-b139-90f38786b880)


Output

![308787369-e39ad9a4-c7c7-4d70-aa4a-7342f8d71429](https://github.com/charumathiramesh/exno1/assets/120204455/fa7d3fe9-1be4-4221-bc03-e5be9859acb8)


2.Display Head

![308787537-02ca8ab8-cc92-4dbc-a1ba-42a52c14a6a9](https://github.com/charumathiramesh/exno1/assets/120204455/92e5581e-1301-4381-81e4-2413d800d63d)


Output

![308787636-9d221eb7-3374-4216-be10-896ef7514902](https://github.com/charumathiramesh/exno1/assets/120204455/b5d6de8e-92b5-44b7-b547-b7a413e52b14)


3.Display Tail

![308787777-2f60d737-7114-4ea2-879b-bdcf4be83765](https://github.com/charumathiramesh/exno1/assets/120204455/de9c9caf-4475-44ac-9c1d-98800f45f6e1)


Output

![308787871-52a8e4d1-2a96-4d51-ba93-ce8752a8ca25](https://github.com/charumathiramesh/exno1/assets/120204455/058026a7-fd7b-4b55-9f87-b94217b5648d)



4.Info of DataFrame

![308787993-bedefbdb-de71-49c5-bcb0-3e32209ccb2f](https://github.com/charumathiramesh/exno1/assets/120204455/16bab9ac-a2ef-42f9-b5e6-1c896f875f6b)


Output

![308788081-b983145e-fc05-41b8-8799-023f84d2ffc4](https://github.com/charumathiramesh/exno1/assets/120204455/244fb6f0-f822-4483-a3e0-9166f76d4ffb)


5.Describe about Dataframe

![308788239-4e31132e-ddf8-4129-a6f3-717a1b7c6dad](https://github.com/charumathiramesh/exno1/assets/120204455/fb06dba2-108f-40ed-9576-0df9e7ee24fe)


Output

![308788332-5aff5bfc-4624-4e7b-97a9-7e2415c50a64](https://github.com/charumathiramesh/exno1/assets/120204455/4f664209-0cc4-49e0-af25-0bdf07636511)


6.Shape of the dataframe

![308840841-4e35144b-922d-43a1-ba84-57299a8d5914](https://github.com/charumathiramesh/exno1/assets/120204455/c14a26dd-dc04-4f07-b647-d20807e74101)


Output

![308840973-a9a58572-d402-4367-b3be-76a7d2e3ee65](https://github.com/charumathiramesh/exno1/assets/120204455/abf05221-695a-42f1-8690-a210b8ee531b)




7.Checking tha NUll values

![308841164-860e00fb-88b8-4c81-a9e2-9af250457007](https://github.com/charumathiramesh/exno1/assets/120204455/fdf61144-ee8f-4b6a-99a2-a10b18a52a3e)


Output

![308841277-46c14197-5b6b-4cdd-830e-d7b9870e8f46](https://github.com/charumathiramesh/exno1/assets/120204455/7c578d45-80bb-49d8-a6dd-bb88dc5d9c35)


8.Drop the Null values

![308841456-216c68b1-2d00-4054-b0ad-6daa53058024](https://github.com/charumathiramesh/exno1/assets/120204455/f7838428-74a9-4e3f-bc69-80740d0acf42)


Output

![308841593-f9ad02c7-1256-4650-bb9f-d5b55da1471a](https://github.com/charumathiramesh/exno1/assets/120204455/38dfe305-66d7-4c67-9537-fe2fb1c96e4c)



9.Drop the Null values in Total

![308841987-a93ff3d6-0f45-43ab-8bd5-3be113e84170](https://github.com/charumathiramesh/exno1/assets/120204455/4b572bdc-ca65-4ff1-9d1d-047bf14fe967)


Output

![308842552-57a542a3-415f-464f-9229-c6b96bfd047a](https://github.com/charumathiramesh/exno1/assets/120204455/92eedc23-8162-47d8-a531-d526cc965c46)

10.Determinig the Duplicates

![308843571-3c4e1ba6-47e7-44d4-91c9-e37dfff5e8a1](https://github.com/charumathiramesh/exno1/assets/120204455/96d197f1-de73-4518-a679-f90ce80e1e58)

Output

![308843703-869c9a72-ffe2-48cb-85fc-b84a0846e2a4](https://github.com/charumathiramesh/exno1/assets/120204455/119d36c0-3b88-4cdb-827a-4eb12d7909fc)

11.Deleting the duplicates
![308844765-efbabc0f-9cf8-4dd8-8c60-caea3e10d869](https://github.com/charumathiramesh/exno1/assets/120204455/396127b1-85f4-49f3-ac67-948f894263e4)


Output

![308844908-5d95fa7b-3a2d-4e52-bd58-771dfc5f4555](https://github.com/charumathiramesh/exno1/assets/120204455/a3fb0b83-3980-461a-8041-2b48b0befa3f)


12.Highlighting Null values

![308846170-1ff7e73b-f5ca-46e8-b841-e0e06fda57bb](https://github.com/charumathiramesh/exno1/assets/120204455/47883e6c-b149-4a3e-bcf0-a447be555408)


Output
![308846389-e4ffd3df-b29c-4125-bfe9-f12eb1e8fc64](https://github.com/charumathiramesh/exno1/assets/120204455/3091b645-304a-4cdd-bb31-427edcc3f24b)

13.Dropping Null vales
![308846578-0bdc3bec-358c-4e44-af13-8b6c6535b2b3](https://github.com/charumathiramesh/exno1/assets/120204455/b3427295-115f-4dd2-bbf0-99e7a5875379)




Output


![308846686-3270d8e2-5e32-4045-91b7-1e5136d58911](https://github.com/charumathiramesh/exno1/assets/120204455/ebdca8af-20b4-40e8-ae83-d0273341a3b1)



# Result
The data clearning has beeen done successfully

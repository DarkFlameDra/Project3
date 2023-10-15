# Project3
To start Project 3 we nee to somplete the following questions:
Use the data from MongoDB sample: sample_supplies
Find the following queries.

1.Show top 10 products (name) sales (quantity x price).

2.Show top 3 products (name) sales by store (location).

3.Show rankings of each store (location).

4.Show purchased method by gender table

 ![image](https://github.com/DarkFlameDra/Project3/assets/148003597/e4a72678-365d-40a3-a790-9c1234b5d329)

5.Show monthly total sales 

Perform data analytics using any notebook tool. 

ex:, Kaggle, Colab, VSCode Notebook 

Open mongodb and create a temperaly user for the task
![image](https://github.com/DarkFlameDra/Project3/assets/148003597/03782b82-701a-4dbe-8135-bbbcd2a07d55)
Connect with VS Code with command :
mongodb+srv://pj3:63383870@cluster0.mej1zzq.mongodb.net/
In cmd, create a json file with this command:C:\Users\chenl>mongoexport --uri="mongodb+srv://pj3:63383870@cluster0.mej1zzq.mongodb.net/sample_supplies" --collection="sales" --out=sales.json
Create a jupyternotebook file and do complete the questions

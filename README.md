# Python_Project_Sem3
import matplotlib.pyplot as plt
import pandas as pd
import csv
df=pd.read_csv("Customer_Feedback.csv") 
name=df['Name']
print(name)
users=df['Services']


plt.bar(name, users)
plt.xlabel("Name of Restaurants")
plt.ylabel("Ratings")
plt.title('Services')
plt.show()

df=pd.read_csv("Customer_Feedback.csv") 
name=df['Name']
print(name)
users=df['Hospitality']

plt.bar(name, users)
plt.xlabel("Name of Restaurants")
plt.ylabel("Ratings")
plt.title('Hospitality')
plt.show()

df=pd.read_csv("Customer_Feedback.csv") 
name=df['Name']
print(name)
users=df['Rates']

plt.bar(name, users)
plt.xlabel("Name of Restaurants")
plt.ylabel("Ratings")
plt.title('Rates')
plt.show()

df=pd.read_csv("Customer_Feedback.csv") 
name=df['Name']
print(name)
users=df['Infrastructure']

plt.bar(name, users)
plt.xlabel("Name of Restaurants")
plt.ylabel("Ratings")
plt.title('Infrastructure')
plt.show()

df=pd.read_csv("Customer_Feedback.csv") 
name=df['Name']
print(name)
users=df['Location']

plt.bar(name, users)
plt.xlabel("Name of Restaurants")
plt.ylabel("Ratings")
plt.title('Location')
plt.show()

df=pd.read_csv("Customer_Feedback.csv") 
name=df['Name']
print(name)
users=df['Taste of Veg Food']

plt.bar(name, users)
plt.xlabel("Name of Restaurants")
plt.ylabel("Ratings")
plt.title('Taste of Veg Food')
plt.show()

df=pd.read_csv("Customer_Feedback.csv") 
name=df['Name']
print(name)
users=df['Taste of Non Veg Food']

plt.bar(name, users)
plt.xlabel("Name of Restaurants")
plt.ylabel("Ratings")
plt.title('Taste of Non Veg Food')
plt.show()

df=pd.read_csv("Customer_Feedback.csv") 
name=df['Name']
print(name)
users=df['Home Delivery']

plt.bar(name, users)
plt.xlabel("Name of Restaurants")
plt.ylabel("Ratings")
plt.title('Home Delivery')
plt.show()

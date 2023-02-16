# Heroku

#### **Guide** 
### **Using the MongoDB Atlas UI**
The easiest way to get started with MongoDB is by using the Atlas developer data platform. A free tier is available with basic database functionalities. This free tier is more than enough for the purposes of this article.


### **Prerequisites for MongoDB Atlas**
To create a database on MongoDB Atlas, you will need to register an Atlas account and create your first forever-free cluster:

* [Register a free Atlas account](https://account.mongodb.com/account/register?_ga=2.128784396.1632078396.1676568400-342271493.1676568400) with your email address (no credit card required)
* [Deploy your first cluster](https://www.mongodb.com/docs/atlas/tutorial/deploy-free-tier-cluster/) in less than 10 minutes

### **Creating a MongoDB Database with the Atlas UI**
From your cluster page, click on “Browse Collections.”
![img](https://webimages.mongodb.com/_com_assets/cms/l8sx7eoqk4klqwad9-First%20Cluster.png?auto=format%252Ccompress)
If there are no [databases](https://www.mongodb.com/databases) in this cluster, you will be presented with the option to create your first database by clicking on the “Add My Own Data” button.
![img2](https://webimages.mongodb.com/_com_assets/cms/l8sxqpmfwc2zv85o4-Add%20Data.png?auto=format%252Ccompress)
This will open up a modal, asking you for a database name and collection name. Once these fields are filled, click on “Create” and your database will be created for you.
![img3](https://webimages.mongodb.com/_com_assets/cms/l8syibibn98qljn59-Create%20Database%20in%20Atlas.gif)
The database is now available to you. You can manually enter new documents, or connect to the database using any of the MongoDB drivers.

### ***Connecting it to your bot***
To connect your MongoDB to your bot, click the `Connect` button.
![img4](https://webimages.mongodb.com/_com_assets/cms/l8sx7eoqk4klqwad9-First%20Cluster.png?auto=format%252Ccompress)
After clicking `Connect` select the `'Connect Your Application'` option.
![img5](https://media.discordapp.net/attachments/1039277692106846288/1075833104490569808/Screenshot_2023-02-16_17.36.20.png?width=517&height=432)

Now you have your MongoDB URL, all thats left is to copy it and put the password.

The URL should look something like this: 
```
mongodb+srv://NAME:<password>@NAME.hrwdsqg.mongodb.net/?retryWrites=true&w=majority
````

Where it says `<password>` is where you need to replace it with the password you set.

Then paste it into your bots `.env` and you're done!

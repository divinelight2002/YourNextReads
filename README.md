# YourNextReads&#128218;

### Hey there! Welcome (Namaste) to YourNextReads&#128218;, developed in 2022 by Divyata Gosai.

The YourNextReads is a web app built for book lovers with a Book
Recommendation engine. 

A web app uses a hybrid recommendation engine
with different machine learning algorithms to power the web app's book
recommendations. 

Using data like rating books from a user,
Recommendation Engine uses Machine Learning algorithms to provide a
user with highly personalized book recommendations.

<p style="color:white">The <b style="color:skyblue">&#128218; YourNextReads</b> is a web app built for book lovers with a Book Recommendation engine. A web app  uses a <b style="color: green">hybrid recommendation engine with different machine learning algorithms </b> to power web app's book recommendations. Using data like rating books from a user, Recommendation Engine uses Machine Learning algorithms to provide a user with highly personalized book recommendations.</p>
                                    <br>
                                    <p style="color:white">A hybrid recommendation system is the combination of two diffrent types of recommender systems: content-based filtering and collaborative filtering.</p>   
                                    <br>
                                    <p style="color:white">Firstly, <b style="color: green">&#11088; content-based filtering </b> is a method of recommending items by the similarity of the said items. For example, if I like the first book of The Hunger Games, then it gonna recommend me similar books such as Catching Fire (the second book of The Hunger Games), and Mockingjay (the third book of The Hunger Games). For content-based filtering, I implemented <b style="color: green">&#127775; cosine similarity metrics machine learning algorithm.</b></p>
                                    <br>
                                    <p style="color:white">Secondly, <b style="color: green">&#11088; collaborative filtering</b> is a method by which user ratings are used to determine user or item similarities. For instance, If there is a high correlation between users rating the first Lord of the Rings book and the second Lord of the Rings book, then they are deemed to be similar. For collaborative filtering, I have applied <b style="color: green">two machine learning algorithms called &#127775; K-means clustering and &#127775; Gaussian mixture modelling</b> to cluster the users and reach the best silhouette score.</p>
                                    <br>
                                    <p style = "color:white"><b style="color:skyblue">&#127752; Functionalities</b> that are successfully implemented in the system are:</p>
                                    <ul style = "color:white" >                
                                    <li>&#10024; Book recommendation</li>
                                    <li>&#10024; Give Ratings</li>
                                    <li>&#10024; View book details</li>
                                    <li>&#10024; Register, Log in & log out</li>
                                    <li>&#10024; Show rated books</li>
                                    <li>&#10024; Search book </li>
                                    </ul> 

# Technical Details 🔧
### Tech Stack : 
 - Front-end : HTML, CSS, Javascript, bootstrap
 - Technologies: Django framework, machine learning model
 - Databases/Data storage: MySQL
 - ML Libraries in python 3: NumPy, pandas, sklearn
 - Tools: Visual Studio Code, Jupyter Notebook, MySQL workbench, MySQL server

# To set up

The Project works seamlessly on Python version `3.10.2`

Fork the Repository or download zip file

If you don't have virtualenv already installed - `pip install virtualenv`

Create a new environment 

Install requirements - `pip install -r requirements.txt`

Open BookRack/settings.py
Set database and change password

Make Migrations - `python manage.py migrate`

`python manage.py runserver` - You're good to Go !!


# Functionalities

Functionalities that are successfully implemented in the system are:

 - Book recommendation
 - Give Ratings
 - View book details
 - Registration, Log in & log out
 - Show rated books
 - Search book

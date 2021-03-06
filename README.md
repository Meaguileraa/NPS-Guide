# National Park Service Guide :national_park:	
```sh
"Discover America's Story: The National Parks"
```

## About
NPS Guide is a site where users can view available activities at a given national park and select their preferred activities to add to a bucket list. The inspiration for my project stems from my passion for exploring national parks, where I save activities in my phone that I want to check out while I am there. NPS Guide serves as a perfect solution!

## API
[National Park Service API](https://www.nps.gov/subjects/developer/api-documentation.htm#/activities/parks)

## Tech Stack 
* Python 
* Flask
* PostgreSQL
* SQLAlchemy
* JavaScript 
* jQuery
* HTML
* Jinja
* CSS
* Bootstrap

## Features 
* New user registration using Bootstrap
* User functionality
    * Search a park of their choice
    * View the available activities at that given park
    * Save activities to an existing bucket list or create a new bucket list
    * Set a preferred date for these acivities to occur
    * Login and Logout


## Deployment
* Deployed via Lightsail on AWS
* Visit NPS Guide at [http://www.nps-guide.com/](http://www.nps-guide.com/)



## Installation

### Virtual Environment
Create a virtual environment to install requirements 

```sh
$ virtualenv
$ source env/bin/activate
```


### Prerequisites
All the prerequisites are in the requirements.txt file 

```sh
pip3 install -r requirements.txt
```

### Run Server 
```sh
python3 server.py
```



## Using NPS Guide
### 1. Register as a new user or login to your account
![](/static/imgs/login-register.gif?raw=true)


### 2. Choose a National Park 
![](/static/imgs/choose-park.png)

### 3. Select activity(s) that are available at that park to be added to a bucket list
![](/static/imgs/add-activities.gif?raw=true)

### 4. Once activity(s) are added to a bucket list you can update your planned date
![](/static/imgs/change-date.gif?raw=true)


### 5. In your profile you can view all of your bucket lists
![](/static/imgs/profile-page.png)


## Version 2.0 
* Rebuild frontend using React 
* Alphabetically sort parks list
* Replace dropdown menu on parks page with a search bar 


## Author 
Marissa Aguilera - *Initial work* - **[LinkedIn](https://www.linkedin.com/in/marissa-aguilera/)** **[GitHub](https://github.com/Meaguileraa)**


## Acknowledgments
* *Hackbright Instructors:* Marisa Gloor, Katrina Huber-Juma, Andrew Blum
* *Mentors:* Nakita Strangeways, Rachael Morton

**Thank you all for your endless support and guidance throughout the cohort!**


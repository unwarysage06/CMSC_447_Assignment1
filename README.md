<div id="top"></div>
<!-- ABOUT THE PROJECT -->

# Introduction

![Product Name Screen Shot][product-screenshot]

This is a Full-stack web application using React, NodeJs, Django, Python, JavaScript, SQLite, Leaflet, Chart.js, HTML, and CSS.  This is a website used to track various crimes in the city of Baltimore it allows the user to filter the crime type based on the location of the crime, type of crime, and date of crime committed. This software may be especially useful to certain users such as the police force, realtors and real-estate agents.

### Structure of the application

* On the homepage we use this page as a landing page and the user can access both the stats page and the about page either using the buttons on the top right-hand side of the screen, or they can press the blue button in the middle of the screen to take them to the stats page. Clicking the words "The Crime Site" on the top left-hand side of the screen will take the user back to the home page.
   ![Home]

* On the about page we use this page to describe our methodologies in how we built the website itself, how we acquired data for the stats page, and some use cases for how the site will be useful.
   ![About]

* The Final stats page is split into a 3 diffrent components:

   * A map with multiple methods of interaction, including clicking on diffrent crime types, zooming in and out. as well as moving around the globe.
      ![Map]


   * A filter which allows us to edit date ranges, change the crime type plus disctricts.
      ![Filter]


   * a plot chart, a graph and a bar graph that help visualize the data
      ![Charts]    

   <p align="right">(<a href="#top">back to top</a>)</p>

# System overview

From a system administrator perspective there are many upkeep and processes that need to be taken care of. in this section, we will go over the duties that a system administratior needs to be thoughtful of in this program.

### Background
This program uses a multitude of technologies, a system administrator needs to be mindful of how each one works, and make sure all processes are working accordingly, some of the most critical parts of this include:
   * Maintaining the current running backend system and front end system. make sure that all systems are running properly and communicating with each other at all times. we use bootstrap as a framework to maintain the systems, Django for the back end systems and react for the front end systems. These technologies must remain running as it is critical for the website.
   * Database is running and properly maintained. we are using SQLite for the database, a system administrator needs to be mindful that the database works.
   * Update and fix bugs accordingly
   * Monitor communication between the back and front end
   * Ither critical API's that a system administrator must keep an eye on include chart.js and leaflet.
   * A system administrator must also be aware that the ports the system is operating on are open and change ports if needed.
   * Report bugs and update any agile software boards that might be used in the project.
   * keep an eye on, and assign parts of the project to the team


##### Other Duties
   * Be mindful that a program might become corrupted. They should maintain a backup of the system, with multiple snapshots remaining on the backups.
   * Monitor system performances, make sure that there are no hardware or software limitations, and act accordingly if there are.
   * Keep an eye on the size of the program, if the program becomes too large for the system to handle, patching vulnerabilities and bugs will become much more difficult.
   * Be aware that the environments of the system are running and up to date as this can cause security vulnerbilities
   * The program and its subparts are in a reasonable location with easy access via a terminal if needed
   * Optimizing the program to work with as much hardware and browsers as possible



<!-- INSTALLATION AND HARDWARE -->

### Required Hardware and Software

The hardware requirements for the crime website is a machine that can identify and read x86 processes this can be a Linux, Windows or macOS machine. At least 4 GB of ram is recommended as there is a large amount of data within this project. Any 64 bit processor, and at least 5 gb of storage, as there will be download of new software as well as a ~1GB project.

This project was built with the frameworks and applications listed below. Installing and downloading the software below including any npm listed in this manual will be required for this aplication to work.

* [python](https://reactjs.org/)
* [React.js](https://reactjs.org/)
* [Bootstrap](https://getbootstrap.com)
* [Node JS](https://nodejs.org/en/)
* [Django](https://docs.djangoproject.com/en/4.0/)
* [SQLite](https://www.sqlite.org/docs.html)
* [Leaflet](https://leafletjs.com/reference.html)
* [Chart.js](https://www.chartjs.org/docs/latest/)

It is highly reccomended that you use and IDE for development, in this manual we will use VScode.

<!-- GETTING STARTED -->

### Getting Started

Start by downloading and installing Python, Node JS, SQLite, Django, leaflet, and Chart.js.

* [Python](https://www.python.org/downloads/)
* [Node JS](https://nodejs.org/en/)
* [React.js](https://reactjs.org/)
* [Bootstrap](https://getbootstrap.com)
* [Django](https://docs.djangoproject.com/en/4.0/)
* [SQLite](https://www.sqlite.org/docs.html)
* [Leaflet](https://leafletjs.com/reference.html)
* [Chart.js](https://www.chartjs.org/docs/latest/)

### Prerequisites

Make sure your Node is fully updated before running further npm commands.

* npm
  ```sh
  npm install npm@latest -g
  ```

### Backend installation

_Make sure this project directory is placed into a resonable place and use the terminal to interact with the application and installation._

1. Download Python: https://www.python.org/downloads/
2. Download node.js: https://nodejs.org/en/download/
3. Download SQLite: https://www.tutorialspoint.com/sqlite/sqlite_installation.htm
4. Before we continue, it is recommended you restart your pc at this point
5. Open a terminal environment  in order to install the next applications
6. Install Django

   ```sh
    pip install django
   ```
7. Install Django rest framework

   ```sh
    pip install djangorestframework
   ```
8. Install django CORS headers

   ```sh
    pip install django-cors-headers
   ```
9. Install SQLAlchemy

   ```sh
    pip install mysqlcleint
   ```

### Frontend installation

_Make sure this project directory is placed into a resonable place and use the terminal to interact with the application and installation._

1. Open a terminal and run the following commands
2. Install bootstrap (current latest version as of 5/18/2022, please check the website listed above for the latest version)
   ```sh
    npm i bootstrap@5.2.0-beta1
   ```
3. Install react
   ```sh
    npm install react
   ```
4. Install leaflet
   ```sh
    npm install react react-dom leaflet
    npm install react-leaflet
   ```
5. Install chart.js
   ```sh
    npm i chart.js
   ```

<!-- RUNNING THE PROJECT -->

### Routine Tasks

_Make sure this project directory is placed in a reasonable place and use the terminal to interact with the application and installation._

1. Open 2 separate terminals or command prompts
2. Open the A1 directory and type in the following command
3. In the first terminal, first Find your way to the project directory with the cd commands, enter your backend

   ```sh
    cd .\django\backend
   ```
4. Start the server

   ```sh
    python .\manage.py runserver
   ```
5. In the 2nd terminal, find your way to the project directory, and with the cd commands, enter your frontend

   ```sh
    cd frontend
   ```
6. Start the front end

   ```sh
    npm start
   ```

   Do not close these terminal windows

<!-- SUPPORT AND ADMINISTRATION -->

### Periodic administration

Check periodically if there is new data available and update the .csv file. While doing this, make sure to update any backups you have of the website. it is recommended you keep at least 1 backup, as files and drives can easily fail or reach an unusable state.

### User Support

For any issues, contact one of the team members via Microsoft teams or email. The email usernames will be listed below (all Microsoft team accounts use the same emails). We can also accommodate urgent messaging if needed.

Resources for the website can be found in the documentation for each of the technologies used:

* [Python](https://docs.python.org/3/)
* [Node JS](https://nodejs.org/en/docs/)
* [React.js](https://reactjs.org/docs/getting-started.html)
* [Bootstrap](https://getbootstrap.com/docs/4.1/getting-started/introduction/)
* [Django](https://docs.djangoproject.com/en/4.0/)
* [SQLite](https://www.sqlite.org/docs.html)
* [Leaflet](https://leafletjs.com/reference.html)
* [Chart.js](https://www.chartjs.org/docs/latest/)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- TROUBLESHOOTING -->

# Dealing with errors

While this project has been extensively tested with both white box and black box methodologies of testing. We are aware that we can't account for every system configuration, browser, or a multitude of other things such as operating system or resolution. Because of this, please use this section as a guide for troubleshooting common errors and issues.

#### error messages

* Missing module - if your error stems from the "import" section of a codeblock, please refer to the installation section of the system requirements, and make sure that all of the software requirements are installed.
* Run "pip install --upgrade pip" if any of the installs are giving errors.
* Missing module - If you have made sure all installs are working and still getting an error, make sure your interpreter is set properly, in this instance, we will do this in the Visual Studio code IDE:

  1. Firstly, we will open a python file, in this case. open the manage.py python file
     ![inter-open]
  2. Select the python version in the bottom right, in this case, I would select "3.10.64-bit (windows store)
     ![inter-select]
  3. A menu will open at the top middle, select the interpreter where your python is saved
     ![inter-set]
* Python missing - if your error stems from python commands not being recognized, make sure that python is included in your environment variables. We will give a tutorial on how to do this in windows.

  1. First start by searching for "virtual environment in the windows home menu, then select the control panel option as shown below
     ![venv-search]
  2. In the system properties menu that opens up, select "Environment Variables"
     ![venv-click]
  3. In the environment variables menu, double click on "path."
     ![venv-path]
  4. Finally, add the location for your python interpereter.
     ![venv-add]

#### Known limitations

* Low framerate - Low framrate issues stem from the large database, please make sure the system meets all requirements.
* Large database - This is a limiation with the code. Because the database is so large, please dont overload it by selecting a large date filter. Loading hundreds of thousands of datasets will take some time especally on lower end machines.
* Bar graph - Sadly, if you want to compare 2 bar graphs up to each other, this is currently not possible with our database. However, it is a feature we would like to implement in the future. Please use the pie chart to visually compare 2 data sets.
* graph - for the same reason as the bar graph, we are only able to include one graph a at a time. If you would like to compare these data sets, please use the pie chart.
* Other errors - Please understand that it is very difficult for us to account for every error, there are thousands of browsers, operating systems and ways of using a website. If you run into any error, please refer to the Support section or contact a project author.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CREDITS -->

# Credits

Hamza Adnan - hamzaa1@umbc.edu
Ulfina Wakjira - uwakjir1@umbc.edu
Azeem Shuja - ashuja1@umbc.edu
Mustafa Abduljaleel - mustafa8@umbc.edu
Magdi Hassanein - magdih1@umbc.edu

<!-- MARKDOWN LINKS & IMAGES -->

<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[product-screenshot]: https://i.imgur.com/LLY2vIl.png
[venv-search]: https://i.imgur.com/mCeXtam.png
[venv-click]: https://i.imgur.com/WegfmDi.png
[venv-path]: https://i.imgur.com/WlouopR.png
[venv-add]: https://i.imgur.com/3lf8Ju9.png
[inter-open]: https://media.discordapp.net/attachments/730274179072524308/976665299476680734/unknown.png
[inter-select]: https://media.discordapp.net/attachments/730274179072524308/976665299703197706/unknown.png
[inter-set]: https://media.discordapp.net/attachments/730274179072524308/976665543207690321/unknown.png
[Home]: https://media3.giphy.com/media/UPQojziNk4A6sMRzzZ/giphy.gif?cid=790b76111b9c829e175bbcb19cf8ef9725c0e5f6d765e681&rid=giphy.gif
[Charts]: https://media0.giphy.com/media/ESbIPmcbjVAds9OJ5v/giphy.gif
[About]: https://media2.giphy.com/media/DrTJjWhV32dHzO6psU/giphy.gif?cid=790b7611d7675a724748dbdfcea9d6240413c587e8ccc3c7&rid=giphy.gif
[Filter]: https://media3.giphy.com/media/tC96nHLbkf2LTAtEbu/giphy.gif
[Map]: https://media1.giphy.com/media/XvPxqoeYRqcjCFoE1E/giphy.gif

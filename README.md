# Travel-Safe

## Scope 
Travel Safe aims to help with travel decisions with the aid of weather predicting software application. The objective is to use a detailed database to draw relations between the input statistics that will deliver a system to assist the user with choosing their future travel location. The system will offer a user-friendly Android based application that allows users to search a specific location's weather status. The application will provide information regarding the occurrence probability of extreme and unwanted weather conditions. The product’s main goal is providing the user with beforehand information to aid in the traveling decisions that are affected by unsettling weather changes.

## Algorithms Used
<ul>
 <li> Merge sort was used to stort the hazards by month so that the search data can be used for binary search to find the specific hazards occuring at a month </li>
 <li> Dijkstra's algorithm was used to find the shortest path between states using the frequency of hazards within a specified state and month as weights. </li>
</ul>

## Installation and Configuration of Application
In order to run this application, an IDE for Android development should be installed. It is recommended to use Android Studio. The guide will be based on Android Studio.
<ol>
 <li>Plug in an Android device to the Computer via USB</li>
 <li>Open the "Settings" on the device</li>
 <li>Tap on "About Phone"</li>
 <li>Find "Build Number"</li>
 <li>Tap on "Build Number" a total of 7 times in quick succession. A pop-up message stating "You are now a developer!" should appear if done corrrectly</li>
 <li>Go back to "Settings:</li>
 <li>Scroll down to the bottom to find "Developer Options"</li>
 <li>Turn on "USB Debugging"</li>
 <li>Dialog appears asking permission for USB Debugging ("Allow USB Debugging?"). Check "Always allow from this computer" and hit "OK"</li>
 <li>Import this entire project into the IDE of your choice</li>
 <li>Once the device is discovered by Android Studio, click the "Run" button on the top left of the task bar, ensuring that you are choosing the correct device when running</li>
 <li>An installation page will appear on the device. Follow the guidelines to finish the installation.</li>
</ol>

## How To Use the Application
The application is now ready after you finish the installation process. Make sure you are connected to the
Internet and you are in a region where Google Play services are available before running the app.

Once it is all set up, the app will direct you into the main page of Travel Safe and a pop up message will
notify you whether connection is successful or not. The main page consists of a title and three search
buttons that allows the user to search by time and location, find the best time for travelling to a particular
location, and find the safest path. It is up to the user to decide which one they want to prioritize and they
can simply tap it to start the search. Once the required information is entered, one of the options will be displayed: a map with icons indicating the type of disaster that have happened in the state at that time, a ranking of the Top 3 times to travel based on the location, or a map showing the safest path to travel. The user can take the results as a guideline to choose the routes for their trip

<span style="text-decoration:underline;">Topic</span>

Analysis of running and bicycle activities. The main questions to be answered are the following:



*   In which countries are these activities most popular?
*   What is the average duration by type of activity and country?
*   What seasonality do they show during the year?
*   Are these activities affected by weather conditions?
*   Most popular activity names
*   Average calories burnt by activity per minute
*   At what times of the day do people mostly practice them?
*   Do these activities have an impact on people’s main health indicators?
*   Is there any relation at all between the activity in each country and its performance in the olympic games?

<span style="text-decoration:underline;">Sources of information</span>

1 [Strava API](https://developers.strava.com/docs/reference/#api-Athletes-getStats) : Strava API usage is limited on a per-application basis using both a 15-minute and daily request limit. The default rate limit allows 100 requests every 15 minutes, with up to 1,000 requests per day

2 [Weather API](https://www.weatherbit.io/api)

3 [Olympic games csv](https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results/data) (_Also info about cycling [here](https://www.procyclingstats.com/))_

4 [Health datasets csv ](https://www.who.int/gho/database/en/) 

<span style="text-decoration:underline;">Github organization</span>

Folders



*   .gitignore
    *   MacOs
    *   Microsoft 
    *   Jupyter Notebook
*   Sources:
    *   Raw data
    *   Any other file from the internet
    *   **_Don’t edit or remove these files_**
*   Code:
    *   Folder for each user: Paula, Sander and Javier
*   Outputs:
    *   Images
    *   Report
    *   Presentation

<span style="text-decoration:underline;">Code structure</span>


<table>
  <tr>
   <td>Type
   </td>
   <td>Structure
   </td>
  </tr>
  <tr>
   <td>Variable names
   </td>
   <td>
<ul>

<li>No capital letters

<li>Underscore to separate words
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Function names 
   </td>
   <td>Every function starts with a capital letter
   </td>
  </tr>
  <tr>
   <td>Common Libraries / <em>Add here the name of libraries if we come up with a new one + in slack. </em>
   </td>
   <td>pd (pandas)
<p>
re
<p>
json 
<p>
np (numpy)
<p>
requests
   </td>
  </tr>
  <tr>
   <td>Title and Markdown style 
   </td>
   <td>## Titlle 
<p>
### Subtitle 
<p>
Text
   </td>
  </tr>
  <tr>
   <td>Always comment our code 
   </td>
   <td>Always explain what we are doing to make it readable by others
   </td>
  </tr>
</table>
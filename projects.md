---
title: Personal Projects
layout: page
style: page
---


I recently heard [Harper Reed](https://en.wikipedia.org/wiki/Harper_Reed) speak at [Think Chicago](http://www.thinkchicago.net). I thought his [quantifed self idea](http://harperreed.com/#/) was awesome so I made my own. 

## Tom Quantified (Yesterday)
* Amount of Sleep: 8 hours, 16 minutes
* Amount walked: 5.2 miles 
* Time Spent on Spotify: 2 hours, 39 minutes


## A Day in the Life

 I was curious how I spent my days. Using the Fitbit API, Spotify API, and work schedule I quantitatively broke it down. Below is a graph I created in R using ggplot2.  

<img src="https://s3-us-west-2.amazonaws.com/files.tomzidar.com/carousel/unkown.png" alt="DayintheLife" >

<!-- # Google Analytics
```html
<body>
  <div id="chart_div">
    <script type="text/javascript" src="https://www.google.com/jsapi"></script>
    <script type="text/javascript">

      // Load the Visualization API and the piechart package.
      google.load('visualization', '1.0', {'packages':['corechart']});

      // Set a callback to run when the Google Visualization API is loaded.
      google.setOnLoadCallback(drawChart);

      // Callback that creates and populates a data table,
      // instantiates the pie chart, passes in the data and
      // draws it.
      function drawChart() {

        // Create the data table.
        var data = new google.visualization.DataTable();
        data.addColumn('string', 'User Type');
        data.addColumn('number', 'Sessions');
        data.addRows([
          ['New Visitor', 369],
          ['Returning Visitor', 64]
        ]);

        // Set chart options
        var options = {'title':'How Many People Have Seen My Site?',
                       'width':400,
                       'height':300};

        // Instantiate and draw our chart, passing in some options.
        var chart = new google.visualization.PieChart(document.getElementById('chart_div'));
        chart.draw(data, options);
      }
    </script>
</div>
</body>
``` -->

# My Google Analytics for this Site

I created an R shiny application for my Uber job interview. Pardon the aesthetics 

<iframe src="https://tzidar.shinyapps.io/Toms_Google_Analytics/" width="800" height="550"></iframe>


# Music I listen to while I'm working

<iframe src="https://embed.spotify.com/?uri=spotify:track:6WHNJHwOZSi42BSBVEQmso" 
width="300" height="380" frameborder="0" allowtransparency="true"></iframe>

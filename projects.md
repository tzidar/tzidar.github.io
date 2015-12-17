---
title: Personal Projects
layout: page
style: page
---


I recently heard [Harper Reed](http://harperreed.com/#/) speak at [Think Chicago](http://www.thinkchicago.net). I thought the idea was awesome so I copied it. 
## Tom Quantified (Yesterday)
* Age: 21
* Amount of Sleep: 7 hours, 31 minutes
* Amount walked: 3.7 miles 
* Time Spent on Spotify: 2 hours, 19 minutes


## A Day in the Life

 I was curious how I spent my days. Using the Fitbit API, Spotify API, and class schedule I quantitatively broke it down. Below is a graph I created using the Seaborn library within Python.  

<img src="../../public/img/Unknown.png" alt="DayintheLife" >

# Google Analytics
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
```

# Music I listen to while I'm working

<div class="row" id="spotify"> 
	<p>
<iframe src="https://embed.spotify.com/?uri=spotify:track:2mP19NOAs1eNi9o6K8ngwt" 
width="300" height="380" frameborder="0" allowtransparency="true"></iframe>
	</p>
</div>
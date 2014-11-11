ZepplinMap
==========

##What is this##
ZepplinMap is a simple code snippet to use if you want to add a Google Map with multiple markers on your web application

##How does it work ?##
Simply call it's constructor with your DOM that should contains the map and the list of pins to place in it
```
  var pins=[
      {
      title : "Bell center",
      city : "Montréal",
      zipCode : "H4B 5G0",
      address : "1909 Avenue des Canadiens-de-Montréal",
      latitude : 45.496067,
      longitude : -73.569315
      },
  ]

  var zepplinMap = new ZepplinMap($("#map"), pins, {});
```

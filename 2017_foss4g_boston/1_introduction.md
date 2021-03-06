# 1] Workshop introduction

Slides: http://slides.com/bertt/workshop-sensorthings-and-gost

In this workshop, you will learn the basics of working with GOST.

GOST is an OGC compliant implementation of the <a href= "http://docs.opengeospatial.org/is/15-078r6/15-078r6.html">OGC SensorThings API</a> written in <a href="https://golang.org/">Golang</a>.

For more background information of SensorThings API, please read <a href="https://en.wikipedia.org/wiki/SensorThings_API">SensorThings API on Wikipedia</a>. 

You will learn practical things like:

- Installing GOST using Docker

- Configuring GOST with your sensors

- Using Node-RED to get data into GOST

- Using MQTT with GOST for Publish/Subscribe

- Using OASIS OData filtering capabilities (spatial and non-spatial)

Finally there is a bonus exercise about realtime visualizing Boston bike-sharing information using GOST.

Before starting the workshop, lets create a workshop directory to store the various workshop files:

```
$ mkdir gost_workshop
$ cd gost_workshop
```

Now you're ready to start with installing <a href="2_installation.md">GOST</a>

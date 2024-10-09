# Ghackk-Tech-Assignment for software development intern role
Improving on the performance of this [webpage](https://animemangatoon.com/webtoon-kpop-how-these-two-korean-media-impact-each-other/).

The following methods can be used to improve the webpage performance.

## Making lightweight graphics
The first impression of the webpage is the title picture, which takes a lot of time to load. To improve the loading time, appropriate image types such as WebP can be used to ensure quick loading without loss of quality. Furthermore, image compression techniques can be utilised to enhance load speeds.

## Making the code lightweight
In case the code for the webpage is a big file, rendering it across a network is a task. To optimise loading time, the code can be split into smaller, lightweight segments to load across the network and render the webpage quickly. 

## Implementing 'lazy loading'
This procedure only loads a certain element of the webpage when it is in the user's view. This helps render the relevant content very quickly and enhances the user experience by leading to lesser wait times to generate the content that is meant to be read by the user. 

## Using caching for frequent visitors
Using browser-side caching methods to hold rendering data for frequent visitors may help reduce wait times. 

## Using Content Delivery Networks(CDN)
CDN can be used to upload and render content such as images, and CSS stylings a lot quicker as compared to a conventional fetch and load process. This can help reduce latency and improve load speed.

# Udagram Image Filtering Microservice

Udagram is a simple cloud application developed alongside the Udacity Cloud Engineering Nanodegree. It allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice.

## Tasks

### Github Link:

`https://github.com/Thomas-Max99/udacity-image-filter-app`

### How to run this project ?
After cloning the project, open a terminal and run:

`npm i`

After installing the dependencies, run the development server with 

`npm run dev`

The API to apply a filter to the image, will be available at the URL: http://localhost:8082/filteredimage

To test you must pass an image URL, for example:

`http://localhost:8082/filteredimage?image_url=https://i.ibb.co/sqNRPsQ/nft-art-logo-design-template-7bc8ffc9ccb4d7a91524b1bd36100d19-screen.jpg`

### Image before filter

<img src="https://i.ibb.co/sqNRPsQ/nft-art-logo-design-template-7bc8ffc9ccb4d7a91524b1bd36100d19-screen.jpg" alt="imagebeforefilter" border="0">

### Image after filter


<img src="https://i.ibb.co/M77q6gX/filteredimage.jpg" alt="filteredimage" border="0">


## AWS Elastic Beanstack URL
 
## Elastic BeanStalck App URL: 

`http://image-filter-dev-dev2.us-west-2.elasticbeanstalk.com`

## EB_URL: 

`image-filter-dev-dev2.us-west-2.elasticbeanstalk.com`
## URL with endpoint

http://image-filter-dev-dev2.us-west-2.elasticbeanstalk.com/filteredimage/?image_url=https://i.ibb.co/sqNRPsQ/nft-art-logo-design-template-7bc8ffc9ccb4d7a91524b1bd36100d19-screen.jpg

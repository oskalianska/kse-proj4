# Image Analysis Service on Google Cloud

Table of contents:

1. Google Cloud package
2. First problem statement and dataset description
3. Second problem statement and dataset description

## 1. Google Cloud Vision AI

Derive insights from your images in the cloud or at the edge with AutoML Vision or use pre-trained Vision API models to detect emotion, understand text, and more.
Detect objects automatically: Detect and classify multiple objects including the location of each object within the image. Learn more about object detection with Vision API and AutoML Vision.
Gain intelligence at the edge: Use AutoML Vision Edge to build and deploy fast, high-accuracy models to classify images or detect objects at the edge, and trigger real-time actions based on local data. AutoML Vision Edge supports a variety of edge devices where resources are constrained and latency is critical. Learn more.
Understand text and act on it: Vision API uses OCR to detect text within images in more than 50 languages and various file types. It’s also part of Document Understanding AI, which lets you process millions of documents quickly and automate business workflows.
Detect explicit content: Vision API can review your images using Safe Search, and estimate the likelihood that any given image includes adult content, violence, and more.


## 2. First problem statement (Text Recognition) :

We want all our employees to not use company benefits in an unfair way and not provide fake documents. (Vision)

Today we have too many situations when employees have work trips and submit their expenses with tens of receipts from each person. Many companies do not allow submitting alcohol in their spending. But everybody knows that nobody will be able to check it in big corporations. If we ignore this problem; resources will need to increase and people will use this situation for their profit. (Issue Statement)

We will use image recognition to detect if any alcoholic drinks in receipts to help us improve our processes. (Method)

Dataset description: I created a custom receipts dataset, it consists of 20 images with 2 alcoholic receipts positive images and 18 non-alcoholic receipts images. Collection of receipts images is a tedious, time consuming and downright painful task hence the low image count.


## 3. Second problem statement (Landmark Recognition) :

We want to find out all the names of places we’ve been even we did not have the internet to check these places or write down street names etc. (Vision)

Nowadays, we travel a lot in different countries. Sometimes we do not have the opportunity to buy new sim-card with the internet or connect to wifi to check some information online. So we lose many photos and don`t know all the information about the places that we visited and can not tell the whole story for our friends, for example. (Issue Statement)

We will use image recognition to detect the names of places to help us know all about the places that we’ve seen. (Method)

Dataset description: I created a custom dataset, it consists of 20 images with different places. So as we want just to test this idea with place recognitions, I added places from unlike places.

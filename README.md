
# Write a Blog Post

This repository contains the files for analyzing the data used in a Medium Blog Post: [What Airbnb data can tell about Rio De Janeiro](https://medium.com/@gasparitiago/what-airbnb-data-can-tell-about-rio-de-janeiro-4068f9d6becf). 

## Installations

To install all the dependencies of the project, just use pip:

```
pip install requirements.txt
```

## The CRISP-DM Process (Cross Industry Process for Data Mining)

The lessons leading up to the first project are about helping you go through CRISP-DM in practice from start to finish.

In this project I'm going through CRISP-DM using the followings steps:

- Business Understanding
- Data Understanding
- Prepare Data
- Data Modeling
- Evaluate the Results

**Important Note:** All of the CRISP-DM steps used are described directly in the `Analyze.ipynb` file.

## Project Motivation

In this repository I'm sharing the files used to finish the first project of the *Udacity Nanodegree: Become a Data Scientist*.

This project consists in just one Python Notebook called `Analyze.ipynb` that was used to get different information from the Rio de Janeiro Airbnb data.

It includes also the csv file used in the analysis and an image used to improve one of the analysis.

In this file, the data of Airbnb was used to answer three questions:

> Does the GeoLocation of a property affect its price?

> What amenities I can expect when going to Rio?

> A new host can estimate the price of a room just by describing it (Without any further research)?

## Summary of the results

Answering the above question briefly:

- Does the GeoLocation of a property affect its price?

It seems that the geolocation doesn't affect the price of an Airbnb room in Rio De Janeiro: You can visit Rio paying less and stay closer to a person that is visiting Rio paying more for a room.

- What amenities I can expect when going to Rio?

Besides some essential amenities, rooms in Rio are popular to allow long-term stays, having Air Conditioning, and Wifi.

- A new host can estimate the price of a room just by describing it (Without any further research)?

Yes and No. It's possible to estimate the price, but just using a Linear Regression Model and few of the columns available, the result is not so good as expected.

### Important Note: 

A further analysis of the data, including the answer of these three questions were published in Medium, in the following link: https://medium.com/@gasparitiago/what-airbnb-data-can-tell-about-rio-de-janeiro-4068f9d6becf

## Files Description
- Analyze.ipynb: Notebook containing the code used for the data analysis.
- listings.csv: Dataset on csv format of the Rio De Janeiro Airbnb listings.
- map.png: Map image used in one of the analysis to verify if the geolocation of each room affects the price of the offer.

## Acknowledgement

I would like to thank Airbnb to make the dataset available used in this work.

## Licensing

The code provided is under BSD 3-Clause License.


# ghibli-flickr-scraper

A scraper to create a dataset of ghibli images and real life photos

## The first step is to get images from ghibli.jp

For that we simply use the urls to get all the images for each given movie

## Second step is getting images from Flickr

We use the Flickr API to get latest images and save them to disk.

## Last step (optional): generating TFREC files

In order to access the image faster using Kaggle's TCP we generate TFREC files for the two datasets.

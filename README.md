# Personal Listing Tracker

A small private tool that reads public, active Etsy listings through the
[Etsy Open API v3](https://developers.etsy.com/documentation/) and checks them against market
prices from other sources. When a listing looks priced well below its typical value, it sends me a
private notification so I can decide whether to buy it myself.

## What it does

- Reads public listing data only: title, price, shipping cost, photo and listing URL.
- Skips listings it has already seen, so I don't get duplicate notifications.
- Sends a private notification to me when a listing looks underpriced.

## What it does not do

- It does not post, edit, favorite or buy anything on Etsy.
- It does not access any shop, buyer or account data.
- It does not store listing content beyond the short-term records needed to avoid duplicate alerts.

## Usage and limits

This is a personal tool for my own use. It makes a low volume of requests and stays within Etsy's
rate limits. It is not a public service and has no users other than me.

Etsy is a trademark of Etsy, Inc. This project is not affiliated with or endorsed by Etsy.

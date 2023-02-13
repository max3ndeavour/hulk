# HULK Brute Force

Author: Max endeavour
Date: 17.11.2022

This is a transposition of the hulk tool found here:
https://packetstormsecurity.com/files/112856/HULK-Http-Unbearable-Load-King.html

Into a python3 version.

## Prerequisites
1. Python3
2. Internet connection

## How to Use it
1. Install requirements from requirements.txt

`pip install -r requirements.txt`

2. run the tool:

`python3 hulk.py [https://target-url.org]`

## Changes:
1. Typos due to changes in python3 (prints etc.)
2. Usage of requests ti chect the url
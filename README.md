# AI Stylist Tool 

A tool to help users in their fashion journey!

## Table of Contents

- [Overview](#overview)
  - [Purpose](#purpose)
  - [Team](#team)
- [Getting Started And Contributing](#getting-started-and-contributing)

## Overview

### Purpose

This is a project for Rodrigo Canaan's Artificial Intelligence (CSC 480) class. This project aims to help users with their personal style by proposing an AI-generated Personal Styling Assistant. By utilizing natural language processing and image recognition technologies, the system will offer tailored fashion recommendations, considering individual preferences, body types, and current trends. Our goal is to enhance the personal styling industry by creating a unique and personalized experience for all users. 

### Team

Poornima Godavarthy, Katy Hosokawa, Nidhi Raviprasad, and Ananya Thapar

### How to develop locally

1. git clone this repository

2.  Make sure the following files are included - ai_personal_stylist.py, styles.csv, and the images folder with images 1163.jpg to 600.jpg 

3. Install dependencies - Pillow >= 2.0 and Tensorflow = 2.15. We running the following commands: pip install Pillow and pip install Tensorflow.

3. Run python3 ai_personal_stylist.py

4. Input your preferences into the quiz in the following order: Gender, Base Colour, Season, and Usage.

5. Rank your overall satisfaction with the recommendation out of 10. If your satisfaction level is less than 6, it will attempt to generate a new recommendation that better suits your preferences until you are satisfied.

6. Rank your satisfaction in each category. 

7. Congrats, you have a new outfit! Good luck on your fashion journey!

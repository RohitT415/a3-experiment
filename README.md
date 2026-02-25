# A3 Experiment

**Team Granite: Max McCalla, Rachel Conca, Elias Montas, and Rohit Tallapragada**

*Experiment link: https://maxmccalla.github.io/CS4804-ReVisIt/*

*ReVISit Fork: https://github.com/MaxMcCalla/CS4804-ReVisIt*

*Results Visualization: 

## Introduction

For our project, we wanted to analyze perceptual differences in different styles of bar charts since bar charts are one of the most commonly used methods of data visualization and have many different variations on how they can appear.

Sticking with the general premise of the Cleaveland McGill experiments, we specifically wanted to see if different styles of bar charts impacted subjects' ability to determine the ratios between two differently sized bars. We focused on three different styles of bar charts for this assignment: normal bar chart (where all the bars rest on the x-axis and go upward), diverging bar chart (where all the bars rest on the x-axis but go both up and down), and stacked bar charts (where all the bars are stacked into one bar).

## Setting Up Our Experiment

We decided to use ReVISit for our project as the program is readily available via GitHub and can be confirgured to randomize trials, calculate error and other relevant statistics, and compiling the results into CSV form for easy analysis. We used the D3 library to generate our stimuli (various bar charts) before uploading those to our forked ReVISit repository.

We generated 20 variations of each type of bar chart (normal, diverging, and stacked), randomly marking two of the bars on each. After selecting two of the bars, we calculated what percentage of the larger bar the smaller bar would take up (ex. if the large bar was 5 units and the smaller bar was 3 units, the percentage would be 60% since 3 is 60% of 5).

When completing the experiment, participants would have to move a slider to indicate what percentage of the larger bar the smaller bar would take up. After submitting a response, our program compares the user response to the "true" response and calculates the absolute error and log error of their trial.

## Gathering Data

Once the site was all set up, we hosted our experiment using GitHub Pages and sent it out to various group chats to entice our friends to particpate. Members of the group also did the experiment ourselves for extra data. We weren't able to set up a database to collect responses, so we had each participant download their CSV results to send to a group member who then uploaded them to the `results` folder on the ReVISit repository. In total, we recieved 13 participants who completed our study.

Once all the participants had completed the experiment and sent their results to the group, we compiled them into a single CSV file that we used for analysis.


## Inspiration
The team was inspired by the popular game "Wordle". We wanted to create a fun game that could be played daily by everyone around the world which would also get people to start conversations about songs that they like to listen to.

## What it does
Musicle is a game played only once per day. The goal of the game is for the player to guess the daily song with as little amount of guesses as possible. Starting with only two seconds of listening time, with each wrong guess the player is exposed to a longer snippet of the song. Statistics are collected with each game to show the player how wide their music repertoire is

## How we built it
Musicle was built with a combination of multiple frameworks and APIs.

The Spotify API is used to query the global Spotify library for the daily song and also allows users to search for the daily song  
Firebase was used to host a list of daily songs. Song IDs are stored in a list and the app finds the daily song by using the current day number (counted from 01/01/2000)  
Apple's AVFoundation framework is used for playing the preview of the daily song  
UIKit is used for the app layout and animations  
Custom frameworks built by team members  
Accomplishments that we're proud of  
All team members are proud to announce that they have a 95%+ success rate in finding the daily song!

## What we learned
How to integrate Firebase into our project  
How to fetch data from APIs  
How to play audio on iOS devices  
How to make display-linked animations  
What's next for Musicle  
The AppStore!!!

## Built With
avfoundation  
firebase  
love  
spotify  
uikit  

See More Info Here: https://devpost.com/software/musicle

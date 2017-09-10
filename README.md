# Boulder-WeatherCheck

## Background

<p class='util--hide'>Welcome to the “Boulder-Weathercheck” program by [me] Richard Burd!  I am a student at the Flatiron School and this is my submission for <a href='https://github.com/learn-co-students/oo-student-scraper-v-000'>this project here</a> on Learn.co.</p>

## About This Program

The purpose of this program is to check the Boulder Colorado weather and see if it's OK to go outside.  I could check the weather online but then I have to look at the complete hourly forecast for the entire day; this program just checks a specific timeframe that the user specifies so the user only sees weather for that time-frame, and nothing more.  The user can also specify the weather conditions they're willing to tolerate and will be told whether or not the weather conforms to those conditions the user finds tolerable; the objective is to get a quick answer on whether or not the user wants to go outside for exercise, or stay indoors. 

## Install instructions

You will need Ruby installed on your machine to run this program; simply fork a copy of this repo onto your machine and run the `boulder-weathercheck` file in the `bin` directory to execute the program, follow the instructions on the command line interface to enter data and receive results.

### Project Structure

```
├── README.md
├── bin
│   └── boulder-weathercheck
├── config
│   └── environment.rb
├── lib
    ├── engine
        ├── data_query.rb
        └── check_weather.rb
    ├── parameters
        ├── weather_parameters.rb
        └── modules.rb

    ├── data_scraper.rb
    ├── data_requester.rb
    ├── cli.rb
    └── weather_database.rb
```

## Contributors Guide

There are three GitHub accounts contributing to this project; they are all me [I promise] and will be referred to herein as “Red-Burd,” “Green-Burd,” and “Blue-Burd” commensurate with the avatar icons for each account.  My objective in using three accounts is to experiment with (and learn about) GitHub’s multi-user functionality; although this is the whole point of GitHub, all of my Flatiron School projects (to date) have involved only one user (me) submitting to a repo. I want to try & push GitHub to its limits in terms of seeing how it handles multiple users trying to submit conflicting code at the same time, the purpose of all this is to turn me into a GitHub master.  If you would like to contribute to the project as well, go ahead and submit a pull request, but I won’t incorporate any of your code until I’ve been graded on this assignment...anything else would be cheating.

## Notes for My Instructor

<p class='util--hide'> I started writing the URL scraping code on a single ruby file several weeks ago just to play around with Nokogiri a bit; that single ruby file (believe it or not) evolved into the whole program; I never created a Git Repo or setup a proper working environment because I wasn’t that comfortable with GitHub to be honest.  My strategy was to first get all the code working correctly first, then make a proper Git repo and do some refactoring along the way.  The tool I used to organize the whole thing was my process-flow illustration’ both the illustration and the original (fully working) ruby file of the fully-working program are <a href='https://drive.google.com/open?id=0B4e44pJ1yCAtRjdXcWNMaG56bDQ'>available here</a> on my google drive.</p>

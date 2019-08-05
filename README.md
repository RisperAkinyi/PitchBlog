# Pitch Blog

## Description
This is  an application that allows users to submit their one minute pitches and other users will vote on them and leave comments to give their feedback on them.
 

## user stories
* view pitches
* login
* pitch
* downvote and upvote
* view personal pitches on profile
* comment on pitches
## BDD
| Behavior           | Input                 | Outcome                            |
| -------------------|-----------------------| -----------------------------------|
| request page       | click horuku link url | view othr pitches  & vote          |
| click on a pitch   |                       | vote/comment                       |
| sign in/up         | details pass & user   | view,pitch & comment               |


## Setup/Installation Requirements
* Internet access
* git clone https://github.com/RisperAkinyi/best-pitch
* $ cd into pitch-perfect
* $ python3.6 -m venv virtual (install virtual environment)
* $ source virtual/bin/activate
* $ python3.6 -m pip install -r requirements.txt (install all dependencies)
* Inside the manage.py module change the config_name parameter from 'production' to 'development' ie app = * create_app('production') should be app = create_app('development')
* $ ./start.sh
* or click on this link and follow the steps in the BDD.





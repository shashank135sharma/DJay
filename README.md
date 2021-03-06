## Inspiration
At clubs and house parties, when a DJ is hired, people often go up to the DJ and request a song to be played. But song selection shouldn't be the choice of one person. After all, the party is for everyone. We wanted to develop a way for the people to efficiently select their playlist, and allow the DJ to interact with it easily.

## What it does
deeJay implements a bidding system to request songs. The more bid points a song has, the sooner the song will play. The people are given an alotted number of points at the start of the party and can bid as many points as they want on songs of their choice throughout the party, simply by tweeting. The DJ can switch songs and control the volume with simple hand gestures.

## How we built it
The bidding system is implemented using Capital One's Nesse API. The points are first given and emulated by the creation of a checking account, from which you can withdraw funds when a bid is placed. In addition, if a song request is liked, bid points are awarded to the user who made the request. This is modeled by a deposit. With Bose, the DJ has an elevated experience of controlling the music. Because of Bose's SoundTouch enabled speakers, we are able to interact with the speaker using hardware such as the Pebble. Twitter allows deeJay to be easy to use for the people. There's no app to be installed, no account to be made, all thanks to Twitter. Solely by tweeting, the people can make their bids and requests to the DJ and listen to their music of choice. Everything was interfaced using a Node.js server.

## Challenges we ran into
It took a long time to program the Pebble to correctly recognize the hand gestures made by the DJ. The sheer amount of accelerometer data we were receiving was difficult to process, but after sifting through x, y, and z values, we were able to recognize gestures.

## Accomplishments that we're proud of
Allowing the DJ to control a speaker system with the motion of his/her hands is something we are definitely proud of, as this provides and new and easy experience for the DJ.

## What we learned
By building deeJay, we learned how to use checking accounts with Capital One's Nessie API. We also learned how to use Bose's SoundTouch API to control a home or club speaker system.

## What's next for deeJay
We hope to get input from real DJs and users to better the party experience.


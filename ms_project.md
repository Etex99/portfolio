# MS Project

Unity 3D game prototype with AR elements and location-based gameplay. 

## The Project

The project target was to design and develop a serious game to help students seek healthier indoor air at the University of Oulu Linnanmaa campus. A prototype was developed for our customer, Ikune Labs, as part of the "R&D Project"- course included in the Master of Information Processing Science degree programme.

The team consisted of 4 students including myself. Work was carried out in Scrum sprints and the team practiced professional use of version control in a team setting.

My roles were lead game designer and developer.

## Key Results

* Novel game design for a serious game related to indoor air quality.
* A functional prototype developed with Unity 3D game engine.

Unfortunately this Git repository is private. 
You may view footage of the prototype via this [link to a shared Mp4 file on Google Drive.](https://drive.google.com/file/d/16wGT755DbYcSrU631NnRa2E02A-QaAmj/view?usp=sharing).
Bear in mind the idle nature of the game and that the app is running on a weak budget phone. It is slow and boring to watch.

## My Contribution

* Game design documentation.
* Implementations of numerous basic core game mechanics.
* Sensor data fetching via MQTT.
* Ensuring comprehensive design and code documentation.
* Assisting my team on Unity 3D development.

## Technologies & Tools

* Unity 3D
* C#
* MQTT (M2MQTT)
* Jira
* Git
* Doxygen

## Reflection

First thing I would highlight is the organizational tasks I took upon myself during this project. As I was the only person on the team with experience developing with Unity 3D, I offered great assistance to my teammates. I helped each one get quickly started with development by ensuring understanding of basic concepts and quirks unique to the engine through written guidelines and tutoring where needed. Also, I personally ensured that both the game design documentation and system documentation were up to date.

I also improved my ability to utilize version control in a team setting. This project was the first one for me in which the team utilized Git rather formally. With formalities I mean submitting pull requests of development branches with Jira ticket IDs, making code reviews, and merging only approved changes. It was good to familiarize with a more proper workflow which had not been taught or enforced in the past.

It was also the first time I came in contact with sensors and integrating real world data into an application. During the project I familiarized myself with the architecture of MQTT brokers and clients, and implemented a client using an off-the-shelf MQTT protocol library. Through some implementation challenges that we faced, I learned a few dos and don'ts on broker topic stucture and how it greatly influences the applications it enables.
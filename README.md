FlashCards
=======

Web analog of ankiDroid application. Application allow you to create collections with words and offers you translations automaticly. 
The app uses [spaced repetition](https://en.wikipedia.org/wiki/Spaced_repetition) for learning new words.
Applicaton will track down all of your progress on each collection.

#### I used Golang for building 2 restfull api and React for SPA. 

Installation
------------

Clone this repo: 
	
	git clone https://github.com/Kin-dza-dzaa/ankiDroidWeb

And run:
	
	docker compose up -d

It creates 5 containers and 4 images. Those images need around 600 mb of space.
Then open:
	
	localhost:3000


Demo of the app
------------

### Creating a collection

![](https://raw.github.com/Kin-dza-dzaa/ankiDroidWeb/main/spa_build/create_collection.gif)


### Learning a collection


![](https://raw.github.com/Kin-dza-dzaa/ankiDroidWeb/main/spa_build/learn_words.gif)
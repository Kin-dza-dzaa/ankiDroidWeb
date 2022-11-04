FlashCards
=======

Web analog of ankiDroid application. Application allow you to create collections with words and offers you translations automaticly. 
The app uses [spaced repetition](https://en.wikipedia.org/wiki/Spaced_repetition) for learning new words.
Applicaton will track down all of your progress on each collection.

####I used Golang for building 2 restfull api and React for SPA. 

Installation
------------

Clone this repo: 
	
	git clone https://github.com/Kin-dza-dzaa/ankiDroidWeb

Pull down all submodules:

	git submodule init
	git submodule update

And run:
	
	docker compose up -d

It creates 5 containers and 4 images. Those images need around 400 mb of space.
Then open 
	
	localhost:3000


Demo of my app
------------

###Creating a collection

![](https://github.com/Kin-dza-dzaa/ankiDroidWeb/spa_build/create_collection.gif)


###Learning a collection


![](https://github.com/Kin-dza-dzaa/ankiDroidWeb/spa_build/learn_collection.gif)
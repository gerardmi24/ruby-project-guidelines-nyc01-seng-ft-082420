***POKEMON RPG: GOTTA CATCH 'EM ALL***

A Pokemon RPG where a user begins their journey with a starter Pokemon and tries to catch all 151 Pokemon!

Installation Instructions:
* Clone down
* Run bundle install
* Run ruby run.rb
* Remember you movie facts and have fun!!

User Stories:
* As a user, I can travel to new locations (Forest, Beach, Tundra, Mountain, Cave)
* As a user, I can access Pokemon data by selecting Pokedex
* As a user, I can catch wild Pokemon to add them to my team and update my Pokedex
* As a user, I want to level up my Pokemon and evolve them through training

Models, Associations, Attributes:
* A User has many Pokemon
* A Pokemon belongs to a User
* A Pokemon has many Attack
* An Attack has many Pokemon
* A User has many Attacks through Pokemon
* An Attack has many User through Pokemon

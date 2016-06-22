# Sails.JS Practice

My First [Sails](http://sailsjs.org) application


* Installation

```

sudo npm install -g sails
npm install -g sails-generate-views-handlebars
sails new projectName --template=handlebars
cd projectName
sails lift
npm install sails-hook-autoreload	# for auto reloading server if any change made

```

To run-

```

git clone ....
cd projectFolder
npm install

```

## Some Info-

*	api/policies.js		=>	middlewere
*	api/controllers.js	=>	controller
*	config/routes.js	=>	route
*	config/env			=>	env (prod + dev)

*	Task Autometion		=>	http://sailsjs.org/documentation/concepts/assets/task-automation
*	Migration			=>	https://github.com/building5/sails-db-migrate
*	Seed				=>	https://www.npmjs.com/package/sails-migrations
*	Faker				=>	https://www.npmjs.com/package/sails-hook-seed

##Connect With DB-

*	MySQL		=>	https://www.npmjs.com/package/sails-mysql
*	MongoDB		=>	https://www.npmjs.com/package/sails-mongo

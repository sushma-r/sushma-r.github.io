---
layout: post
title: Generators in PHP 5.5
---

Laravel is a web application framework with expressive, elegant syntax and with the amazing following features.

* It has everything with best software & programming practices

* Great community support

* RESTful Routing

	One of the coolest thing is its amazing routing features. Looking closely at routing mechanisim there are various types of routes,
	These includes : Routing for basic static pages, Passing parameters to functions, Using named routes to make URLs easier to use, Group routing
	Filtering routes for Auth or anything else & Handling 404 Errors.

* Eloquent ORM
	
	The Eloquent ORM makes it incredibly easy to interact with a database. The ORM will take care of object retrieval and persistance, where no need to write a query. 

* Beautiful Templating
	
	Laravel uses a powerful templating engine called Blade, is driven by template inheritance and sections.

* Composer

	Composer is an amazing tool to manage application's third-party packages.

* TDD 
	
	TDD is a developement process where it employs test first and code later approach. TDD in laravel is marvelous. 

```
<?php
function getAlphabets(){
  yeild "A";
  yeild "B";
  yeild "C";
  yeild "D";
}
$alphabets = getAlphabets();
foreach ($alphabet as $alphabets) {
    echo $alphabet;
}
```

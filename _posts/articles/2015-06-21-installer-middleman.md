---
layout: post
title: Installer Middleman
modified:
categories: articles
excerpt: 
tags: [Installation, ruby]
image:
  feature:
date: 2015-06-21T23:06:54+02:00
author: xavier
---

Middleman est un utilitaire Ruby qui permet de faciliter la réalisation sites statiques.
Nous vous proposons d'apprendre à l'installer, ainsi que le template middleman-bss qui vous fournit une base pour un joli site utilisant bootstrap. Attention, ces notes très succintes sont destinées à être un aide mémoire.

## Installation sous Ubuntu de middleman

	sudo apt-get install slim
	sudo apt-get install gem
	sudo apt-get install ruby ruby-dev
	sudo gem install middleman

## Installation de middleman bss
	
	mkdir ~/.middleman
	git clone https://github.com/hello-jason/middleman-bss ~/.middleman/middleman-bss

## Utilisation

	middleman init project-name --template=middleman-bss
	cd project-name/
	bundle install

	cd source
	cp environment_variables.rb.sample environment_variables.rb


## Outils supplémentaires

	sudo npm install bower -g
	sudo gem install sass
	sudo gem install compass
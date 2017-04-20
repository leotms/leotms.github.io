---
layout: posts
title: ANAR Memoria
description: Educational memory game about rock paintings in Venezuela. Developed as community service for the Archivo Nacional de Arte Rupestre (ANAR).
image: /img/posts/anarmemoria.png
categories: project
themes: Web Development, Videogame, Educational.
tools: Angular 1.x, Node.js, Loopback.io, Sockets.io, CouchDB, PouchDB.
coauthors: Edward Fernández.
---

![Logo AnarMemoria](/img/posts/anarmemoria.png)

ANAR Memoria is a web based educational game, whose objective is to teach children in schools about rock paintings in Venezuela. [Edward Fernández](https://github.com/edansi94) and I started working in this project in April 2016, and the work ended in January 2017.

The project was already started by another group of students, but it was only a single player game. Our main work consisted to implement a multiplayer game mode and adding some modifications to the single player mode, among several other corrections.

For this, we decided using Node.js for the multiplayer server, and Loopback.io to create a simple REST API to control current active games and movements. For the realtime connection, we used Sockets.io.

The game is currently being served in one of the [USB servers](http://159.90.9.166:443), feel free to register and play it.

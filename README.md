# MVC Framework.

Now with silly name! Iguana. This is purely because I needed a single directory name for all the code and such, I promise.

This is a simple MVC framework I intend to use for any web applications I produce. "Framework" is a bit of a misnomer; I'm not trying to provide a complete suite of components for your every need - the framework simply translates URLs into classes and methods and invokes them to allow you to code in an object oriented fashion. Providing some kind of view library for output is on the cards, but not really done yet. I'm not going to include any kind of model functionality as part of this framework ever since as Zend point out the kind of model you want varies by project.

This framework now uses Composer and requires PHP 5.4 and up because I want to horribly misuse traits.
# Tor Browser Research-Project

The goal of this research is to break a part of the anti-fingerprinting mechanisms built into the Tor Browser, specifically the aspect which attempts to obscure the loading time of a page. While it may seem like an arbitrary statistic, when a website is able to glean any uniquely identifying information from a user it then becomes possible to track the actions taken by that user across the web. 

In the context of this research, a user on the native Firefox or Chrome browser loads a webpage with Javascript enabled. The Javascript

In this project, it is seen that the Tor Browser utilizes a form of fuzzing to obscure the loading time for a page. When compared directly with data from native installations of Firefox and Chrome, that information was not obscured. In a randomized manner, the browser would report times of loading from 0 ms to 400 ms with no identifiable pattern.

In order to break this randomization, 

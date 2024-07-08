# LibraryRecommendations
Building AI Course Project

# Project Title

Library Recommendations

## Summary

A recommendation system for a library user, that concentrates especially on widening the world view instead of creating an information bubble.


## Background

Libraries are great places for independent learners, but their selection is huge. It can be difficult to find the relevant material, and often the user is not even sure what he would be interested in, until he finds it (oftentimes by chance according to my experience!). Libraries' task is to educate people to learn more about the world, and widen the world view. This system helps people find what they are looking for, and even what they are not looking for, but will find interesting nevertheless!


## How is it used?

There are several ways this library recommendation system will differ from many other recommendation systems. First of all, it takes into account the learning curve of the user. For example, if the user has previously borrowed an entry level book on programming, the system will next recommend intermediate level programming material. Second, it tries always to widen the scope of the user. For example, if the user has borrowed Spanish study books on intermediate level, it will next recommend Spanish novels, cartoons or movies, that may prove to be of interest and use to the user. If the user has read fantasy books about the Middle Ages, the system might recommend some factual historical documentaries of the era. Here, the feature 'Spanish' was kept constant while changing other features, like 'study book' into 'movie', or keeping the theme 'Middle Ages' constant, but changing the feature 'fantasy' into 'factual'. Third, the system follows current events, and may suggest reading Christmas novels during December, or biographies of athletes during the Olympic year, taking inspiration from the outside world and not only from the user's preferences. This way, the user will stay up to date on current events and learn more about them, and the world he lives in. Fourth, it has a 'Surprise me' function, that pulls a wild card, that is, a recommendation that has very little to do with anything the user has previously borrowed. This may surprise the user, and he may find new areas of interest. And even if it doesn't inspire him, at least he will learn that this kind of thing exists, too ("Imagine that there are whole books written on the procreation of fungus! Who would have thought!").


## Data sources and AI methods
Data sources, in addition to the library book repository and the data on the user's previously borrowed books, will be the suggested reading materials and links from different schools' curriculum, as well as current events from a local and global news site. Nearest neighbor method can be used for some of the recommendations, but at times we need the opposite of the nearest neighbor, that is, when we use the Surprise function.

## Challenges

Data privacy has to be taken into account, because the material that people have borrowed is private. Also, we need to make sure we don't give recommendations of material meant for adults for under-aged users. Also, if the scope of the recommendations is too wide, the user might become frustrated by all the irrelevant material. It might be a good idea to arrange the recommendations into different categories, so the user can decide whether he is feeling more adventurous or wants to stick to his own preferences. The system needs to be kept up to date with the current events, too.

## What next?

This system could grow to include material not just from the library, but from other libraries and bookstores the user visits.


## Acknowledgments

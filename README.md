# Patterns-in-Angularjs
Common patterns and anti patterns


## How to Structure your Application

There is no right way to structure the files!

The computer doesn’t care how we structure, in the end it would be served in a single file and minified. Structuring is done for Humans.

#### The two main ways to do it
#### By type:
you will see this a lot in generators out there, like yeoman generator for angular
```
app/
    controllers/
    services/
    views/
```
This is great in simple demos or POC apps but, eventually this gets harder and harder as the application grows.

#### By feature
```
app/
    dashboard/
    layout/
    people/
```
I prefer this style as it is very easy to plug and play with different features all together and smaller teams can easily focus on a small component

you ain’t gonna need it (YAGNI)
you don’t need to build the stuff that you think are "what if we need this feature in future” build the ones you are sure you need and take it up if you have time.

#### Hybrid
Another option is to go Hybrid
Folders for feature and then by type?


## Resources used to collect this
1. John Papa - 10 AngularJS Patterns - Code on the Beach 2014
Link: https://www.youtube.com/watch?v=UlvCbnKAH3g
Demos: https://github.com/johnpapa/ng-demos

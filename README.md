Blocky game

Similar to Tetris but you have to click a block to have matching neighbour blocks removed.

Implemented with vanilla javascript/ES6, browserify and gulp

To get started

```
$ npm i
$ npm start
$ open http://localhost:9100/
```

Game rules e.g.,

Given:

```
#######
###$$##
###$##$
##$$###
```

After the first $ is clicked the board should look like this:

```
###  ##
### ###
##  ##$
#######
```

Clicking and of the # will result in:

```
       $



```

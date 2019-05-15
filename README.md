# utbc2019-mdl-play

Play with material design lite in preparation for MD and React.

I'm following along in this (somewhat dated circa 2015) navbar [tutorial](https://webdesign.tutsplus.com/tutorials/learning-material-design-lite-navigation--cms-24565).

## Early screen shot

![alt](docs/img/mdl-screen-shot.png)

I've found this nice responsive codepen on the internet that features a CSS grid which should suit my purposes nicely (even though I'm big on flexbox at the moment) ...

![alt](docs/img/mdl-screen-shot-2.png)

## Latest fu

I would /really/ like to redesign the user interface for project 1.  It's fine especially given that we only had 2 weeks to knock it out.  But I'm jones'ing for some MDL and so I'm pushing forward.

![alt](docs/img/mdl-screen-shot-3.png)

## Floating Action Button (FAB)

I see plenty of Material Design examples with floating action buttons that overlap the border between two divs.  I find it very attractive, but I don't see any off-the-shelf classes in the framework to make that happen.  Fortunately, there is plenty of CSS fu for that.

Using a combination of flexbox (for flexing the main div and yielding a sticky footer) and absolute positioning relative to the main div, I'm able to create the effect I want:

![alt](docs/img/fab-study.png)

In this code section we are going to dive in to animating react apps. we are going to learn how to move from static 
styles and component to animated styles and components

###CSS animations and why they are sometimes not enough

###Animating React Components with Extra Libraries

by this project we animate the modal and appearance of the list.

keyframe in animation and filmmaking is a drawing or shot that defines the starting and ending points of any smooth 
transition.

making the opacity of a modal 0 is not good as it appears in the dom yet. that will affect the performance.

below package, we used!!!!!
###npm install react-transition-group --save

When considering animations there are 6 aspects
1. onEnter
2. onEntering
3. onEntered
4. onExist
5. onExiting
6. onExited


<Transition onEnter={() => {}} >

we can replace <ul></ul> by <TransitionGroup></TransitionGroup> to add transitions to list items

import TransitionGroup from 'react-transition-group/TransitionGroup';
import CSSTransition from 'react-transition-group/CSSTransition';

"in" property is used to control the state of our transition.

#other animation packages
1. React-Motion Library

npm install --save react-motion

2. React-Move Library

npm install react-move

3. React Router Transition Library

npm install --save react-router-transition

Animation helps to get user attention.

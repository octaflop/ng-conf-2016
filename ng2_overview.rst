Angular 2 Core Concepts
=======================

Dan Walin and John Papa.

We use components to figure parts / sections of our single-page apps.

Imports are awesome because we don't worry about ordering any more. They also
help compress our js files.

Services replace a number of concepts in angular.

Con: There is a completely different syntax, but it's easy to learn
(supposedly).

TypeScript is the massive china polandball that has ES6 ES7 (and of course
ES5).

43 directives are gone in angular 2.

Building Blocks
---------------

Modules
+++++++

``export`` is a way to allow an object/class/varialbe to be imported elsewhere.

Router: better than ui-view and ng-view from angular 1.
There's a built-in directive [routerLink] that is like django's url template function.

Components
++++++++++

Banana in a box is the term for attribute selection ``[( )]`` eg ``[(ngModel)]``. This causes the 2-way data-binding.

Decorators
++++++++++


Services
++++++++

They do all the things now. 

This is the idea of a reusable code. We have one type of service now.

You need to add ``@Injectable()`` to classes that you want to inject.

http
****

Observables: maps the results of a response. This is like an array spread out
over time. This would also allow for sockets and other streaming principles.

You can do a ``.promise(`` instead of ``.map``.

rxmarbles.com for learning about observables.

Example of using the star wars api with an observable:

http://tinyurl.com/ng2Swapi

films => this.films = films → this arrow function is a more powerful anonymous
function.

Questions
---------

Should I use ``angular-cli`` or ``npm start``?

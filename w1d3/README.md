# W1D3 - Objects in JS

Hey crew,

You folks are ... THE BEST! Thanks for that fun class today. We went over the agenda below:

### Agenda
- [x] Check ins and Review
- [x] Arrays review
- [x] Objects
- [x] Classwork


### Take aways today

- learned that the `for .. in` can loop through both arrays and objects. In case of an array, we get indexes while for objects we get the keys
- defining a function (method) inside an object.
- do not define a variable without the keywords const / let. Even if you can. Not sure why? Please speak to a mentor.
- console.log extension and commenting hotkeys (`CMD + /`)
- arrays and objects within other arrays are referenced rather copied by value. Primitives are copied by value while non-primitives (arrays / objects) are copied by reference
- Arrays are good for grouping heterogenous data while objects are suited for data grouped around a peculiar business thing (object).

[Breakout gist is here, courtesy of KV - thanks KV ;)](https://gist.github.com/hafbau/ffc28b276c621127c4c6b80e51e86e69)

[The files we worked on (commented with notes) are here.](https://github.com/hafbau/lecture_notes/w1d3)
[Checkout solution of the classwork here.](https://github.com/hafbau/lecture_notes/w1d3/classwork)

[Video will be here, when upload is ready](#)

[Here's a visualization of pass by reference for non-primitive data types. Made by Andy (another awesome Vancouver instructor)](http://pythontutor.com/javascript.html#code=const%20myObj%20%3D%20%7B%20name%3A%20'Alice'%20%7D%3B%0A%0Aconst%20changeName%20%3D%20function%28obj%29%20%7B%0A%20%20obj.name%20%3D%20'Bob'%3B%0A%20%20console.log%28'inside',%20obj.name%29%3B%0A%7D%3B%0A%0AchangeName%28myObj%29%3B%0Aconsole.log%28'outside',%20myObj.name%29%3B&mode=edit&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)

Also, feel free to look at [Dom's (Montreal Lead instructor) awesome notes](https://gist.github.com/DominicTremblay/246f70931394316eaaa81d5a3e6b30d7) (waaaay better than mine), for alternative spins on the things we discussed today.

Thank you!
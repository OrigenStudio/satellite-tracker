Satellite tracker
=================

Javascript 3D satellite tracker with up-to-date data from CELESTRAK. Uses [Three.js](https://threejs.org/), [React](https://reactjs.org/) and [satellite.js](https://github.com/shashwatak/satellite-js) for orbit prediction. 

Here is a nice screenshot showing the predicted International Space Station orbit through a day. (Side note, [Why doesn't ISS pass over the polar regions?](https://space.stackexchange.com/questions/5297/why-doesnt-iss-pass-over-the-polar-regions))

![International Space Station](screenshots/01.png)

Active objects from CELESTRAK (http://www.celestrak.com/NORAD/elements/active.txt)

![Active satellites](screenshots/02.png)

Here debris from cosmos-2251 in red, active sats in blue, stations in yellow: 

![debris](screenshots/04.png)

Installation
============

    $ git clone https://github.com/dsuarezv/satellite-tracker
    $ cd satellite-tracker
    $ npm install
    $ npm run dev

That should start a [parcel](https://parceljs.org/) dev server and browse http://localhost:1234 to see it in action. In case parcel is not installed, follow instructions on their site. 
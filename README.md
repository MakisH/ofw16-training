# My 16th OpenFOAM Workshop training session slides

- Title: Flexible & efficient multiphysics simulations with the coupling library preCICE
- Speaker: Gerasimos Chourdakis, Technical University of Munich
- Authors: Gerasimos Chourdakis, Benjamin Uekermann, + [more](https://www.precice.org/about/)
- Event: [16th OpenFOAM Workshop](https://www.ucd.ie/openfoam2021/), online
- Date: June 11, 2021

[Start the presentation](https://makish.github.io/ofw16-training/) - [Get the PDF](https://github.com/MakisH/ofw16-training/blob/master/pdf-export/slides.pdf) (coming soon)

## Build

Follow the instructions on [reveal.js](https://revealjs.com/installation/), or just install Node.js 10.0.0 or later and do:

```bash
npm install
npm start
```

and go to [localhost:8000](http://localhost:8000/) to see the slides.

## Convert to PDF

See section "[Export to PDF](https://revealjs.com/pdf-export/)" in the reveal.js documentation.

[Decktape](https://github.com/astefanutti/decktape) does a marvelous job converting this presentation to PDF. Get the Docker image (see Decktape README) and run (for localhost):

```bash
docker run --rm -t --net=host -v "$(pwd)":/slides astefanutti/decktape generic --key=" " -p 2000 -s 1920x1440 http://localhost:8000 slides.pdf
```

## License & more

- License: [CreativeCommons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/)
- Based on [reveal.js](https://github.com/hakimel/reveal.js). Template based on the "White" template by Hakim El Hattab.
- The TUM logo is part of the corporate identity of the Technical University of Munich.

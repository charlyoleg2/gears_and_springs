Gears and springs
=================


Presentation
------------

This repo is a maker-repository. It stores the parameters and the STL-files of *gears and springs*.
This repo uses the javascript packages [designix-cli](https://www.npmjs.com/package/designix-cli) and [designix-uis](https://www.npmjs.com/package/designix-uis) of the design-library [designix](https://charlyoleg2.github.io/parametrix/).


Requirements
------------

- [node](https://nodejs.org) > 20.10.0
- [npm](https://docs.npmjs.com/cli) > 10.1.0


### Optional requirements

- [OpenSCAD](https://openscad.org/)

For Ubuntu users, *OpenSCAD* is available on [snapcraft](https://snapcraft.io/openscad) and can be installed with:

```bash
sudo snap install openscad
```

Upgrade
-------

For working with the latest *designix* version:

```bash
npm outdated
npm update --save
git commit -am 'npm update --save'
```


Dev
---

```bash
git clone https://github.com/charlyoleg2/gears_and_springs
cd gears_and_springs
npm install
npm run
npm run designix-uis
npx designix-uis
npx designix-cli --help
./make_gear.js
```

Vocabulary
----------

- Design: A parametrizable 3D parts. Desginix is a collection of designs.
- Reference: A particular parametrization of a design.
- Instance: The realization of a reference.


References for the gears and springs
------------------------------------

ID | Reference                 | Design                   | Nb of instances
---|---------------------------|--------------------------|----------------
1  | gear\_wheel\_wheel        | gear\_wheel\_wheel       | 1
2  | simplified\_gear\_wheel   | simplified\_gear\_wheel  | 1

Each reference has its own directory with its json-parametrization, scad-script and stl-file.



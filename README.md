lesscw
======

lessc with watching

* src: `lesscw.co` written in [coco language](https://github.com/satyr/coco/)
* bin: `lesscw`

## Installation

* get [node](nodejs.org/)
* get [npm](https://npmjs.org/)
* `npm install -g lesscw`
* or `git clone https://github.com/jan-swiecki/lesscw/ && cd lesscw && npm link`

## Usage

 * `lesscw asd.less` will output `./asd.css` and it will output `./asd.css` on every change of `./asd.less`.
 * `lesscw asd` will compile all `./asd/*.less` into `./asd/*.css` and it will do so on every `./asd/*.less` file change.

have fun
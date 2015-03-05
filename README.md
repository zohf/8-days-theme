# 8 Days Theme

8 Days is a custom Ghost theme.

## Getting started

To install, simply download this repo as a zip, extract, and place the 8-days-theme folder in your themes directory. Login to the Ghost CMS backend at `yoursite.com/ghost` with your email and password, go to settings, and select the 8 Days Theme from the dropdown.

## Usage

By default, 8 Days homepage populates via Ghost article tags. It loops through all posts, adding those with the "Blog" and "Gallery" tags to their requisite sections. To add another section based on tags in `loop.hbs`, wrap the code block in a `{{#foreach posts}}` loop and check `{{#has tag="newTag"}}`. You can then access direct properties for each post (e.g. `{{post_class}}`).

## Documentation

If you are new to the Ghost CMS, you can learn more about it here: [https://github.com/tryghost/Ghost](https://github.com/tryghost/Ghost)

Note: the Ghost CMS currently requires standard CSS and does not natively support preprocessors. You'll see an included Sass directory within the assets directory. We used [Compass](http://compass-style.org/) during development. 

Compass runs on any computer that has Ruby installed. If you don't have Ruby installed, you can follow those steps [here](http://www.ruby-lang.org/en/downloads/).

To install Compass type `$ gem install compass` in your terminal window.

Since our project is already setup, navigate to the `assets` diretory and type `$ compass watch`. Now any changes you make in the Sass directory will be compiled and refelcted in the stylesheets directory. Top stop Compass from watching, type `$ ctrl + c`.

## Authors

[Josh Laincz](https://github.com/zohf), [Aidan Feay](https://github.com/alfeay)

## Contribute

This is an active project and we encourage contributions. [Please review our guidelines and code of conduct before contributing.](https://github.com/voxmedia/open-source-contribution-guidelines)

## License 

Copyright (c) 2014, Vox Media, Inc.
All rights reserved.

BSD license

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
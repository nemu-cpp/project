# Nemu/C++ Project Documentation

Nemu/C++ provides a framework to write servers and web applications in C++.

This repository contains the project documentation.


## Contents

### Nemu/C++ projects

1. [Core](https://github.com/nemu-cpp/core): this library provides fundamental functionality for the Nemu/C++ project.

   [![nemu-cpp](https://circleci.com/gh/nemu-cpp/core.svg?style=shield)](https://circleci.com/gh/nemu-cpp/core)

1. [WebFramework](https://github.com/nemu-cpp/web-framework): networking implementation based on
   the Ishiko/C++ [Networking](https://github.com/ishiko-cpp/networking) and [HTTP](https://github.com/ishiko-cpp/http)
   projects.

   [![nemu-cpp](https://circleci.com/gh/nemu-cpp/web-framework.svg?style=shield)](https://circleci.com/gh/nemu-cpp/web-framework)

1. [MustacheTemplateEngine](https://github.com/nemu-cpp/mustache-template-engine): adds support for {{ mustache }} templates to Nemu.

   [![nemu-cpp](https://circleci.com/gh/nemu-cpp/mustache-template-engine.svg?style=shield)](https://circleci.com/gh/nemu-cpp/mustache-template-engine)

1. [Nemu](https://github.com/nemu-cpp/nemu): the top level Nemu project.

   [![nemu-cpp](https://circleci.com/gh/nemu-cpp/nemu.svg?style=shield)](https://circleci.com/gh/nemu-cpp/nemu)


# Usage

## Building the projects from scratch

The following build order can be used to build the projects from scratch:

1. Core
1. WebFramework
1. MustacheTemplateEngine
1. Nemu


# Support

None.

## License

Copyright (c) 2019-2022 Xavier Leclercq

Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the "Software"),
to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL
THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS
IN THE SOFTWARE.

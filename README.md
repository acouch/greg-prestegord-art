# Gregory Prestegord Art

This website is built using Jekyll with HTML, TailwindCSS, JavaScript and Ruby (for a few custom plugins). It is based off of this site: https://github.com/gouravkhunger/portfolio.

The website is generated using [github actions](https://github.com/acouch/gregory-prestegord-art/blob/jekyll/.github/workflows/publish-site.yml) and served via the [gh-pages](https://github.com/acouch/gregory-prestegord-art/tree/gh-pages) branch.

## Local Setup

Please install [Ruby](https://www.ruby-lang.org/en/documentation/installation/) and [Node.js](https://nodejs.org/en/download/) before proceeding future!

Clone the project:

```bash
git clone https://github.com/acouch/gregory-prestegord-art
cd portfolio
```

Install dependencies:

```bash
npm i
bundle install
```

Run local server

```bash
bundle exec jekyll serve
```

Now you can head over to [https://localhost:4000](https://localhost:4000) to preview the website locally!

## License

This project is licensed under the [MIT License](https://github.com/gouravkhunger/portfolio/blob/jekyll/LICENSE) terms.

```
MIT License

Copyright (c) 2022 Gourav Khunger

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

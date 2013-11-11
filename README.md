# Advanced Foundation Course

## Pre-flight checklist

  * [Install Node.js](http://nodejs.org/)
  * Install bower: `npm install bower -g`
  * Install compass: `gem install compass`

## Quickstart

```bash
git clone git@github.com:zurb/advanced-foundation-course.git
cd advanced-foundation-course
bower install
compass watch
```

## Directory Structure

After you run the commands above you'll see the following directory structure

```
advanced-foundation-course/
├── vendor/
│   ├── foundation/
│   ├── jquery/
│   └── modernizr/
├── css/
├── scss/
│   └── app.scss
├── config.rb
└── index.html
```

  * `scss/`: Raw SCSS files
  * `vendor/`: Bower installed components

# Advanced Foundation Course

## Quickstart (Beginner)

  * [Download this project](https://github.com/zurb/advanced-foundation-course/archive/master.zip)
  * Open `index.html` in your browser!


## Quickstart (Advanced)

### Pre-flight checklist

  * [Install Node.js](http://nodejs.org/)
  * Install bower: `npm install bower -g`
  * Install compass: `gem install compass`

Once everything is installed run:

```bash
git clone git@github.com:zurb/advanced-foundation-course.git
cd advanced-foundation-course
bower install
```

When you're working on this project just run the following command:

```bash
compass watch
```

## Directory Structure

After you run the commands above you'll see the following directory structure

```
advanced-foundation-course/
├── vendor/
│   ├── foundation/
│   ├── jquery/
│   ├── modernizr/
│   └── masonry-shim/
├── css/
├── scss/
│   └── app.scss
├── config.rb
└── index.html
```

  * `scss/`: Raw SCSS files
  * `vendor/`: Bower installed components

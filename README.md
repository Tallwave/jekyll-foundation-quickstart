# Jekyll with Foundation (Compass) Quickstart by 29th Drive

Design & Development quickstart with Jekyll & Foundation + Compass.

## Requirements

  * Ruby 1.9+
  * [Foundation](http://foundation.zurb.com): `gem install foundation`
  * [Node.js](http://nodejs.org)
  * [compass](http://compass-style.org/): `gem install compass`
  * [bower](http://bower.io): `npm install bower -g`
  * [Jekyll](http://jekyllrb.com/): `gem install jekyll`

## Quickstart

  * [Download this starter compass project and unzip it](https://github.com/29thdrive/29th-drive-quickstart/archive/master.zip)
  * __Important:__ Don't alter the files in the `bower_components` folder. These files will get updated when Foundation gets updated.
  * __Run `bower install`__ to install the latest version of Foundation
  * Check out the [Foundation 5 Documentation](http://foundation.zurb.com/docs/)
  * Check out the [Jekyll](http://jekyllrb.com/docs/home/) documentation

Then when you're working on your project, run the following command to watch the Sass folder and continually rebuild (poll) the CSS:

```bash
compass watch
```

Run the following command to compile the CSS one time:

```bash
compass compile
```

Run the following command to build the site with Jekyll:

```bash
jekyll build
```

Run the following command to build the site and serve it with Jekyll:

```bash
jekyll serve
```

Run the following command to continually poll for changes in the site and rebuild with Jekyll:

```bash
jekyll build --watch
```

## Upgrading this Repo

Run `bower install` to install the latest version of Foundation

If you'd like to upgrade to a newer version of Foundation down the road, run:

```bash
bower update
```

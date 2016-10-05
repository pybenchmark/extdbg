<h1><img src="https://raw.githubusercontent.com/duboviy/extdbg/master/logo.png" height=85 alt="logo" title="logo"> extdbg</h1>

by [Eugene Duboviy](https://duboviy.github.io/)

[![Build Status](https://travis-ci.org/duboviy/extdbg.svg?branch=master)](https://travis-ci.org/duboviy/extdbg) [![CircleCI](https://circleci.com/gh/duboviy/extdbg.svg?style=svg)](https://circleci.com/gh/duboviy/extdbg) [![Codacy Badge](https://api.codacy.com/project/badge/Grade/3a7bdeaac57c431ab1263fcd5f19e4a9)](https://www.codacy.com/app/dubovoy/extdbg?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=duboviy/extdbg&amp;utm_campaign=Badge_Grade) [![PyPI](https://img.shields.io/pypi/v/extdbg.svg)](https://pypi.python.org/pypi/extdbg) [![Codacy Badge](https://api.codacy.com/project/badge/Coverage/3a7bdeaac57c431ab1263fcd5f19e4a9)](https://www.codacy.com/app/dubovoy/extdbg?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=duboviy/extdbg&amp;utm_campaign=Badge_Coverage) [![Code Health](https://landscape.io/github/duboviy/extdbg/master/landscape.svg?style=flat)](https://landscape.io/github/duboviy/extdbg/master) [![Open Source Love](https://badges.frapsoft.com/os/mit/mit.svg?v=102)](https://github.com/duboviy/extdbg/) [![PRs & Issues Welcome](https://img.shields.io/badge/PRs%20&%20Issues-welcome-brightgreen.svg)](https://github.com/duboviy/extdbg/pulls) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/duboviy/extdbg/)

Extended debugging python utilities



## Installation:

```
pip install https://github.com/duboviy/extdbg/archive/master.zip
```

## Supported python versions

  * 2.7
  * 3.3
  * 3.4
  * 3.5
  * 3.6
  * PyPy

## PyPI

* [Package](https://pypi.python.org/pypi/extdbg)
* [Documentation](https://pythonhosted.org/extdbg/)

Contents
--------

- `extdbg.init_except_hook` - initialise extended traceback hook with locals variables in exception message
- `extdbg.add_watched_attribute(name, watch_get=False)` - when called in class (for example `add_watched_attribute('name')`) - instances of that class will log every change to the attribute. And log every access if `watch_get` is `True`.
- `extdbg.where_is(object)` - return location of object in code.
- `extdbg.from_where_called()` - returns location in code from where function which calles this is called
- `extdbg.watch_for_output(condition=lambda x: True, stream='stdout')` - log location in code where some output is performed.
- `extdbg.func_to_dict` - converts function of one hashable argument to dictionary-like object which "contains" all it returning values.
- `extdbg.pprint` - pprint values wrapped into frame. Also return first passed value unchanged (useful when debugging expressions).

... and many other features

## License

**MIT** licensed library. See [LICENSE.txt](LICENSE.txt) for details.

## Contributing

If you have suggestions for improving the extdbg, please [open an issue or
pull request on GitHub](https://github.com/duboviy/extdbg/).

## Badges

[![forthebadge](http://forthebadge.com/images/badges/fuck-it-ship-it.svg)](https://github.com/duboviy/extdbg/)
[![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](https://github.com/duboviy/extdbg/) [![forthebadge](http://forthebadge.com/images/badges/built-by-hipsters.svg)](https://github.com/duboviy/extdbg/) [![forthebadge](http://forthebadge.com/images/badges/built-with-swag.svg)](https://github.com/duboviy/extdbg/)

[![forthebadge](http://forthebadge.com/images/badges/powered-by-electricity.svg)](https://github.com/duboviy/extdbg/) [![forthebadge](http://forthebadge.com/images/badges/powered-by-oxygen.svg)](https://github.com/duboviy/extdbg/) [![forthebadge](http://forthebadge.com/images/badges/powered-by-water.svg)](https://github.com/duboviy/extdbg/) [![forthebadge](http://forthebadge.com/images/badges/powered-by-responsibility.svg)](https://github.com/duboviy/extdbg/)

[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=102)](https://github.com/ellerbrock/open-source-badge/)

[![forthebadge](http://forthebadge.com/images/badges/makes-people-smile.svg)](https://github.com/duboviy/extdbg/)

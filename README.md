The axyz Middleman Skeleton
===========================

Concepts
--------
- golden ratio based modular scale typography, baseline, responsive grid system(susy)
- color palette based on solarized
- semantic approach:
	- erb layouts to preserve compatibility with raw html
	- scss styles to preserve raw css compatibility
	- susy uses semantic grids
	- jquery ui uses a semantic approach(not perfect, but fine)
	- markdown content (ideally it could be compatible with raw human writing)
- coffeescript for clientside scripts

Installation
------------
- make sure to have:
	- ruby
	- gem install middleman

- git clone git://github.com/axyz/middleman-axyz-skeleton.git ~/.middleman/axyz
- middleman init my-new-project --template=axyz

Usage
-----
- cd my-new-project
- middleman server
- open browser to http://127.0.0.1:4567

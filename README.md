The axyz Middleman Skeleton
===========================

Concepts
--------

- HTL5 Boilerplate

- golden ratio based modular scale typography, baseline, responsive grid system(susy)

- color palette based on solarized

- semantic approach:

    - susy uses semantic grids
    
    - jquery ui uses a semantic approach(not perfect, but fine)

- compatibility:

	- erb layouts to preserve compatibility with raw html
    
	- scss styles to preserve raw css compatibility
    
	- markdown content (ideally it could be compatible with raw human writing)

- coffeescript for clientside scripts


Installation
------------

- make sure to have:

	- ruby
    
	- gem install middleman
    
	- git

- git clone git://github.com/axyz/middleman-axyz-skeleton.git ~/.middleman/axyz

- middleman init my-new-project --template=axyz

Usage
-----

- cd my-new-project

- middleman server

- open browser to http://127.0.0.1:4567

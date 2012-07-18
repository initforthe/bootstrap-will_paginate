## [Will Paginate][wp] link renderer in a [Twitter Bootstrap][bs] stylee.

### Installation

Add to your Gemfile:  
    
    gem 'bootstrap-will_paginate'

### Usage

    <%= will_paginate(@things, :renderer => Bootstrap::WillPaginate::LinkRenderer) %>

Copyright (c) 2012 [Initforthe Ltd](http://www.initforthe.com), [Nicholas Fine](http://ndfine.com), [Isaac Bowen](http://isaacbowen.com) released under the MIT license  

[wp]: http://github.com/mislav/will_paginate
[bs]: http://twitter.github.com/bootstrap

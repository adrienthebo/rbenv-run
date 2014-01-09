rbenv-run
=========

Run a command under a specific version of ruby

Examples
--------

    $ rbenv run 1.8.7-p371 rake -T
    rake package:bootstrap  # Bootstrap packaging automation, e.g
    rake package:implode    # Remove all cloned packaging automation
    rake spec               # Run all specs
    rake spec:rcov          # Run RSpec code examples
    $ rbenv run 1.9.3-p484 bundle exec rspec
    ...................................................................

    Finished in 1.81 seconds
    73 examples, 0 failures, 0 pending

Installation
------------

    git clone git://github.com/adrienthebo/rbenv-run ~/.rbenv/plugins

Caveats
-------

I have no idea if this already exists. If it does, I couldn't find it.

kitchen-example
===============

Example of Test-Kitchen, Kitchen-Puppet, Kitchen-Docker, bats, puppet-lint and puppet-syntax

Checkout [Blog Post](http://blog.grubernaut.com/kitchen-magic/) and [Further info](http://ehaselwanter.com/en/blog/2014/05/08/using-test-kitchen-with-puppet) for all of the juicy details of the post!


Essentially, simply:
- Clone
- ```bundle install```
- ```kitchen test``` or ```kitchen conv```


Proof of concept, stitching together [test-kitchen](https://github.com/test-kitchen/test-kitchen), [kitchen-puppet](https://github.com/neillturner/kitchen-puppet), [kitchen-docker](https://github.com/portertech/kitchen-docker), [bats](https://github.com/sstephenson/bats), [puppet-lint](http://puppet-lint.com/), and [puppet-syntax](https://github.com/gds-operations/puppet-syntax).


Lint and syntax
---------------

- ```rake test```


Continuous Testing
------------------

- ```guard```

Further details:
- http://www.jedi.be/blog/2011/12/13/testdriven-infrastructure-with-vagrant-puppet-guard/-
- https://github.com/alister/guard-puppet-lint
- https://github.com/garethr/puppet-module-skeleton

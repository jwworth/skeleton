# Skeleton

Skeleton is a template for creating Ruby gems.

### The Setup

```
git clone https://github.com/jwworth/skeleton
cd skeleton
rake
```

Wherever you find `NAME`, change that to the name of your project. Here is a list of those places:

```
NAME.gemspec:6:  spec.name          = 'NAME'
NAME.gemspec:12:  spec.homepage      = 'http://rubygems.org/NAME'
NAME.gemspec:15:  spec.files         = ['lib/NAME.rb']
NAME.gemspec:16:  spec.executables   = ['bin/NAME']
NAME.gemspec:17:  spec.test_files    = ['tests/test_NAME.rb']
test/test_NAME.rb:2:require 'NAME'
test/test_NAME.rb:4:class NAMETest < Minitest::Test
```

Add your code, update the README, and you're ready to go.

### License

&copy; 2015 Jake Worth

This repository is distributed under the MIT license. See `LICENSE` for
details.


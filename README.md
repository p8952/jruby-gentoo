JRuby on Gentoo
===============

Building
--------

    mvn --define maven.repo.local=local-repo --define maven.test.skip=true --offline package

Testing
-------

    rake test:mri # MRI Tests
    jruby spec/mspec/bin/mspec ci # RubySpecs

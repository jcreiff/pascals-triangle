_**NOTE** This is a 100% rip of the exercise offered at
[Exercism](http://exercism.io/). Exercism is a great place to practice your
Ruby-foo (or any other language, for that matter!). The original exercises are
licensed under the MIT license._

Have fun!

# Pascals Triangle

Write a program that computes Pascal's triangle up to a given number of rows.

In Pascal's Triangle each number is computed by adding the numbers to
the right and left of the current position in the previous row.

```plain
    1
   1 1
  1 2 1
 1 3 3 1
1 4 6 4 1
# ... etc
```

* * * *

For installation and learning resources, refer to the
[exercism help page](http://exercism.io/languages/ruby).

For running the tests provided, you will need the Minitest gem. Open a
terminal window and run the following command to install minitest:

    gem install minitest

If you would like color output, you can `require 'minitest/pride'` in
the test file, or note the alternative instruction, below, for running
the test file.

In order to run the test, you can run the test file from the exercise
directory. For example, if the test suite is called
`hello_world_test.rb`, you can run the following command:

    ruby hello_world_test.rb

To include color from the command line:

    ruby -rminitest/pride hello_world_test.rb

The test files may have the execution bit set so you may also be able to
run it like this:

    ./hello_world_test.rb


## Source

Pascal's Triangle at Wolfram Math World [view source](http://mathworld.wolfram.com/PascalsTriangle.html)

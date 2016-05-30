toy-robot
===================

Building the code
-----------------

`
ruby lib\toy_robot.rb
`

This will produce a command prompt into which you can enter the commands as defined in the specification.

Example Input and Output:

a)
PLACE 0,0,NORTH
MOVE
REPORT
Output: 0,1,NORTH

b)
PLACE 0,0,NORTH
LEFT
REPORT
Output: 0,0,WEST

c)
PLACE 1,2,EAST
MOVE
MOVE
LEFT
MOVE
REPORT
Output: 3,3,NORTH

Test Data
---------

As required in the specification the test data is to be provided to exercise the application.

`
rake specs
`

This will produce a test coverage report.

[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/jimmysfu/toy-robot-ruby/trend.png)](https://bitdeli.com/free "Bitdeli Badge")


## Coffee Robot

injection using `$()` (used before i think?)

this one uses hidden files, so we need to use `ls -a`

going up a directory with `ls ..` we can see `robot-bank-job`, using `ls -a` in that dir reveals `.robot_sketches.txt`

`$(cat ../robot-bank-job/.robot_sketches.txt)`

scio-koans
==========

A collection of [Scio](https://github.com/spotify/scio) exercises inspired by [Ruby Koans](http://rubykoans.com/) and many others.

# Usage

Clone the repository and start the [sbt](https://www.scala-sbt.org/) console.

```bash
git clone https://github.com/nevillelyh/scio-koans.git
cd scio-koans
sbt
```

Run `~nextKoan` inside the console. This will watch your local files and run the next pending koan in repeat.

Once the test is green, and you are satisfied with the solution, remove the first line in the Koan, `ImNotDone`, to move on to the next one.


Here are all the tasks available.

- `allKoans` - show all Koans and their status
- `nextKoan` - run the next pending Koan
- `test` - run all Koans
- `testOnly <koan>` - run a specific Koan

# License

Copyright 2020 Neville Li.

Licensed under the Apache License, Version 2.0: http://www.apache.org/licenses/LICENSE-2.0

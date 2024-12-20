This repository demonstrates an uncommon issue related to hash key iteration order in Perl.  The Perl language does not guarantee a specific order when iterating through hash keys.  The `bug.pl` file shows an example where the output is not predictable. The `bugSolution.pl` file shows a solution for scenarios where key order matters.
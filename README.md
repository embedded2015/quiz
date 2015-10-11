Directory Organization
======================
* [q2](q2/): Question #2
* [q3](q3/): Question #3
* [q4](q4/): Question #4
* [q5](q5/): Question #5
* [q6](q6/): Question #6
* [q27](q27/): Question #27

From `q2` to `q6`, you have to implement both iterative and recursive versions.


Coding Style
============
You can use [AStyle](http://astyle.sourceforge.net/) source code indenter to
help you auto format your source code. It will for sure not correct all your coding styles but
for sure will eliminate most of them. You can download AStyle from [this location](http://astyle.sourceforge.net/)
or install via `apt-get`:
```sh
sudo apt-get install astyle
```

To format your file you can execute below command:
```sh
astyle --style=kr --indent=spaces=4 --indent-switches --suffix=none *.[ch]
```

Install Git pre-commit hook to check C/C++ source file format
```sh
ln -sf ../../scripts/pre-commit.hook .git/hooks/pre-commit
```

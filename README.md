This needs to be run in a web server since it needs to access local files. A
simple(ish) way to do this if you don't have experience with web servers is to
install Python 3 and in a terminal, go into the directory of the HTML file and
run the command `python3 -m http.server`.

In order for the data visualization to work, you need to first download your
data from OGS and put it in the same directory as the HTML file in a file named
`ogs-data.json`. The easiest way to get this data is from this website [https://avavt.github.io/gotstats/#/](https://avavt.github.io/gotstats/#/).

This code is super rough, so there might be bugs.

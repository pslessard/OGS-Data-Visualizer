### "Installation"
This needs to be run in a web server since it needs to access local files. A
simple(ish) way to do this if you don't have experience with web servers is to
install Python 3 and in a terminal, go into the directory of the HTML file and
run the command `python3 -m http.server`. Then you can go to http://localhost:8000/go-d3.html in your web browser.

In order for the data visualization to work, you need to first download your
data from OGS and put it in the same directory as the HTML file in a file named
`ogs-data.json`. The easiest way to get this data is from this website [https://avavt.github.io/gotstats/#/](https://avavt.github.io/gotstats/#/).

### Controls
Click the checkboxes to filter data. If there's another filter you want, let me
know, I can look into adding it when I have time.
Click and drag within the graph to zoom in. Double click to zoom back out.

### Disclaimer
This code is super rough, so there might be bugs.
Also, the rank displayed is approximation. The data only contains a rating, and
to calculate a rank, I just took a sample of data points from my own data and
ran linear regression on them. That's why dan ranks are listed as negative
numbers (and are not accurate. ie. a rank of -2 is not necessarily equal to 2
dan)

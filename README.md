# Pickles

Experiments in pickling (data serialization) in Golang and Python.

## Motivation

Parsing input data for machine learning is a time-intensive process.

It's a recommended practice to serialize this data (pickle it) so as
to reduce the overhead of continually processing input data - especially
for static datasets.

For a number of reasons, machine learning is normally carried out
in Python. But as I was trying out
[Golang for machine learning](http://github.com/mramshaw/gophernet) 
it seemed like a good idea to look into pickling and whether or not
it could be done in a language-agnostic way.

## To Do

- [ ] Investigate Golang serialiazation formats (gob)

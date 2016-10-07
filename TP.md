#!/bin/bash
ls | grep *.java
ls | grep *.java | count

for f in $(find -name \*.java)
do
echo $f
done

echo off
set path=C:\Program Files\bin
set C:\Program Files\include
set lib=C:\Program Files\lib
set link=C:\Program Files\bin

javac -version Main.java
java Main
javap -c Main > Run.txt
javadoc Main.java -d Malovichko_Lab1
pause
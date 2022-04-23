# tutorials-dittaa

[ditaa](http://ditaa.sourceforge.net) can help you convert ascii art diagram into an actual picture.
This repo provide a list of example ascii diagram and its picture created from ditaa.
Please follow this blog post for how to run ditaa: https://blog.ghost.birdbyrd.dev/ditaa-ekhruue-ngmuue-thamaephnphaaphsamhrabkhnrak-ascii-art/

```
     Start
       |
       V
  +----+-----+       +--------------+            +-----+
  | cf3f     |       | {io}         |  3) done   | cGRE|
  | check in +------>+ show choices +----------->+ END |
  |          |       | c333         |            |     |
  +----------+       +--+--------+--+            +-----+
                        |        |  2) Share Facebook
         1) Add Details |        \--------\
                        V                 |
                   +----+----+            V
                   |         |        +---+---+
                   + details +        |       |
                   | cORA    |        + share +
                   +----+----+        | cBLU  |
                        |             +---+---+
                        |      +-----+    |
                        |      | cGRE|    |
                        \----->+ END +<---/
                               |     |
                               +-----+
```
![ditaa tutorial on birdbyrd.com](http://blog.ghost.birdbyrd.dev/content/images/2017/02/ditaa.png)

# Quick run guide:

- download ditaa from here https://sourceforge.net/projects/ditaa/
- create ascii text file (you can use files in this repo)
- perform these commands

```
$ cd /to/ditaa
$ java -jar ditaa.jar /ascii/text/file.txt /export/to/image.png
```

Enjoy!

## Quick references:

```
+------+  /--------------+
| rect |  | rounded rect |
+------+  +--------------/
```
![rect](https://github.com/birdbyrd/tutorials-dittaa/blob/master/src/rect.png?raw=true)


```
+------+  /--------------+
| rect |  | rounded rect |
| cF00 |  | cGRE         |
+------+  +--------------/
```
![colored rect](https://github.com/birdbyrd/tutorials-dittaa/blob/master/src/rect-color.png?raw=true)

```
+----------+ +----------+ +----------+
| {d}      | | {s}      | | {io}     |
| document | | storage  | | in / out |
| c00F     | | cYEL     | |          |
+----------+ +----------+ +----------+
```
![document storage inout](https://github.com/birdbyrd/tutorials-dittaa/blob/master/src/document-storage-inout.png?raw=true)

```
+----------+
|     c666 |
|   +------+
|   | c333 |
+---+------+
|  c000    |
+----------+
```
![box in box](https://raw.githubusercontent.com/birdbyrd/tutorials-dittaa/master/src/box-in-box.png)

```
             +---+--+
             |      |
             + c0F0 +
             |      |
             +---+--+
                 ^
                 |
                 |
+------+     +---+--+     +------+  
|      |     |      |     |      |  
| cF00 +<----+ c000 +---->+ c00F |  
|      |     |      |     |      |  
+------+     +---+--+     +------+
                 |
                 |
                 \---\
                     |
                     |
                 /---/
                 |
                 |
                 V
             +---+--+
             |      |
             + c369 +
             |      |
             +---+--+
```
![line](https://github.com/birdbyrd/tutorials-dittaa/blob/master/src/line.png?raw=true)

```
+--=---+     +---+--+
|      |     |      |
: cF00 +-=-->+ c000 |
|      |     |      |
+--=---+     +---+--+
```
![dashed line](https://github.com/birdbyrd/tutorials-dittaa/blob/master/src/dashed-line.png?raw=true)

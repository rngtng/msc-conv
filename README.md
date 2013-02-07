# MscConv

A simple [websequencediagrams](http://websequencediagrams.com) to [msc-gen](http://www.mcternan.me.uk/mscgen/) converter


## Usage

```
cat examples/example1.wsd | msc-conv
```


show:
```
(cat examples/example1.wsd | msc-conv > /tmp/out.msc && mscgen -T png /tmp/out.msc && open /tmp/out.msc.png
```


## TODO
  * gemify
  * support  output format for [Msc-Generator](http://msc-generator.sourceforge.net)
  * structure cleanup -> mv classes into dedicated files?

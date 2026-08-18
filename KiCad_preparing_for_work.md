# KiCad preparing for work (rev 1.1)

## 1. Obtain Barsotion KiCad libraries

```
git clone git@github.com:Barsotion/kicad-lib.git
kilm setup
```

For updating from server:

```
git pull
kilm setup
```

Be shore there are no critical errors:

![](./photos/p1.png)

## Turn off standard KiCad libraries pack

On the main KiCad menu, Preferences -> Manage Symbol Libraries...:

![](./photos/p2.png)

On the main KiCad menu, Preferences -> Manage Footprint Libraries...:

![](./photos/p3.png)

On the main KiCad menu, Preferences -> Preferences...:

![](./photos/p4.jpg)

![](./photos/p5.jpg)

You should to install a [GOST type B](./gost_type_b.ttf) font.

![](./photos/p6.jpg)

![](./photos/p7.jpg)

![](./photos/p8.jpg)

![](./photos/p9.jpg)

![](./photos/p10.jpg)

Then, your KiCad is ready to work.

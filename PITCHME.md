#HSLIDE

# Omeletes sem Ovos
### A poor man's GIS

#HSLIDE

![ola](assets/ola.jpg)

#HSLIDE

# <span style="color:#e49436">"</span>
### The only source of knowledge is experience
<span style="font-size:0.6em; color:gray">Albert Einstein</span>

#HSLIDE

# <span style="color:#e49436">"</span>
### A jack of all trades is a master of none,<!-- .element: class="fragment" -->
### but oftentimes better than a master of one!
<span style="font-size:0.6em; color:gray">alguém mais inteligente que eu</span>


#HSLIDE

![culpa](assets/culpa.png)

#HSLIDE

## No fundo...

+ conceito <!-- .element: class="fragment" -->
+ ideia <!-- .element: class="fragment" -->
+ ... <!-- .element: class="fragment" -->

#HSLIDE

![manifesto](assets/manifesto.png)


#HSLIDE

![omeletes](assets/oso.png)

#HSLIDE

![hmmm](assets/hmmm.gif)

#HSLIDE

## Tudo começa com um problema!

---?image=assets/stuck_dog.jpg&size=auto 90%

---?image=assets/cat_tank.jpg&size=auto 90%

---?image=assets/it_guy.jpg&size=auto 85%

---?image=assets/bruce.gif&size=auto

#HSLIDE

## Soluções?
+ explicar o problema <!-- .element: class="fragment" -->
+ mostrar um caminho <!-- .element: class="fragment" -->
+ ... <!-- .element: class="fragment" -->
+ continuar <!-- .element: class="fragment" -->

<span style="font-size:0.6em; color:gray">Porque realmente só estva a perder tempo e a aumentar os níveis de frustração</span>

---?image=assets/computer_panda.gif&size=auto


#HSLIDE

## Go <span style="color:#e49436">portable</span>

---?image=assets/go_portable.png&size=auto 90%

#HSLIDE

## OK...
### mas e as aplicações de <span style="color:#e49436">SIG</span>?

#HSLIDE
+ gvSIG <!-- .element: class="fragment" --> 
+ uDig <!-- .element: class="fragment" --> 
+ openJUMP <!-- .element: class="fragment" -->  
+ Saga GIS <!-- .element: class="fragment" -->
+ PostreSQl + PostGIS <!-- .element: class="fragment" -->
+ Spatialite <!-- .element: class="fragment" -->
+ entre outros <!-- .element: class="fragment" -->

#HSLIDE

## Portable
![gvsig](assets/gvsig.png)
![udig](assets/udig.png)
![openjump](assets/openjump.png)
![sagagis](assets/saga.jpeg)
![postgis](assets/postgis.png)
![spatialite](assets/spatialite.jpg)

### então e o <span style="color:#e49436">QGIS</span>?

#HSLIDE

### Um pouco mais trabalho, mas...

- [https://github.com/Frederikssund/Alternativ-QGIS-installation](http://bit.ly/2z9GU0D)

![github](assets/portable_qgis.png)

#HSLIDE

## E para quem não quer ter trabalho nenhum
### Existe o projecto da <span style="color:#e49436">Jo Cook</span>

![portable_gis](assets/portable_gis.png)

#HSLIDE

+ Desktop GIS packages QGIS version 2.18.11 LTR
+ FWTools (GDAL and OGR toolkit)
+ Apache2 and Php5
+ PostgreSQL (version 9.1)/Postgis (version 2.1)
+ Mapserver 5.6 and 6, OpenLayers
+ Python 2.7 with GDAL 1.9 libraries and Psycopg2
+ ...
+ Geoserver 2.8
+ Utilities- portable firefox, pdf reader and text editor

---?image=assets/sucess.jpg&size=auto 90%

#HSLIDE

---?image=assets/disney.gif&size=auto

---?image=assets/cat_fail.gif&size=auto

#HSLIDE

### Podemos começar de forma <span style="color:#e49436">simples</span>

### Serverless mode

+ Spatialite <!-- .element: class="fragment" -->
+ Geopackage

#HSLIDE

### QGIS Virtual Layers

---?image=assets/qgis_virtual.png&size=auto

---?image=assets/goat.gif&size=auto

#HSLIDE

![odk](assets/qgis_odk.png)
![ona](assets/odk_ona.png)








## Benchmarks

#### Unfortunately, <span style="color:#e49436">ActionCable</span> leaves much to be desired

<span style="font-size:0.6em; color:gray">Press Down key to see charts and gifs</span>

#VSLIDE

## Memory

![memory](assets/Memory3.png)

#VSLIDE

## CPU

![cpu](assets/cpu_chart.gif)

#VSLIDE

## Broadcast Round Trip Time

![rtt](assets/RTT3.png)

#HSLIDE

### Let's extract <span style="color:#e49436">WebSockets</span> somewhere else!

#HSLIDE

## AnyCable

#### Combines the good parts from <span style="color:#e49436">ActionCable</span> with the power of your favorite language for concurrent applications

<span style="font-size:0.6em; color:gray">How it works? See below</span>

#VSLIDE

## How AnyCable Works

![diagram](assets/Scheme2.png)

#VSLIDE

## [gRPC](http://grpc.io)

### Makes AnyCable to be a <span style="color:#e49436">polyglot</span>

#VSLIDE

## AnyCable

#### [Compatible](https://github.com/anycable/anycable#actioncable-compatibility) with ActionCable (channels, javascript, broadcasting)

#### You can still use ActionCable for <span style="color:#e49436">development</span> and <span style="color:#e49436">testing</span>

#VSLIDE

## AnyCable Servers

- [anycable-go](https://github.com/anycable/anycable-go)

- [erlycable](https://github.com/anycable/erlycable)

#VSLIDE

## AnyCable

### [Demo Application](https://github.com/anycable/anycable_demo)

#HSLIDE

## Benchmarks Again

#### AnyCable shows much more better performance.

<span style="font-size:0.6em; color:gray">Press Down key to see charts and gifs</span>

#VSLIDE

## Memory

![memory](assets/Memory5.png)

#VSLIDE

## CPU

![cpu](assets/cpu_chart2.gif)

#VSLIDE

## Broadcast Round Trip Time

![rtt](assets/RTT5.png)


#HSLIDE

## Let's Make ActionCable Not Suck!

[anycable.evilmartians.io](http://anycable.io/)

Vladimir Dementyev [@palkan_tula](http://twitter.com/palkan_tula)

[Evil Martians](http://evilmartians.com)

Twitter [@any_cable](http://twitter.com/any_cable)

GitHub [@anycable](http://github.com/anycable)

This image is designed to provide a simple way to execute Pascal programs on an arbitrary platform.
For the moment, the available programs are MoKa and Braids, two softwares that manipulate algebraic structures
called "gcd-monoids" (MoKa) and braids (Braids).

####How use it

To use the image you need [Docker](http://docker.io) installed on your system.

Once installed Docker, you can use this image to run MoKa without install MoKa directly on your machine.

#####Basic usage

        docker pull dehornoy/programs
        docker run -it dehornoy/programs
        XXX with XXX = "MoKa" or XXX = "Braids"

#####MoKa

The MoKa program implements various algorithms for working in a monoid defined by a complemented presentation, typically an Artin-Tits monoid, and in its enveloping group. The elements of the monoid are handled via words in the alphabet of the specified presentation; the elements of the enveloping group are specified by signed words, or by multifractions, i.e., finite sequences of elements of the monoid. The main tools are subword reversing for the elements of the monoid, and multifraction reduction for those of the group.

#####Braids

The Braids program performs simple braid operations, in particular involving orders. The main comparison tool is handle reduction, which, starting with an arbitrary braid word, returns an equivalent sigma-definite word (the generator with lowest index does not appear both positively and negatively).

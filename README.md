This image is designed to provide a simple way to execute Pascal programs on an arbitrary platform.
For the moment, the only available program is MoKa, a software that manipulates algebraic structures
called "gcd-monoids".

####How use it

To use the image you need [Docker](http://docker.io) installed on your system.

Once installed Docker, you can use this image to run MoKa without install MoKa directly on your machine.

#####Basic usage

        docker pull dehornoy/programs
        docker run -it dehornoy/programs
        MoKa


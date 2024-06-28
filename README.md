Code for the 4th Pythia exercise about Z pt.
To be able to run it you need to be in the Pythia docker environment.
So from this git directory run the following command : 

$ docker run -v $PWD:/host -w /host -it --rm hepstore/rivet-pythia
$ pythia8-main93 -c main93_IV.cmnd -o [Output Name]

You will get a log output and a yoda output.

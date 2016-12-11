# Geo_Satellite
A model of a Satellite orbiting the Earth


ONLY EDIT THIS ON A MAC!!!

If you want to edit it on a mac, do the following:

1. Install Homebrew - its basically a package manager that helps you download files on Mac with like 0 hassle

open terminal and put in the lines:

```
ruby -e "$(curl -fsSkL raw.github.com/mxcl/homebrew/go)"

```

then go to your bash profile and put this line in

```
 export PATH=/usr/local/bin:/usr/local/share/python:$PATH

```

2. Install Python

```
 brew install python

```

Then (you're gonna need to enter your password for this one):

```
 sudo easy_install pip

```
Now we gotta install a couple other things:

3. Numpy:

```
 pip install numpy

```

4. Scipy

First install gfortran (its included in the gcc package so no worries): 

```
brew install gcc

```

If that works, jump to installing scipy.

If it didn't work and you ran into an error while installing, try:

```
brew link gcc

```

If that doesn't work, then we have to fix the symlink. To do that, then do:


```
cd /usr/local/

```

Then:

```
sudo chown -R <your-username> *
```

After you fix the permissions, then you can go back to create a symlink, so:

```
brew link gcc

```

Ayye bet it works now. So, now, go install scipy:


```
 pip install scipy

```



5. Matplotlib (the most important one):

First:

```
brew install pkg-config

```

Then:

```
pip install matplotlib

```

If the "pip install" doesn't work, try this:

```
pip install git+git://github.com/matplotlib/matplotlib.git

```


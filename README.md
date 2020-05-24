# Forked from CoDrone-python
python package for codrone

repo: https://github.com/RobolinkInc/CoDrone-python.git
Homepage: https://www.robolink.com/

## Why fork it?
I noticed that the library was really slow, so I inspected the source code and I found out that there are a lot of seemingly useless ```sleep``` statements (probably because the original devs didn't do multithreading right, they shouldn't have used multithreading in the beginning imo because this package doesn't need it, and the codebase isn't very strong either). Also the original package lacks a humane documentations so I won't be able to provide any
Using this the drone is noticibly more responsive

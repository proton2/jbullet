jbullet
=======

This is non-official mavenisation of jbullet library. See http://jbullet.advel.cz/ for original project details.

My changes comparing with original https://github.com/jbullet-maven/jbullet version:
- Stack.alloc replaced by creating from constructor by new (to avoid some crashes);
- ObjectArrayList replaced by CopyOnWriteArrayList for thread safety;
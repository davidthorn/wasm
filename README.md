# Web Assembly

So, and I always like to start my read me's with So.

I know quite a bit about C and C++, I would not stay that I am a master at it, but I can write the basics of stuff.

The thing was that I could never find a good reason to use either because I generally always do web development or app development using Swift, PHP and javascript.

After watching a couple of videos on youtube about the `wasm` I noticed that I could write some code in `C` or `C++` and use it directly in the browser. This makes `wasm` really interesting!

## Creating a Basic (useless) C program 

So, lets start by making the most basic `C`program to get it compiled and running.

```c
#include <stdio.h>

int main(int argc , char ** argv) {

    printf("Hello world\n");

}
```

### Compiling our useless C program

Now lets compile it into a executable called `main` using the flag `-o`.

```bash
gcc -o main main.c
```

### Running our useless program

Now we can run our new amazing application.

```bash
./main
Hello world
```

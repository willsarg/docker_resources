# hello_cow readme

Riffing off of "Hello World!", hello_cow takes a basic ubuntu image, updates it because that's like washing your hands, and installs cowsay from apt.

Then it calls the cowsay program with "Container Ran Successfully!"

Build Instructions:
1. Download the dockerfile
2. Run: "docker build -t hello_cow ." in the directory containing the dockerfile
    - Tip for beginners, the period at the end there is important shorthand for telling docker to look in the current directory for the dockerfile.
3. docker run hello_cow

Expected Output
```
 _____________________________
< Container Ran Successfully! >
 -----------------------------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
```
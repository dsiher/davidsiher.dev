+++
title = "A heterogenous graphics language"
date = 2021-03-20
draft = false

[extra]
links = [{name="Github", url="https://github.com/dsiher/slang"}]
+++

Currently, graphics programming relies on writing CPU host code (written in a CPU
language such as C++) that will then execute GPU shaders (written in a shading 
language such as HLSL). This opens the door to a variety of bugs that thrive in 
this CPU-GPU disconnect. [Slang][] took the first steps towards bridging this gap
by giving programmers the ability to compile from slang to both CPU and GPU targets.
I am currently working on extending Slang to see how it might support fully heterogeneous compilation,
allowing programmers to specify and execute an entire graphics pipeline from within
a single .slang file.

[slang]: https://github.com/shader-slang/slang
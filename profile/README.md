The FaVOR ISA is an experimental ISA I created for my CS 692 "Advanced Computer Architecture"
term project.

For the project, I partially implemented the ISA in GNU binutils, including an emulator for
it. I also partially implemented (a version of) the ISA in Verilog for an FPGA.

The core features that the ISA wanted to explore include:
- Support for fixed-point operations.
- A focus on vector values that can also be operated on as individual components (common
  in game development).
- ISA-level consideration of pointer tagging, including explicitly dropping support for
  unaligned value access. This feature is also based on my experience with C programming
  and using pointer tagging.
- A clean ABI, fixing many of the gripes I have with existing ABIs.

See also the [report](https://raw.githubusercontent.com/favor-isa/.github/refs/heads/main/FaVOR%20ISA.pdf) on the ISA that I prepared for my class.

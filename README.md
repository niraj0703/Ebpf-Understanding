# Ebpf-Understanding
**practical use case of ebpf**
>default gcc command detail

- /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -imultiarch x86_64-linux-gnu test.c -quiet -dumpbase test.c -mtune=generic -march=x86-64 -auxbase test -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security
- as --64 -o /tmp/ccdhQCIc.o /tmp/cc6mYHD9.s
- as --64 -o /tmp/ccdhQCIc.o /tmp/cc6mYHD9.s
- as --64 -o /tmp/ccdhQCIc.o /tmp/cc6mYHD9.s
- as --64 -o /tmp/ccdhQCIc.o /tmp/cc6mYHD9.s
- /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cctZPs9c.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed
- /usr/bin/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cctZPs9c.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed

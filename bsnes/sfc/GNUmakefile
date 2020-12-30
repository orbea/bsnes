processors += wdc65816 spc700 arm7tdmi

objects += sfc-interface sfc-system sfc-controller
objects += sfc-cartridge sfc-memory
objects += sfc-cpu sfc-smp sfc-dsp sfc-ppu sfc-ppu-fast
objects += sfc-expansion sfc-coprocessor sfc-slot

obj/sfc-interface.o:   $(srcdir)/sfc/interface/interface.cpp maketree
obj/sfc-system.o:      $(srcdir)/sfc/system/system.cpp maketree
obj/sfc-controller.o:  $(srcdir)/sfc/controller/controller.cpp maketree
obj/sfc-cartridge.o:   $(srcdir)/sfc/cartridge/cartridge.cpp maketree
obj/sfc-memory.o:      $(srcdir)/sfc/memory/memory.cpp maketree

obj/sfc-cpu.o:         $(srcdir)/sfc/cpu/cpu.cpp maketree
obj/sfc-smp.o:         $(srcdir)/sfc/smp/smp.cpp maketree
obj/sfc-dsp.o:         $(srcdir)/sfc/dsp/dsp.cpp maketree
obj/sfc-ppu.o:         $(srcdir)/sfc/ppu/ppu.cpp maketree
obj/sfc-ppu-fast.o:    $(srcdir)/sfc/ppu-fast/ppu.cpp maketree

obj/sfc-expansion.o:   $(srcdir)/sfc/expansion/expansion.cpp maketree
obj/sfc-coprocessor.o: $(srcdir)/sfc/coprocessor/coprocessor.cpp maketree
obj/sfc-slot.o:        $(srcdir)/sfc/slot/slot.cpp maketree

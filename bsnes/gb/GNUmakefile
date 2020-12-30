flags += -DGB_INTERNAL -DGB_DISABLE_DEBUGGER -DGB_DISABLE_CHEATS -D_GNU_SOURCE -Wno-multichar
options += -I../sameboy

objects += gb-apu gb-camera gb-rumble gb-display gb-gb gb-joypad gb-mbc
objects += gb-memory gb-printer gb-random gb-rewind gb-save_state gb-sgb
objects += gb-sm83_cpu gb-symbol_hash gb-timing
#objects+= gb-debugger gb-sm83_disassembler

obj/gb-apu.o:               $(srcdir)/gb/Core/apu.c
obj/gb-camera.o:            $(srcdir)/gb/Core/camera.c
obj/gb-debugger.o:          $(srcdir)/gb/Core/debugger.c
obj/gb-rumble.o:            $(srcdir)/gb/Core/rumble.c
obj/gb-display.o:           $(srcdir)/gb/Core/display.c
obj/gb-gb.o:                $(srcdir)/gb/Core/gb.c
obj/gb-joypad.o:            $(srcdir)/gb/Core/joypad.c
obj/gb-mbc.o:               $(srcdir)/gb/Core/mbc.c
obj/gb-memory.o:            $(srcdir)/gb/Core/memory.c
obj/gb-printer.o:           $(srcdir)/gb/Core/printer.c
obj/gb-random.o:            $(srcdir)/gb/Core/random.c
obj/gb-rewind.o:            $(srcdir)/gb/Core/rewind.c
obj/gb-save_state.o:        $(srcdir)/gb/Core/save_state.c
obj/gb-sgb.o:               $(srcdir)/gb/Core/sgb.c
obj/gb-sm83_cpu.o:          $(srcdir)/gb/Core/sm83_cpu.c
obj/gb-sm83_disassembler.o: $(srcdir)/gb/Core/sm83_disassembler.c
obj/gb-symbol_hash.o:       $(srcdir)/gb/Core/symbol_hash.c
obj/gb-timing.o:            $(srcdir)/gb/Core/timing.c

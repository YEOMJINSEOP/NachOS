# NOTE: this is a GNU Makefile.  You must use "gmake" rather than "make".
#
# Makefile for the multiprogramming assignment
#    Defines set up assuming multiprogramming is done before the file system.
#    If not, use the "filesys first"  defines below. 
#
#
# Copyright (c) 1992-1996 The Regents of the University of California.
# All rights reserved.  See copyright.h for copyright notice and limitation 
# of liability and disclaimer of warranty provisions.

DEFINES = -DTHREADS -DUSER_PROGRAM -DFILESYS_NEEDED -DFILESYS_STUB
INCPATH = -I../bin -I../filesys -I../userprog -I../threads -I../machine -I../lib
HFILES = $(THREAD_H) $(USERPROG_H)
CFILES = $(THREAD_C) $(USERPROG_C)
C_OFILES = $(THREAD_O) $(USERPROG_O)

include ../Makefile.common
include ../Makefile.dep
#-----------------------------------------------------------------
# DO NOT DELETE THIS LINE -- make depend uses it
# DEPENDENCIES MUST END AT END OF FILE
bitmap.o: ../lib/bitmap.cc ../lib/copyright.h ../lib/debug.h \
  ../lib/utility.h ../lib/sysdep.h /usr/include/g++-3/iostream.h \
  /usr/include/g++-3/streambuf.h /usr/include/libio.h \
  /usr/include/_G_config.h /usr/include/bits/types.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stddef.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/sched.h \
  /usr/include/wchar.h /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stdarg.h \
  /usr/include/stdlib.h /usr/include/sys/types.h /usr/include/time.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/sys/select.h /usr/include/bits/select.h \
  /usr/include/bits/sigset.h /usr/include/bits/time.h \
  /usr/include/sys/sysmacros.h /usr/include/alloca.h /usr/include/stdio.h \
  /usr/include/bits/stdio_lim.h /usr/include/string.h ../lib/bitmap.h
debug.o: ../lib/debug.cc ../lib/copyright.h ../lib/utility.h \
  ../lib/debug.h ../lib/sysdep.h /usr/include/g++-3/iostream.h \
  /usr/include/g++-3/streambuf.h /usr/include/libio.h \
  /usr/include/_G_config.h /usr/include/bits/types.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stddef.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/sched.h \
  /usr/include/wchar.h /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stdarg.h \
  /usr/include/stdlib.h /usr/include/sys/types.h /usr/include/time.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/sys/select.h /usr/include/bits/select.h \
  /usr/include/bits/sigset.h /usr/include/bits/time.h \
  /usr/include/sys/sysmacros.h /usr/include/alloca.h /usr/include/stdio.h \
  /usr/include/bits/stdio_lim.h /usr/include/string.h
hash.o: ../lib/hash.cc ../lib/copyright.h
libtest.o: ../lib/libtest.cc ../lib/copyright.h ../lib/libtest.h \
  ../lib/bitmap.h ../lib/utility.h ../lib/list.h ../lib/debug.h \
  ../lib/sysdep.h /usr/include/g++-3/iostream.h \
  /usr/include/g++-3/streambuf.h /usr/include/libio.h \
  /usr/include/_G_config.h /usr/include/bits/types.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stddef.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/sched.h \
  /usr/include/wchar.h /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stdarg.h \
  /usr/include/stdlib.h /usr/include/sys/types.h /usr/include/time.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/sys/select.h /usr/include/bits/select.h \
  /usr/include/bits/sigset.h /usr/include/bits/time.h \
  /usr/include/sys/sysmacros.h /usr/include/alloca.h /usr/include/stdio.h \
  /usr/include/bits/stdio_lim.h /usr/include/string.h ../lib/list.cc \
  ../lib/hash.h ../lib/hash.cc
list.o: ../lib/list.cc ../lib/copyright.h
sysdep.o: ../lib/sysdep.cc ../lib/copyright.h ../lib/debug.h \
  ../lib/utility.h ../lib/sysdep.h /usr/include/g++-3/iostream.h \
  /usr/include/g++-3/streambuf.h /usr/include/libio.h \
  /usr/include/_G_config.h /usr/include/bits/types.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stddef.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/sched.h \
  /usr/include/wchar.h /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stdarg.h \
  /usr/include/stdlib.h /usr/include/sys/types.h /usr/include/time.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/sys/select.h /usr/include/bits/select.h \
  /usr/include/bits/sigset.h /usr/include/bits/time.h \
  /usr/include/sys/sysmacros.h /usr/include/alloca.h /usr/include/stdio.h \
  /usr/include/bits/stdio_lim.h /usr/include/string.h \
  /usr/include/unistd.h /usr/include/bits/posix_opt.h \
  /usr/include/bits/confname.h /usr/include/getopt.h \
  /usr/include/sys/time.h /usr/include/sys/file.h /usr/include/fcntl.h \
  /usr/include/bits/fcntl.h /usr/include/sys/socket.h \
  /usr/include/sys/uio.h /usr/include/bits/uio.h \
  /usr/include/bits/socket.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/sockaddr.h \
  /usr/include/asm/socket.h /usr/include/asm/sockios.h \
  /usr/include/sys/un.h /usr/include/signal.h /usr/include/bits/signum.h \
  /usr/include/bits/siginfo.h /usr/include/bits/wordsize.h \
  /usr/include/bits/sigaction.h /usr/include/bits/sigcontext.h \
  /usr/include/asm/sigcontext.h /usr/include/bits/sigstack.h \
  /usr/include/bits/sigthread.h
interrupt.o: ../machine/interrupt.cc ../lib/copyright.h \
  ../machine/interrupt.h ../lib/list.h ../lib/debug.h ../lib/utility.h \
  ../lib/sysdep.h /usr/include/g++-3/iostream.h \
  /usr/include/g++-3/streambuf.h /usr/include/libio.h \
  /usr/include/_G_config.h /usr/include/bits/types.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stddef.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/sched.h \
  /usr/include/wchar.h /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stdarg.h \
  /usr/include/stdlib.h /usr/include/sys/types.h /usr/include/time.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/sys/select.h /usr/include/bits/select.h \
  /usr/include/bits/sigset.h /usr/include/bits/time.h \
  /usr/include/sys/sysmacros.h /usr/include/alloca.h /usr/include/stdio.h \
  /usr/include/bits/stdio_lim.h /usr/include/string.h ../lib/list.cc \
  ../machine/callback.h ../threads/main.h ../userprog/userkernel.h \
  ../threads/kernel.h ../threads/thread.h ../machine/machine.h \
  ../machine/translate.h ../userprog/addrspace.h ../filesys/filesys.h \
  ../filesys/openfile.h ../threads/scheduler.h ../machine/stats.h \
  ../threads/alarm.h ../machine/timer.h
stats.o: ../machine/stats.cc ../lib/copyright.h ../lib/debug.h \
  ../lib/utility.h ../lib/sysdep.h /usr/include/g++-3/iostream.h \
  /usr/include/g++-3/streambuf.h /usr/include/libio.h \
  /usr/include/_G_config.h /usr/include/bits/types.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stddef.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/sched.h \
  /usr/include/wchar.h /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stdarg.h \
  /usr/include/stdlib.h /usr/include/sys/types.h /usr/include/time.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/sys/select.h /usr/include/bits/select.h \
  /usr/include/bits/sigset.h /usr/include/bits/time.h \
  /usr/include/sys/sysmacros.h /usr/include/alloca.h /usr/include/stdio.h \
  /usr/include/bits/stdio_lim.h /usr/include/string.h ../machine/stats.h
timer.o: ../machine/timer.cc ../lib/copyright.h ../machine/timer.h \
  ../lib/utility.h ../machine/callback.h ../threads/main.h ../lib/debug.h \
  ../lib/sysdep.h /usr/include/g++-3/iostream.h \
  /usr/include/g++-3/streambuf.h /usr/include/libio.h \
  /usr/include/_G_config.h /usr/include/bits/types.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stddef.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/sched.h \
  /usr/include/wchar.h /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stdarg.h \
  /usr/include/stdlib.h /usr/include/sys/types.h /usr/include/time.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/sys/select.h /usr/include/bits/select.h \
  /usr/include/bits/sigset.h /usr/include/bits/time.h \
  /usr/include/sys/sysmacros.h /usr/include/alloca.h /usr/include/stdio.h \
  /usr/include/bits/stdio_lim.h /usr/include/string.h \
  ../userprog/userkernel.h ../threads/kernel.h ../threads/thread.h \
  ../machine/machine.h ../machine/translate.h ../userprog/addrspace.h \
  ../filesys/filesys.h ../filesys/openfile.h ../threads/scheduler.h \
  ../lib/list.h ../lib/list.cc ../machine/interrupt.h ../machine/stats.h \
  ../threads/alarm.h
alarm.o: ../threads/alarm.cc ../lib/copyright.h ../threads/alarm.h \
  ../lib/utility.h ../machine/callback.h ../machine/timer.h \
  ../threads/main.h ../lib/debug.h ../lib/sysdep.h \
  /usr/include/g++-3/iostream.h /usr/include/g++-3/streambuf.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/bits/types.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stddef.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/sched.h \
  /usr/include/wchar.h /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stdarg.h \
  /usr/include/stdlib.h /usr/include/sys/types.h /usr/include/time.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/sys/select.h /usr/include/bits/select.h \
  /usr/include/bits/sigset.h /usr/include/bits/time.h \
  /usr/include/sys/sysmacros.h /usr/include/alloca.h /usr/include/stdio.h \
  /usr/include/bits/stdio_lim.h /usr/include/string.h \
  ../userprog/userkernel.h ../threads/kernel.h ../threads/thread.h \
  ../machine/machine.h ../machine/translate.h ../userprog/addrspace.h \
  ../filesys/filesys.h ../filesys/openfile.h ../threads/scheduler.h \
  ../lib/list.h ../lib/list.cc ../machine/interrupt.h ../machine/stats.h
kernel.o: ../threads/kernel.cc ../lib/copyright.h ../lib/debug.h \
  ../lib/utility.h ../lib/sysdep.h /usr/include/g++-3/iostream.h \
  /usr/include/g++-3/streambuf.h /usr/include/libio.h \
  /usr/include/_G_config.h /usr/include/bits/types.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stddef.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/sched.h \
  /usr/include/wchar.h /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stdarg.h \
  /usr/include/stdlib.h /usr/include/sys/types.h /usr/include/time.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/sys/select.h /usr/include/bits/select.h \
  /usr/include/bits/sigset.h /usr/include/bits/time.h \
  /usr/include/sys/sysmacros.h /usr/include/alloca.h /usr/include/stdio.h \
  /usr/include/bits/stdio_lim.h /usr/include/string.h ../threads/main.h \
  ../userprog/userkernel.h ../threads/kernel.h ../threads/thread.h \
  ../machine/machine.h ../machine/translate.h ../userprog/addrspace.h \
  ../filesys/filesys.h ../filesys/openfile.h ../threads/scheduler.h \
  ../lib/list.h ../lib/list.cc ../machine/interrupt.h \
  ../machine/callback.h ../machine/stats.h ../threads/alarm.h \
  ../machine/timer.h ../threads/synch.h ../threads/synchlist.h \
  ../threads/synchlist.cc ../lib/libtest.h ../machine/elevatortest.h
main.o: ../threads/main.cc ../lib/copyright.h ../threads/main.h \
  ../lib/debug.h ../lib/utility.h ../lib/sysdep.h \
  /usr/include/g++-3/iostream.h /usr/include/g++-3/streambuf.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/bits/types.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stddef.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/sched.h \
  /usr/include/wchar.h /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stdarg.h \
  /usr/include/stdlib.h /usr/include/sys/types.h /usr/include/time.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/sys/select.h /usr/include/bits/select.h \
  /usr/include/bits/sigset.h /usr/include/bits/time.h \
  /usr/include/sys/sysmacros.h /usr/include/alloca.h /usr/include/stdio.h \
  /usr/include/bits/stdio_lim.h /usr/include/string.h \
  ../userprog/userkernel.h ../threads/kernel.h ../threads/thread.h \
  ../machine/machine.h ../machine/translate.h ../userprog/addrspace.h \
  ../filesys/filesys.h ../filesys/openfile.h ../threads/scheduler.h \
  ../lib/list.h ../lib/list.cc ../machine/interrupt.h \
  ../machine/callback.h ../machine/stats.h ../threads/alarm.h \
  ../machine/timer.h
scheduler.o: ../threads/scheduler.cc ../lib/copyright.h ../lib/debug.h \
  ../lib/utility.h ../lib/sysdep.h /usr/include/g++-3/iostream.h \
  /usr/include/g++-3/streambuf.h /usr/include/libio.h \
  /usr/include/_G_config.h /usr/include/bits/types.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stddef.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/sched.h \
  /usr/include/wchar.h /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stdarg.h \
  /usr/include/stdlib.h /usr/include/sys/types.h /usr/include/time.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/sys/select.h /usr/include/bits/select.h \
  /usr/include/bits/sigset.h /usr/include/bits/time.h \
  /usr/include/sys/sysmacros.h /usr/include/alloca.h /usr/include/stdio.h \
  /usr/include/bits/stdio_lim.h /usr/include/string.h \
  ../threads/scheduler.h ../lib/list.h ../lib/list.cc ../threads/thread.h \
  ../machine/machine.h ../machine/translate.h ../userprog/addrspace.h \
  ../filesys/filesys.h ../filesys/openfile.h ../threads/main.h \
  ../userprog/userkernel.h ../threads/kernel.h ../machine/interrupt.h \
  ../machine/callback.h ../machine/stats.h ../threads/alarm.h \
  ../machine/timer.h
synch.o: ../threads/synch.cc ../lib/copyright.h ../threads/synch.h \
  ../threads/thread.h ../lib/utility.h ../lib/sysdep.h \
  /usr/include/g++-3/iostream.h /usr/include/g++-3/streambuf.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/bits/types.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stddef.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/sched.h \
  /usr/include/wchar.h /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stdarg.h \
  /usr/include/stdlib.h /usr/include/sys/types.h /usr/include/time.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/sys/select.h /usr/include/bits/select.h \
  /usr/include/bits/sigset.h /usr/include/bits/time.h \
  /usr/include/sys/sysmacros.h /usr/include/alloca.h /usr/include/stdio.h \
  /usr/include/bits/stdio_lim.h /usr/include/string.h \
  ../machine/machine.h ../machine/translate.h ../userprog/addrspace.h \
  ../filesys/filesys.h ../filesys/openfile.h ../lib/list.h ../lib/debug.h \
  ../lib/list.cc ../threads/main.h ../userprog/userkernel.h \
  ../threads/kernel.h ../threads/scheduler.h ../machine/interrupt.h \
  ../machine/callback.h ../machine/stats.h ../threads/alarm.h \
  ../machine/timer.h
synchlist.o: ../threads/synchlist.cc ../lib/copyright.h \
  ../threads/synchlist.h ../lib/list.h ../lib/debug.h ../lib/utility.h \
  ../lib/sysdep.h /usr/include/g++-3/iostream.h \
  /usr/include/g++-3/streambuf.h /usr/include/libio.h \
  /usr/include/_G_config.h /usr/include/bits/types.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stddef.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/sched.h \
  /usr/include/wchar.h /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stdarg.h \
  /usr/include/stdlib.h /usr/include/sys/types.h /usr/include/time.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/sys/select.h /usr/include/bits/select.h \
  /usr/include/bits/sigset.h /usr/include/bits/time.h \
  /usr/include/sys/sysmacros.h /usr/include/alloca.h /usr/include/stdio.h \
  /usr/include/bits/stdio_lim.h /usr/include/string.h ../lib/list.cc \
  ../threads/synch.h ../threads/thread.h ../machine/machine.h \
  ../machine/translate.h ../userprog/addrspace.h ../filesys/filesys.h \
  ../filesys/openfile.h ../threads/main.h ../userprog/userkernel.h \
  ../threads/kernel.h ../threads/scheduler.h ../machine/interrupt.h \
  ../machine/callback.h ../machine/stats.h ../threads/alarm.h \
  ../machine/timer.h ../threads/synchlist.cc
thread.o: ../threads/thread.cc ../lib/copyright.h ../threads/thread.h \
  ../lib/utility.h ../lib/sysdep.h /usr/include/g++-3/iostream.h \
  /usr/include/g++-3/streambuf.h /usr/include/libio.h \
  /usr/include/_G_config.h /usr/include/bits/types.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stddef.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/sched.h \
  /usr/include/wchar.h /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stdarg.h \
  /usr/include/stdlib.h /usr/include/sys/types.h /usr/include/time.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/sys/select.h /usr/include/bits/select.h \
  /usr/include/bits/sigset.h /usr/include/bits/time.h \
  /usr/include/sys/sysmacros.h /usr/include/alloca.h /usr/include/stdio.h \
  /usr/include/bits/stdio_lim.h /usr/include/string.h \
  ../machine/machine.h ../machine/translate.h ../userprog/addrspace.h \
  ../filesys/filesys.h ../filesys/openfile.h ../threads/switch.h \
  ../threads/synch.h ../lib/list.h ../lib/debug.h ../lib/list.cc \
  ../threads/main.h ../userprog/userkernel.h ../threads/kernel.h \
  ../threads/scheduler.h ../machine/interrupt.h ../machine/callback.h \
  ../machine/stats.h ../threads/alarm.h ../machine/timer.h
elevatortest.o: ../machine/elevatortest.cc ../lib/copyright.h \
  ../machine/elevatortest.h ../machine/elevator.h ../lib/utility.h \
  ../machine/callback.h ../lib/list.h ../lib/debug.h ../lib/sysdep.h \
  /usr/include/g++-3/iostream.h /usr/include/g++-3/streambuf.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/bits/types.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stddef.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/sched.h \
  /usr/include/wchar.h /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stdarg.h \
  /usr/include/stdlib.h /usr/include/sys/types.h /usr/include/time.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/sys/select.h /usr/include/bits/select.h \
  /usr/include/bits/sigset.h /usr/include/bits/time.h \
  /usr/include/sys/sysmacros.h /usr/include/alloca.h /usr/include/stdio.h \
  /usr/include/bits/stdio_lim.h /usr/include/string.h ../lib/list.cc \
  ../threads/synch.h ../threads/thread.h ../machine/machine.h \
  ../machine/translate.h ../userprog/addrspace.h ../filesys/filesys.h \
  ../filesys/openfile.h ../threads/main.h ../userprog/userkernel.h \
  ../threads/kernel.h ../threads/scheduler.h ../machine/interrupt.h \
  ../machine/stats.h ../threads/alarm.h ../machine/timer.h
elevator.o: ../machine/elevator.cc ../lib/copyright.h \
  ../machine/elevator.h ../lib/utility.h ../machine/callback.h \
  ../lib/list.h ../lib/debug.h ../lib/sysdep.h \
  /usr/include/g++-3/iostream.h /usr/include/g++-3/streambuf.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/bits/types.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stddef.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/sched.h \
  /usr/include/wchar.h /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stdarg.h \
  /usr/include/stdlib.h /usr/include/sys/types.h /usr/include/time.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/sys/select.h /usr/include/bits/select.h \
  /usr/include/bits/sigset.h /usr/include/bits/time.h \
  /usr/include/sys/sysmacros.h /usr/include/alloca.h /usr/include/stdio.h \
  /usr/include/bits/stdio_lim.h /usr/include/string.h ../lib/list.cc \
  ../threads/kernel.h ../threads/thread.h ../machine/machine.h \
  ../machine/translate.h ../userprog/addrspace.h ../filesys/filesys.h \
  ../filesys/openfile.h ../threads/scheduler.h ../machine/interrupt.h \
  ../machine/stats.h ../threads/alarm.h ../machine/timer.h \
  ../threads/main.h ../userprog/userkernel.h
addrspace.o: ../userprog/addrspace.cc ../lib/copyright.h \
  ../threads/main.h ../lib/debug.h ../lib/utility.h ../lib/sysdep.h \
  /usr/include/g++-3/iostream.h /usr/include/g++-3/streambuf.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/bits/types.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stddef.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/sched.h \
  /usr/include/wchar.h /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stdarg.h \
  /usr/include/stdlib.h /usr/include/sys/types.h /usr/include/time.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/sys/select.h /usr/include/bits/select.h \
  /usr/include/bits/sigset.h /usr/include/bits/time.h \
  /usr/include/sys/sysmacros.h /usr/include/alloca.h /usr/include/stdio.h \
  /usr/include/bits/stdio_lim.h /usr/include/string.h \
  ../userprog/userkernel.h ../threads/kernel.h ../threads/thread.h \
  ../machine/machine.h ../machine/translate.h ../userprog/addrspace.h \
  ../filesys/filesys.h ../filesys/openfile.h ../threads/scheduler.h \
  ../lib/list.h ../lib/list.cc ../machine/interrupt.h \
  ../machine/callback.h ../machine/stats.h ../threads/alarm.h \
  ../machine/timer.h ../bin/noff.h /usr/include/strings.h
exception.o: ../userprog/exception.cc ../lib/copyright.h \
  ../threads/main.h ../lib/debug.h ../lib/utility.h ../lib/sysdep.h \
  /usr/include/g++-3/iostream.h /usr/include/g++-3/streambuf.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/bits/types.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stddef.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/sched.h \
  /usr/include/wchar.h /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stdarg.h \
  /usr/include/stdlib.h /usr/include/sys/types.h /usr/include/time.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/sys/select.h /usr/include/bits/select.h \
  /usr/include/bits/sigset.h /usr/include/bits/time.h \
  /usr/include/sys/sysmacros.h /usr/include/alloca.h /usr/include/stdio.h \
  /usr/include/bits/stdio_lim.h /usr/include/string.h \
  ../userprog/userkernel.h ../threads/kernel.h ../threads/thread.h \
  ../machine/machine.h ../machine/translate.h ../userprog/addrspace.h \
  ../filesys/filesys.h ../filesys/openfile.h ../threads/scheduler.h \
  ../lib/list.h ../lib/list.cc ../machine/interrupt.h \
  ../machine/callback.h ../machine/stats.h ../threads/alarm.h \
  ../machine/timer.h ../userprog/syscall.h
synchconsole.o: ../userprog/synchconsole.cc ../lib/copyright.h \
  ../userprog/synchconsole.h ../lib/utility.h ../machine/callback.h \
  ../machine/console.h ../threads/synch.h ../threads/thread.h \
  ../lib/sysdep.h /usr/include/g++-3/iostream.h \
  /usr/include/g++-3/streambuf.h /usr/include/libio.h \
  /usr/include/_G_config.h /usr/include/bits/types.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stddef.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/sched.h \
  /usr/include/wchar.h /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stdarg.h \
  /usr/include/stdlib.h /usr/include/sys/types.h /usr/include/time.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/sys/select.h /usr/include/bits/select.h \
  /usr/include/bits/sigset.h /usr/include/bits/time.h \
  /usr/include/sys/sysmacros.h /usr/include/alloca.h /usr/include/stdio.h \
  /usr/include/bits/stdio_lim.h /usr/include/string.h \
  ../machine/machine.h ../machine/translate.h ../userprog/addrspace.h \
  ../filesys/filesys.h ../filesys/openfile.h ../lib/list.h ../lib/debug.h \
  ../lib/list.cc ../threads/main.h ../userprog/userkernel.h \
  ../threads/kernel.h ../threads/scheduler.h ../machine/interrupt.h \
  ../machine/stats.h ../threads/alarm.h ../machine/timer.h
userkernel.o: ../userprog/userkernel.cc ../lib/copyright.h \
  ../userprog/synchconsole.h ../lib/utility.h ../machine/callback.h \
  ../machine/console.h ../threads/synch.h ../threads/thread.h \
  ../lib/sysdep.h /usr/include/g++-3/iostream.h \
  /usr/include/g++-3/streambuf.h /usr/include/libio.h \
  /usr/include/_G_config.h /usr/include/bits/types.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stddef.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/sched.h \
  /usr/include/wchar.h /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stdarg.h \
  /usr/include/stdlib.h /usr/include/sys/types.h /usr/include/time.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/sys/select.h /usr/include/bits/select.h \
  /usr/include/bits/sigset.h /usr/include/bits/time.h \
  /usr/include/sys/sysmacros.h /usr/include/alloca.h /usr/include/stdio.h \
  /usr/include/bits/stdio_lim.h /usr/include/string.h \
  ../machine/machine.h ../machine/translate.h ../userprog/addrspace.h \
  ../filesys/filesys.h ../filesys/openfile.h ../lib/list.h ../lib/debug.h \
  ../lib/list.cc ../threads/main.h ../userprog/userkernel.h \
  ../threads/kernel.h ../threads/scheduler.h ../machine/interrupt.h \
  ../machine/stats.h ../threads/alarm.h ../machine/timer.h
console.o: ../machine/console.cc ../lib/copyright.h ../machine/console.h \
  ../lib/utility.h ../machine/callback.h ../threads/main.h ../lib/debug.h \
  ../lib/sysdep.h /usr/include/g++-3/iostream.h \
  /usr/include/g++-3/streambuf.h /usr/include/libio.h \
  /usr/include/_G_config.h /usr/include/bits/types.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stddef.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/sched.h \
  /usr/include/wchar.h /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stdarg.h \
  /usr/include/stdlib.h /usr/include/sys/types.h /usr/include/time.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/sys/select.h /usr/include/bits/select.h \
  /usr/include/bits/sigset.h /usr/include/bits/time.h \
  /usr/include/sys/sysmacros.h /usr/include/alloca.h /usr/include/stdio.h \
  /usr/include/bits/stdio_lim.h /usr/include/string.h \
  ../userprog/userkernel.h ../threads/kernel.h ../threads/thread.h \
  ../machine/machine.h ../machine/translate.h ../userprog/addrspace.h \
  ../filesys/filesys.h ../filesys/openfile.h ../threads/scheduler.h \
  ../lib/list.h ../lib/list.cc ../machine/interrupt.h ../machine/stats.h \
  ../threads/alarm.h ../machine/timer.h
machine.o: ../machine/machine.cc ../lib/copyright.h ../machine/machine.h \
  ../lib/utility.h ../machine/translate.h ../threads/main.h \
  ../lib/debug.h ../lib/sysdep.h /usr/include/g++-3/iostream.h \
  /usr/include/g++-3/streambuf.h /usr/include/libio.h \
  /usr/include/_G_config.h /usr/include/bits/types.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stddef.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/sched.h \
  /usr/include/wchar.h /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stdarg.h \
  /usr/include/stdlib.h /usr/include/sys/types.h /usr/include/time.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/sys/select.h /usr/include/bits/select.h \
  /usr/include/bits/sigset.h /usr/include/bits/time.h \
  /usr/include/sys/sysmacros.h /usr/include/alloca.h /usr/include/stdio.h \
  /usr/include/bits/stdio_lim.h /usr/include/string.h \
  ../userprog/userkernel.h ../threads/kernel.h ../threads/thread.h \
  ../userprog/addrspace.h ../filesys/filesys.h ../filesys/openfile.h \
  ../threads/scheduler.h ../lib/list.h ../lib/list.cc \
  ../machine/interrupt.h ../machine/callback.h ../machine/stats.h \
  ../threads/alarm.h ../machine/timer.h
mipssim.o: ../machine/mipssim.cc ../lib/copyright.h ../lib/debug.h \
  ../lib/utility.h ../lib/sysdep.h /usr/include/g++-3/iostream.h \
  /usr/include/g++-3/streambuf.h /usr/include/libio.h \
  /usr/include/_G_config.h /usr/include/bits/types.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stddef.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/sched.h \
  /usr/include/wchar.h /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stdarg.h \
  /usr/include/stdlib.h /usr/include/sys/types.h /usr/include/time.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/sys/select.h /usr/include/bits/select.h \
  /usr/include/bits/sigset.h /usr/include/bits/time.h \
  /usr/include/sys/sysmacros.h /usr/include/alloca.h /usr/include/stdio.h \
  /usr/include/bits/stdio_lim.h /usr/include/string.h \
  ../machine/machine.h ../machine/translate.h ../machine/mipssim.h \
  ../threads/main.h ../userprog/userkernel.h ../threads/kernel.h \
  ../threads/thread.h ../userprog/addrspace.h ../filesys/filesys.h \
  ../filesys/openfile.h ../threads/scheduler.h ../lib/list.h \
  ../lib/list.cc ../machine/interrupt.h ../machine/callback.h \
  ../machine/stats.h ../threads/alarm.h ../machine/timer.h
translate.o: ../machine/translate.cc ../lib/copyright.h ../threads/main.h \
  ../lib/debug.h ../lib/utility.h ../lib/sysdep.h \
  /usr/include/g++-3/iostream.h /usr/include/g++-3/streambuf.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/bits/types.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stddef.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/sched.h \
  /usr/include/wchar.h /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/2.96/include/stdarg.h \
  /usr/include/stdlib.h /usr/include/sys/types.h /usr/include/time.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/sys/select.h /usr/include/bits/select.h \
  /usr/include/bits/sigset.h /usr/include/bits/time.h \
  /usr/include/sys/sysmacros.h /usr/include/alloca.h /usr/include/stdio.h \
  /usr/include/bits/stdio_lim.h /usr/include/string.h \
  ../userprog/userkernel.h ../threads/kernel.h ../threads/thread.h \
  ../machine/machine.h ../machine/translate.h ../userprog/addrspace.h \
  ../filesys/filesys.h ../filesys/openfile.h ../threads/scheduler.h \
  ../lib/list.h ../lib/list.cc ../machine/interrupt.h \
  ../machine/callback.h ../machine/stats.h ../threads/alarm.h \
  ../machine/timer.h
# DEPENDENCIES MUST END AT END OF FILE
# IF YOU PUT STUFF HERE IT WILL GO AWAY
# see make depend above


import os.path

object_list = Object('prog.c', LIBS = 'm',
                             LIBPATH = ['/usr/lib', '/usr/local/lib'])
program_list = Program(object_list)
program_name = str(program_list[0])
if not os.path.exists(program_name):
    print program_name, "does not exist!"


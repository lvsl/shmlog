build_env = Environment(CCFLAGS = '-O2 -Wall -std=gnu99 -W -pedantic')

build_env.Program(["shmlog_write.c", "shmlog.c"])
build_env.Program("shmlog_read.c")

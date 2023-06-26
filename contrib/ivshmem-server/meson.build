executable('ivshmem-server', files('ivshmem-server.c', 'main.c'), genh,
           dependencies: [qemuutil, rt, numa],
           build_by_default: targetos == 'linux',
           install: false)

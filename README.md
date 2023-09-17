# snd-soc_kernel_obj
Please put these modules in /lib/modules/`uname -r`/kernel/sound/soc/intel/boards           where `uname -r` is the name command that will output the kernel release name.

These Kernel objects are already compiled for you.

They will be detected automatically when you reboot or, if you want to enable them now then use this:

For example: `# modprobe snd-soc-bdw-rt286`

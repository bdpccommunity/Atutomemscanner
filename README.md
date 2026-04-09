vol.exe -f memory.mem windows.threads | findstr 4724
vol.exe -f memory.mem windows.malfind --pid 4724 --dump
vol.exe -f memory.mem windows.malfind
vol.exe -f memory.mem windows.ldrmodules
InLoad = False, InInit = False, InMem = True
vol.exe -f memory.mem windows.pslist
vol.exe -f memory.mem windows.psscan

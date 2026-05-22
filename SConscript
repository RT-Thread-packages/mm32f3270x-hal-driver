from building import *

cwd = GetCurrentDir()

src = Glob('./Src/*.c')

CPPPATH = [
    cwd + '/../mm32f3270x-cmsis-latest/CMSIS/Include',
    cwd + '/../mm32f3270x-cmsis-latest/CMSIS/Device/MM32/MM32F3277/Include',
    cwd + '/Inc',
]

group = DefineGroup('Libraries', src, depend = ['PKG_USING_MM32F3270X_HAL_DRIVER'], CPPPATH = CPPPATH)

Return('group')

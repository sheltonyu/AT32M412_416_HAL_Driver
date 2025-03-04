from building import *
import os

cwd = GetCurrentDir()
path = [os.path.join(cwd, 'inc')]
src_path = os.path.join(cwd, 'src')

CPPDEFINES = ['USE_STDPERIPH_DRIVER']

src = [
os.path.join(src_path, 'at32m412_416_adc.c'),
os.path.join(src_path, 'at32m412_416_can.c'),
os.path.join(src_path, 'at32m412_416_cmp.c'),
os.path.join(src_path, 'at32m412_416_crc.c'),
os.path.join(src_path, 'at32m412_416_crm.c'),
os.path.join(src_path, 'at32m412_416_dac.c'),
os.path.join(src_path, 'at32m412_416_debug.c'),
os.path.join(src_path, 'at32m412_416_dma.c'),
os.path.join(src_path, 'at32m412_416_ertc.c'),
os.path.join(src_path, 'at32m412_416_exint.c'),
os.path.join(src_path, 'at32m412_416_flash.c'),
os.path.join(src_path, 'at32m412_416_gpio.c'),
os.path.join(src_path, 'at32m412_416_i2c.c'),
os.path.join(src_path, 'at32m412_416_misc.c'),
os.path.join(src_path, 'at32m412_416_op.c'),
os.path.join(src_path, 'at32m412_416_pwc.c'),
os.path.join(src_path, 'at32m412_416_scfg.c'),
os.path.join(src_path, 'at32m412_416_spi.c'),
os.path.join(src_path, 'at32m412_416_tmr.c'),
os.path.join(src_path, 'at32m412_416_usart.c'),
os.path.join(src_path, 'at32m412_416_wdt.c'),
os.path.join(src_path, 'at32m412_416_wwdt.c'),
]

group = DefineGroup('libraries', src, depend = ['PKG_USING_AT32M412_416_HAL_DRIVER'], CPPPATH = path, CPPDEFINES = CPPDEFINES)

Return('group')

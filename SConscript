from building import *

cwd = GetCurrentDir()
src = Split('''
xxtea.c
''')
CPPPATH = [cwd]

group = DefineGroup('xxtea', src, depend = [''], CPPPATH = CPPPATH)

Return('group')


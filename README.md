# set-clear-toggle-bit
define functions for set,clear,toggle bits
In AVR C project, you can use the following macros to set, clear or toggle a bit

#define SET_BIT(REG,BIT)            REG |=  (1 << BIT)

#define CLR_BIT(REG,BIT)            REG &= ~(1 << BIT)

#define TOG_BIT(REG,BIT)            REG ^=  (1 << BIT)

#define GET_BIT(REG,BIT)             (1 & (REG >> BIT))

in Reg.c ... add this
	#include "Timer.h"
	volatile Timer_t*	Timer = (Timer_t*)TIMER_CPU_BASE)

in Main.c add this
	#include "HalInterrupt.h"

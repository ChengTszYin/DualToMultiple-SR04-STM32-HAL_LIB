### [Timer Setting] ###
Select a timer<br />
Clock Source -> Internal Clock <br />
Channel 1 -> Input Capture direct mode <br />
Prescalar (mine is stm32f103 running at 72MHz) -> 72 -1<br />
auto-reload preload -> Enable<br />
NVIC settings -> Enable TIMx global Interrupt<br /><br />

### [Trigger IO Setting] ###
GPIO output level -> low <br />
GPIO mode -> Output Push Pull<br />
GPIO Pull-up/Pull-down -> Pull-up <br />
Maximun Output Speed -> HIGH<br />

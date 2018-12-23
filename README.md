# RT2560F
WiFi card on Fujitsu Siemens Amilo M7400 and L7300

This notebook use a miniPci WiFi card that use an hardware signal for activate the wifi.
Under Linux (Xubuntu 18.10) there is no way to activate it, the result for rfkill command is always "Hard Blocked" so the classic rfkill unblock command do not resolve the problem.

thanks to a disappeared german page, but present on wayback machine, i discover that the hw signal is a pulluped signal on pin 13 of the miniPci WiFi card.
The founded info was for the Amilo M7400 notebook, but i tested it on L7300 notebook, that have a different WiFi module, WMIR-103G with an RT2560F chip.

The procedure remain the same of the german page, I attached the original one and an english translated page, plus some photo of the L7300 WiFi board that I tested.


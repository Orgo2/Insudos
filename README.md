# Insudos
Insulin dose monitor/datalogger HW&SW project

Project was to make small insulin pen mounted insulin dose monitor/datalogger. 
Project runs on stm32wb55 mcu. supplied from coin rechargeable battery.
Functions-RTC for time logging and dose time counter
Button controlled(user can set/correct the dose manually)
Button triggered-when insulin piston moves mcu wakes up and start counting time
Microphone dose monitor- mcu will be listening to background clicking sound(approx 14kHz?) and count the dose from it. 
Temperature sensor pcb contains temperature sensor so mcu can detect insulin overtemperature events
buzzer is the only pcb signalisation. It should beep warning when two doses will be applied in short time
Bluetooth connection for sending the data out bluetooth can be used. Cosnider bluetooth pen finder function-activate beeping when the pen is lost
Datalogging- certain space from mcu ram/flash should be used for data storage so the user will be able to download or view old data.
USB is implemented for charging, firmware update, or possible data download

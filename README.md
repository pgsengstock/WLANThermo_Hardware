# Misc. Notes
* The StepUp circuit is only needed for the blower/servo circuits.

# BOM Differences
v1 > v2
## StepUp
* LM2577T-ADJ = MT3608
  * MT3608 has no COMP line
* 1N5822 = PMEG6030EP
* v2 add 2.0A diode on line in

## Blower/Servo
* TLC272ACP = TS912ID
* BD131-16 = SC3303
* 1N5822 = PMEG6030EP
* v2 add 0.75A diode on +12V in
* v2 add datalines back from pitmaster ports to logic level coverter

## Alarm
* BC337-25 = BC848

## A/D Converter
* MCP3208-CI/P = MCP3208

## Voltage Regulator
* MAX604CPA = LP2985

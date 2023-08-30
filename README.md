# SBM20 Counter

With this PCB and an SBM20 tube you can build a small, battery operated geiger counter. It can be supplied by two AA batteries, for example. Depending on the battery type you can populate the Step-Up (<5V) or the Step-Down (>5V).
The left part of the PCB generates the approx. 400V for the tube, the right part amplifies and shapes the pulses for the LED and buzzer.
The buzzer is optional if the LED is sufficient feedback.

![image](https://github.com/stdlogicvector/SBM20_Counter/assets/8276483/a56da398-fcd1-4b7e-9c3d-6d336f2a8b5b)

## Acknowledgements
The circuit is bodged together from multiple sources on the internet, mainly from [MightyOhm](https://mightyohm.com/files/geiger/geiger_sch_fixedR5R6.png).


## Contact
Send Questions to @stdlogicvector@chaos.social 

## BOM

| **Qty** | **Value** | **Footprint**     | **Parts**         | **DIGIKEY**                 | **LCSC** |
| ------- | --------- | ----------------- | ----------------- | --------------------------- | -------- |
| 1       | Red       | CHIPLED_1206      | LED               |                             |          |
| 1       | 100R      | R-TRIMM3224J      | R14               |                             |          |
| 1       | 1M        | R-EU_R1206        | R2                |                             |          |
| 2       | 1N4148    | SOD123            | D2, D3            |                             |          |
| 2       | 1k        | R-EU_R0603        | R13, R32          |                             |          |
| 1       | 1k5       | R-EU_R0603        | R1                |                             |          |
| 2       | 1n        | C-EUC0603         | C3, C6            |                             |          |
| 1       | 1u        | C-EUC1206         | C9                |                             |          |
| 1       | 2u2       | C-EUC1206         | C10A              |                             |          |
| 1       | 4M7       | R-EU_R1206        | R10               |                             |          |
| 1       | 4k7       | R-EU_R0603        | R9                |                             |          |
| 1       | 10mH      | L-EUL8065         | L1                |                             |          |
| 2       | 10n 630V  | C-EUC1206         | C1, C5            |                             |          |
| 4       | 10u       | C-EUC1206         | C8, C8A, C8B, C10 |                             |          |
| 1       | 20p       | C-EUC0603         | C11               |                             |          |
| 1       | 22R       | R-EU_R0603        | R5                |                             |          |
| 1       | 27k       | R-EU_R0603        | R4                |                             |          |
| 1       | 30R       | R-EU_R0603        | R5A               |                             |          |
| 3       | 100k      | R-EU_R0603        | R7, R11, R12      |                             |          |
| 2       | 100n      | C-EUC0603         | C2, C7            |                             |          |
| 1       | 120k      | R-EU_R0603        | R16               |                             |          |
| 1       | 180k      | R-EU_R0603        | R6                |                             |          |
| 1       | 220k      | R-EU_R0603        | R3                |                             |          |
| 1       | 220p      | C-EUC0603         | C4                |                             |          |
| 1       | 330R      | R-EU_R0603        | R8                |                             |          |
| 1       | 680k      | R-EU_R0603        | R15               |                             |          |
| 1       | CMMR1U-06 | DO-214AC          | D1                | 1514-CMMR1U-06TRPBFREECT-ND |
| 1       | DN350T05  | SOT23             | T1                | DN350T05DICT-ND             |
| 1       | LM555D    | LM555D            | IC2               | LM555CMX/NOPBCT-ND          |
| 1       | LM556D    | LM556D            | IC1               | 2156-LM556CM-FS-ND          |
| 2       | MMBT3904  | SOT23             | T2, T3            | 4530-MMBT3904CT-ND          |
| 2       | SBM20     | FUSECLIP          | SBM20             | F3781-ND                    |          |
| 1       | XC914X    | SOT23-5           | IC3               | 893-1373-1-ND               |          |
| 1       | XC926X    | SOT23-5           | IC3A              | 893-1330-1-ND               |          |
| 2       | 4u7       | L5050             | L2, L2A           | 490-7779-1-ND               |          |
| 1       | KJL-5020  | BUZZER-5020       | BEEP              |                             | C556937  |
| 1       | AO3404A   | SOT23             | T6                |                             | C30010   |
| 1       |           | SWITCH-SPDT-SMD-A | PWR               |                             | C319019  |

The SMB20 tube is available from several ebay sellers.

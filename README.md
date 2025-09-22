# AIF Macronetworks report
_______

## Table of Contents

- [Introduction](#Introduction)
  * [Structure of the repository](#Structure-of-the-repository)
- [Files used in the project and their structure](#Files-used-in-the-project-and-their-structure)
- [How to change the master table file](#How-to-change-the-master-table-file)
- [Examples](#Examples)
- [Things to do before running the notebooks](#Things-to-do-before-running-the-notebooks)
- [References](#References)

## Introduction
This repostory aims to examine financial linkages amount different economics sectors across different asset classes and over time. 

### Structure of the repository
This repository is organized as follows:
- `Notebooks` contains

## Files used in the project and their structure
Files used in the project:
- `2024-08-30_PT_macronetwork.ipynb` contains
- `Network_metrics.ipynb` contains
- `macronetworks_driver.xlsx` contains

The network.driver is the master table that will dictate which variables should be included in the whole project. This excel file contains those sheets:

"fenomeno": sheets
"sector": sheets
"instrument": sheets
"ap": sheets
"periodo": sheets

Inside each sheet there are two column one with the variables available to choose from and the 'flag' column where it will be signed with either 0 - not selected - and 1 if selected.

### Consider the Data labels
Consider the data as: 

**fenomeno** :   Pos, Trans                           <br>
**setor**:    

| **setor**      | **DesignacaoPT**                                                                                     | **sector_name**                                                 | **sector_ESAcode**             | **sector_code** |
|----------------|------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------|-------------------------------|----------------|
| BC             | Banco central                                                                                        | Central bank                                                    | S121                          | CB             |
| OIFM           | Outras instituições financeiras monetárias                                                           | Other monetary financial institutions                           | S122_S123                     | BNK            |
| FI             | Fundos de investimento, exeto fundos do mercado monetário                                             | Investment funds (IF), except money market funds                 | S124                          | IFNM           |
| OIFAF_exc_FI   | Sociedades financeiras, exceto IFM, fundos investimento e sociedades seguros e fundos pensões         | Financial corporations, except MFI, IF and ICPF                 | S125_S126_S127                | OFI            |
| SS             | Sociedades de seguros                                                                                 | Insurance corporations (IC)                                      | S128                          | INS            |
| FP             | Fundos de pensões                                                                                     | Pension funds (PF)                                              | S129                          | PF             |
| SNF            | Sociedades não financeiras                                                                            | Non-financial corporations                                       | S11                           | NFC            |
| AP             | Administrações públicas                                                                              | General government                                              | S13                           | GOV            |
| Part           | Particulares                                                                                         | Households                                                      | S14_S15                       | HH             |
| RM             | Resto do mundo                                                                                       | Rest of the world                                               | S2                            | RoW            |
| SF             | Sociedades financeiras                                                                               | Financial corporations                                          | S12                           | FI             |
| IFM            | Instituções financeiras monetárias                                                                   | Monetary financial institutions                                  | S121_S122_S123                | MFI            |
| OIFAF          | Sociedades financeiras, exceto IFM e sociedades seguros e fundos pensões                             | Financial corporations, except MFI and ICPF                     | S124_S125_S126_S127           | MFINM          |
| OIF            | Outros intermediários financeiros                                                                    | Other financial intermediaries                                  | S125                          | OFI_narrow     |
| AF             | Auxiliares financeiros                                                                               | Financial auxiliaries                                           | S126                          | FA             |
| CATIVAS        | Instituções financeiras cativas e prestamistas                                                       | Captive financial institutions and money lenders                 | S127                          | CFI_ML         |
| SSFP           | Sociedades de seguros e fundos de pensões                                                            | Insurance corporations and pension funds                         | S128_129                      | INSPF          |
<br>

**Instrumento** : <br>


| **Code** | **Designação PT**                                                   | **English Description**                        |
|----------|----------------------------------------------------------------------|-----------------------------------------------|
| F2       | Numerário e depósitos                                               | Currency and deposits                          |
| F2M      | Depósitos                                                           | Deposits                                       |
| F3       | Títulos de dívida                                                   | Debt securities                                |
| F31      | Títulos de dívida de curto prazo                                     | Short-term debt securities                     |
| F32      | Títulos de dívida de longo prazo                                     | Long-term debt securities                      |
| F4       | Empréstimos                                                         | Loans                                          |
| F41      | Empréstimos de curto prazo                                           | Short-term loans                               |
| F42      | Empréstimos de longo prazo                                           | Long-term loans                                |
| F51      | Ações e outras participações exceto em fundos de investimento        | Equity                                         |
| F511     | Ações cotadas                                                       | Listed shares                                  |
| F52      | Ações ou unidades de participação em fundos de investimento          | Investment fund shares/units               
<br>


**DesignaInst** : This value depends on the Instrument                           <br>

| **Instrument Code** | **Instrument Designation**                                       |
|---------------------|-----------------------------------------------------------|
| F1                  | Monetary gold and SDRs                                    |
| F2                  | Currency and deposits                                     |
| F2M                 | Deposits                                                  |
| F3                  | Debt securities                                           |
| F31                 | Short-term debt securities                                |
| F32                 | Long-term debt securities                                 |
| F4                  | Loans                                                     |
| F41                 | Short-term loans                                          |
| F42                 | Long-term loans                                           |
| F5                  | Equity and investment fund shares/units                   |
| F511                | Listed shares                                             |
| F512+F519           | Unlisted shares and other equity                          |
| F52                 | Investment fund shares/units                              |
| F6                  | Insurance, pension and standardized guarantee schemes     |
| F7                  | Financial derivatives and employee stock options          |
| F8                  | Other accounts receivable/payable                         |


**AP** :   Ativo (Assets) or  Passivo (Liabilities)                        <br>
**Setor_Cont** :  same as *setor*
<br>
**_NAME_** : Value <br>
**_LABEL_** :  Value                          <br>



## Libraries requirements
 
Check requirements.txt for more libraries versions.

## How to change the master table file

## Examples

## Things to do before running the notebooks
> :exclamation: **Important:** Key information users need to know to achieve their goal.

## References


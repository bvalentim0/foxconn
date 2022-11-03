
|![enter image description here](https://www.foxconn.com.br/img/logo.png) | ![Inex Brail](https://www.inexbr.com.br/wp-content/uploads/2022/07/logo-inex-azul.png) | [Bruno Valentim](mailto:Bruno.Valentim@inex.com.br)
|--|--|--|

# 1. Today tasks (03.11.2022)

## 1.1. `Atuando`:

 - ### Controle de Acesso:
   - [ ] [**IMPRESSÃO**]
   - [ ] [**DOUBLE_CHECK**]
   - [ ] [**CONSIGURAÇÃO**]

    ## 1.1.1 Sobre `Rules`:

    >### `Rules` na Base de Dados para `MacLabelPrintWeb`:
    >```SQL
    >SELECT DISTINCT RP.NAME AS PROGRAM_NAME,R.NAME AS PROGRAM_RULE
    >FROM FOCUS.R_ROLE_T R ,FOCUS.R_PROGRAM_T RP 
    >WHERE RP.NAME = 'MacLabelPrintWeb'
    >```	
    >> - ADMIN
    >> - AGUARDANDO_SN
    >> - AOI 1 DEBUG
    >> - AOI 2 DEBUG
    >> - APROVAR_WO
    >> - CAB_SETUP
    >> - CANCELAR_WO
    >> - CHANGE_PASSWORD
    >> - CHANGE_PREFERENCES
    >> - CLOSE_ECR
    >> - CONFIG_GROUP

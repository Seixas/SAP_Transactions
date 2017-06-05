*$*$ -------------------------------------------------------------- *$*$
*$*$                       P E T R O B R A S                        *$*$
*$*$ -------------------------------------------------------------- *$*$
*$*$ Autor       : Lucas Seixas                                     *$*$
*$*$ Início      : 05/06/2017                                       *$*$
*$*$ Término     : 05/06/2017                                       *$*$
*$*$ -------------------------------------------------------------- *$*$
*$*$ Projeto     : Help Desk                                        *$*$
*$*$ Finalidade  : Centralizar todas as transações de suporte INDRA *$*$
*$*$ Descrição   : Projeto pessoal, nenhuma para PETROBRAS,ou seja, *$*$
*$*$               nenhum envolvimento na produção da mesma.        *$*$
*$*$ -------------------------------------------------------------- *$*$
*$*$ Histórico de modificações                                      *$*$
*$*$ Data     |Autor        | Descrição                             *$*$
*$*$ -------------------------------------------------------------- *$*$



REPORT yhp_suporte_atendimento NO STANDARD PAGE HEADING
                           LINE-SIZE 89
                           LINE-COUNT 65.


TABLES: sscrfields.


************************BOTÕES******************************************
*SU01
SELECTION-SCREEN PUSHBUTTON /3(59) b_cf01 USER-COMMAND cf01. "#EC NEEDED

*YS_PERFIL
SELECTION-SCREEN PUSHBUTTON /3(59) b_cf19 USER-COMMAND cf19. "#EC NEEDED

*YSUSOPERFIL
SELECTION-SCREEN PUSHBUTTON /3(59) b_cf08 USER-COMMAND cf08. "#EC NEEDED

*SUIM
SELECTION-SCREEN PUSHBUTTON /3(59) b_cf06 USER-COMMAND cf06. "#EC NEEDED

*S_BCE_68001425 Critérios complexos
SELECTION-SCREEN PUSHBUTTON /3(59) b_cf17 USER-COMMAND cf17. "#EC NEEDED

*SE16
SELECTION-SCREEN PUSHBUTTON /3(59) b_cf05 USER-COMMAND cf05. "#EC NEEDED

*ME23N
SELECTION-SCREEN PUSHBUTTON /3(59) b_cf09 USER-COMMAND cf09. "#EC NEEDED

*ME33K
SELECTION-SCREEN PUSHBUTTON /3(59) b_cf18 USER-COMMAND cf18. "#EC NEEDED

*XK03
SELECTION-SCREEN PUSHBUTTON /3(59) b_cf10 USER-COMMAND cf10. "#EC NEEDED

*YSENCERRAMENTO
SELECTION-SCREEN PUSHBUTTON /3(59) b_cf11 USER-COMMAND cf11. "#EC NEEDED

*YSMEDICAO
SELECTION-SCREEN PUSHBUTTON /3(59) b_cf12 USER-COMMAND cf12. "#EC NEEDED

*ML81N
SELECTION-SCREEN PUSHBUTTON /3(59) b_cf07 USER-COMMAND cf07. "#EC NEEDED

*YSLMC
SELECTION-SCREEN PUSHBUTTON /3(59) b_cf14 USER-COMMAND cf14. "#EC NEEDED

*PA20
SELECTION-SCREEN PUSHBUTTON /3(59) b_cf13 USER-COMMAND cf13. "#EC NEEDED

*PPOSE
SELECTION-SCREEN PUSHBUTTON /3(59) b_cf02 USER-COMMAND cf02. "#EC NEEDED

*YSCS60
SELECTION-SCREEN PUSHBUTTON /3(59) b_cf03 USER-COMMAND cf03. "#EC NEEDED

*IW53
SELECTION-SCREEN PUSHBUTTON /3(59) b_cf04 USER-COMMAND cf04. "#EC NEEDED

*ME53N
SELECTION-SCREEN PUSHBUTTON /3(59) b_cf15 USER-COMMAND cf15. "#EC NEEDED

*CJ20N
SELECTION-SCREEN PUSHBUTTON /3(59) b_cf16 USER-COMMAND cf16. "#EC NEEDED

*IW33
SELECTION-SCREEN PUSHBUTTON /3(59) b_cf20 USER-COMMAND cf20. "#EC NEEDED

*J1BNFE
SELECTION-SCREEN PUSHBUTTON /3(59) b_cf21 USER-COMMAND cf21. "#EC NEEDED

*YSPROTOCOLO
SELECTION-SCREEN PUSHBUTTON /3(59) b_cf23 USER-COMMAND cf23. "#EC NEEDED

*FB03
SELECTION-SCREEN PUSHBUTTON /3(59) b_cf24 USER-COMMAND cf24. "#EC NEEDED

*KO03
SELECTION-SCREEN PUSHBUTTON /3(59) b_cf25 USER-COMMAND cf25. "#EC NEEDED

*KS03
SELECTION-SCREEN PUSHBUTTON /3(59) b_cf26 USER-COMMAND cf26. "#EC NEEDED

*YSRELLOG
SELECTION-SCREEN PUSHBUTTON /3(59) b_cf27 USER-COMMAND cf27. "#EC NEEDED

*PRTE
SELECTION-SCREEN PUSHBUTTON /3(59) b_cf28 USER-COMMAND cf28. "#EC NEEDED

*SWI1
SELECTION-SCREEN PUSHBUTTON /3(59) b_cf29 USER-COMMAND cf29. "#EC NEEDED

SELECTION-SCREEN PUSHBUTTON /3(59) b_cf30 USER-COMMAND cf30. "#EC NEEDED

*******************AT SELECTION-SCREEN OUTPUT***************************
AT SELECTION-SCREEN OUTPUT.

  b_cf01 = text-001.
  b_cf02 = text-003.
  b_cf03 = text-004.
  b_cf04 = text-005.
  b_cf05 = text-006.
  b_cf06 = text-007.
  b_cf07 = text-008.
  b_cf08 = text-009.
  b_cf09 = text-010.
  b_cf10 = text-011.
  b_cf11 = text-012.
  b_cf12 = text-013.
  b_cf13 = text-014.
  b_cf14 = text-015.
  b_cf15 = text-016.
  b_cf16 = text-017.
  b_cf17 = text-018.
  b_cf18 = text-019.
  b_cf19 = text-020.
  b_cf20 = text-021.
  b_cf21 = text-022.
  b_cf23 = text-023.
  b_cf24 = text-024.
  b_cf25 = text-025.
  b_cf26 = text-026.
  b_cf27 = text-027.
  b_cf28 = text-028.
  b_cf29 = text-029.
  b_cf30 = text-030.

*******************AT SELECTION-SCREEN**********************************
AT SELECTION-SCREEN.

  CASE sscrfields-ucomm.

    WHEN 'CRET' OR 'ONLI'.
*     Favor escolher um dos botões disponíveis
      MESSAGE e001(ys_hp). **classe mensagem ys_hp**

    WHEN 'CF01'.
*      SU01
      CALL TRANSACTION 'SU01'.

    WHEN 'CF02'.
*      PPOSE
      CALL TRANSACTION 'PPOSE'.

    WHEN 'CF03'.
*      YSCS60
      CALL TRANSACTION 'YSCS60'.

    WHEN 'CF04'.
*      IW53
      CALL TRANSACTION 'IW53'.

    WHEN 'CF05'.
*      YSLMCDOCPROC
      CALL TRANSACTION 'YSLMCDOCPROC'.

    WHEN 'CF06'.
*      SUIM
      CALL TRANSACTION 'SUIM'.

    WHEN 'CF07'.
*      ML81N
      CALL TRANSACTION 'ML81N'.

    WHEN 'CF08'.
*      YSUSOPERFIL
      CALL TRANSACTION 'YSUSOPERFIL'.

    WHEN 'CF09'.
*      ME23N
      CALL TRANSACTION 'ME23N'.

    WHEN 'CF10'.
*      XK03
      CALL TRANSACTION 'XK03'.

    WHEN 'CF11'.
*      YSENCERRAMENTO
      CALL TRANSACTION 'YSENCERRAMENTO'.

    WHEN 'CF12'.
*      YSMEDICAO
      CALL TRANSACTION 'YSMEDICAO'.

    WHEN 'CF13'.
*      YSLMCDELEGAGEX
      CALL TRANSACTION 'YSLMCDELEGAGEX'.

    WHEN 'CF14'.
*      YSLMC
      CALL TRANSACTION 'YSLMC'.

    WHEN 'CF15'.
*      ME53N
      CALL TRANSACTION 'ME53N'.

    WHEN 'CF16'.
*      CJ20N
      CALL TRANSACTION 'CJ20N'.

    WHEN 'CF17'.
*      S_BCE_68001425
      CALL TRANSACTION 'S_BCE_68001425'.

    WHEN 'CF18'.
*      ME33K
      CALL TRANSACTION 'ME33K'.

    WHEN 'CF19'.
*      YS_PERFIL
      CALL TRANSACTION 'YS_PERFIL'.

    WHEN 'CF20'.
*      IW33
      CALL TRANSACTION 'IW33'.

    WHEN 'CF21'.
*      J1BNFE
      CALL TRANSACTION 'J1BNFE'.

    WHEN 'CF23'.
*      YSPROTOCOLO
      CALL TRANSACTION 'YSPROTOCOLO'.

    WHEN 'CF24'.
*      FB03
      CALL TRANSACTION 'FB03'.

    WHEN 'CF25'.
*      KO03
      CALL TRANSACTION 'KO03'.

    WHEN 'CF26'.
*      *KS03
      CALL TRANSACTION 'KS03'.

    WHEN 'CF27'.
*      *YSRELLOG
      CALL TRANSACTION 'YSRELLOG'.

    WHEN 'CF28'.
      CALL TRANSACTION 'PRTE'.

    WHEN 'CF29'.
*         *SWI1
      CALL TRANSACTION 'SWI1'.

    WHEN 'CF30'.
      CALL TRANSACTION 'YSMM_DACMOD'.

  ENDCASE."SSCRFIELDS-UCOMM

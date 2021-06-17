# utl_sas-classic-editor-point-and-shoot-a-proc-freq
Fast proc freq processing using the classic SAS editor

    Fast proc freq processing using the classic SAS editor

    https://github.com/rogerjdeangelis/utl_sas-classic-editor-point-and-shoot-a-proc-freq

    https://tinyurl.com/sfekmfzc
    https://raw.githubusercontent.com/rogerjdeangelis/utl-macros-used-in-many-of-rogerjdeangelis-repositories/master/utl_perpac.sas

    Run this code

    data class;
      set sashelp.class;
      this_is_a_ling_variable_name = sex;
    run;quit;

    Just do this in the classic 1980's sas editor

    1.  Hihglight 'this_is_a_ling_variable_name=sex'
        cntl-c (to copy to paste buffer)
        Note I keep my right hand over the 'cntl-c/cntl-v' area of the keyboard

    2.  Next hit the home button ( my left hand is near the home key)


    3.  cbtl-c (this pastes 'this_is_a_ling_variable_name' on the commandline

    4.  type frq in front of the text 'this_is_a_ling_variable_name'
        Note cursor should already be in front of the text

    5.  Hit enter (left hand is very near enter)

    This will appear in the output window

    Frequency of this_is_a_ling_variable_name datasets WORK.CLASS

    The FREQ Procedure

           Number of Variable Levels

    Variable                          Levels
    ----------------------------------------
    THIS_IS_A_LING_VARIABLE_NAME           2


    THIS_IS_
    A_LING_
    VARIABLE_                             Cumulative    Cumulative
    NAME         Frequency     Percent     Frequency      Percent
    --------------------------------------------------------------
    F                   9       47.37             9        47.37
    M                  10       52.63            19       100.00



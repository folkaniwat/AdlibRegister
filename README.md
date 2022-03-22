# AdlibRegister
Func OnEvent_CLOSE_TWO()     ConsoleWrite('- Func OnEvent_CLOSE_TWO()' &amp; @CRLF)     $iExitLoop = 1 EndFunc   ;==>OnEvent_CLOSE_TWO  Func LoadGuiTwoFromGuiOne()     Example2($hGUIParent1) ; no solution. ;~  $iLoadGuiTwo = 1 ; solution 1 ;~  AdlibRegister("LoadGuiTwoRunner", 10) ; solution 2 EndFunc   ;==>LoadGuiTwoFromGuiOne

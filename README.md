# EXCEL-MACRO-PROGRAM-TO-PERFORM-STRING-MANIPULATION
Sub ExecuteCode() 

Dim text1 As String, text2 As Stringtext1 = "Hi" 

text2 = "Tim" 

MsgBox text1 & " " & text2

Dim text As String text = "example text" 

MsgBox Left(text, 4) 

MsgBox Right("example text", 2) 

MsgBox Mid("example text", 9, 2) 

MsgBox Len("example text") 

MsgBox InStr("example text", "am") 

End Sub

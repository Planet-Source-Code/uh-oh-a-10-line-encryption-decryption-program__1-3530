<div align="center">

## a 10 line encryption/decryption program


</div>

### Description

This is a encrypt/decrypt program thats only 10 lines long!!!

all it uses is 2 simple fonts to encrypt, times new romand for the text and Money for the encrypted text! please tell me if you like it:)
 
### More Info
 
'1 text box

'2 command buttons (encrypt, decrypt)


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[uh oh](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/uh-oh.md)
**Level**          |Unknown
**User Rating**    |1.6 (64 globes from 39 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[String Manipulation](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/string-manipulation__1-5.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/uh-oh-a-10-line-encryption-decryption-program__1-3530/archive/master.zip)





### Source Code

```
'add 2 command buttons
'add 1 text box
'coded by the other matt
'please give me mention if you ever decide to use this in one of you apps:)
Private Sub Command1_Click()
If Text1 = "" Then MsgBox "YOU MUST ENTER SOME TEXT!"
Command1.Caption = "Encrypt"
Text1.Font = "Money"
End Sub
Private Sub Command2_Click()
If Text1 = "" Then MsgBox "YOU MUST ENTER SOME TEXT!"
Command2.Caption = "Decrypt"
Text1.Font = "Times New Roman"
End Sub
```


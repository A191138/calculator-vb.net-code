# calculator-vb.net-code
THIS PROGRAM TAKES INPUT OF TWO NUMBERS AND AN OPERATOR AND DISPLAYS THE RESULT  


Module Program
    Sub Main()
        Dim num1 As Integer
        Dim num2 As Integer
        Dim op As Char
        Dim answer As Double

        Console.WriteLine("please enter the first number")
        num1 = Console.ReadLine

        Console.WriteLine("please enter an operator")
        op = Console.ReadLine

        Console.WriteLine("please enter the second number")
        num2 = Console.ReadLine

        If op = "+" Then
            answer = num1 + num2
        End If
        If op = "-" Then
            answer = num1 - num2
        End If
        If op = "*" Then
            answer = num1 * num2
        End If
        If op = "/" Then
            answer = num1 / num2
        End If

        Console.WriteLine("ANSWER = " & answer)

        Console.ReadKey()
    End Sub
End Module

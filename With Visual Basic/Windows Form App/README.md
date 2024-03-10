## Print Hello World using Visual Basic

![hellovb](https://github.com/sudeepsudhevan/Dot-NET-FrameWork/assets/31392327/e3f4626f-759f-464c-9a5b-6b088e01992e)

Form1.vb

```vb
Public Class Form1
    Private Sub btnClickThis_Click(sender As Object, e As EventArgs) Handles btnClickThis.Click
        lbIHelloworld.Text = "Hello World"
    End Sub
End Class
```

Form1.Designer.vb

```vb
<Global.Microsoft.VisualBasic.CompilerServices.DesignerGenerated()> _
Partial Class Form1
    Inherits System.Windows.Forms.Form

    'Form overrides dispose to clean up the component list.
    <System.Diagnostics.DebuggerNonUserCode()> _
    Protected Overrides Sub Dispose(ByVal disposing As Boolean)
        Try
            If disposing AndAlso components IsNot Nothing Then
                components.Dispose()
            End If
        Finally
            MyBase.Dispose(disposing)
        End Try
    End Sub

    'Required by the Windows Form Designer
    Private components As System.ComponentModel.IContainer

    'NOTE: The following procedure is required by the Windows Form Designer
    'It can be modified using the Windows Form Designer.  
    'Do not modify it using the code editor.
    <System.Diagnostics.DebuggerStepThrough()> _
    Private Sub InitializeComponent()
        Me.btnClickThis = New System.Windows.Forms.Button()
        Me.lbIHelloworld = New System.Windows.Forms.Label()
        Me.SuspendLayout()
        '
        'btnClickThis
        '
        Me.btnClickThis.Location = New System.Drawing.Point(206, 47)
        Me.btnClickThis.Name = "btnClickThis"
        Me.btnClickThis.Size = New System.Drawing.Size(187, 48)
        Me.btnClickThis.TabIndex = 0
        Me.btnClickThis.Text = "click pls "
        Me.btnClickThis.UseVisualStyleBackColor = True
        '
        'lbIHelloworld
        '
        Me.lbIHelloworld.AutoSize = True
        Me.lbIHelloworld.Location = New System.Drawing.Point(226, 127)
        Me.lbIHelloworld.Name = "lbIHelloworld"
        Me.lbIHelloworld.Size = New System.Drawing.Size(39, 13)
        Me.lbIHelloworld.TabIndex = 1
        Me.lbIHelloworld.Text = "Label1"
        '
        'Form1
        '
        Me.AutoScaleDimensions = New System.Drawing.SizeF(6.0!, 13.0!)
        Me.AutoScaleMode = System.Windows.Forms.AutoScaleMode.Font
        Me.ClientSize = New System.Drawing.Size(800, 450)
        Me.Controls.Add(Me.lbIHelloworld)
        Me.Controls.Add(Me.btnClickThis)
        Me.Name = "Form1"
        Me.Text = "Form1"
        Me.ResumeLayout(False)
        Me.PerformLayout()

    End Sub

    Friend WithEvents btnClickThis As Button
    Friend WithEvents lbIHelloworld As Label
End Class
```


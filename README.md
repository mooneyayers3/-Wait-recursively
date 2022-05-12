# -Wait-recursively
 Wait recursively 10 seconds for active button For $i = 1 To $timeout Step 1 ; Check if the Start button is active If ControlCommand($hWnd, "", $buttonName, "IsEnabled", "") &lt;> 0 Then ; Click the button and end the loop $clicked = ControlClick($hWnd, "", "[TEXT:" &amp; $buttonName &amp; "]") If $clicked = 1 Then

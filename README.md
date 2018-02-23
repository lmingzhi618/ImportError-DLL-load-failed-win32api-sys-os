# ImportError-DLL-load-failed-win32api-sys-os
I was blocked by the problem for days, but one day I solved it.
After you installed the pywin32 libs, there is a directory "Lib/site-packages/pywin32_system32", which including three dll libs, copy them to the "/Lib/site-packages/win32" directory, which including the win32api.pyd or win32api.pyc.
There will be no ImportError Exception any more

BTW： My python's version is 2.7.13

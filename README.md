# 1 Windows Developer Power Shell öffnen


# 2 Mit CL von Microsoft compileieren und bauen
cl /Zi /std:c++latest /EHsc /Fe: rooster.exe main.cpp

# 3 Ausgabe in der Developer Power Shell for VS2022

PS F:\dev-workspace\sandbox\CMakeSandbox\002> cl /Zi /std:c++latest /EHsc /Fe: rooster.exe main.cpp
Microsoft (R) C/C++-Optimierungscompiler Version 19.38.33133 für x86
Copyright (C) Microsoft Corporation. Alle Rechte vorbehalten.

"/std:c++latest" wird als Vorschau auf die Sprachfeatures aus dem neuesten C++-Arbeitsentwurf
 zur Verfügung gestellt, und wir sind gespannt auf Fehler und Verbesserungsvorschläge.
Beachten Sie jedoch, dass diese Features ohne Mängelgewähr und ohne Unterstützung bereitgestellt werden und Funktionen während der Weiterentwicklung
 des Arbeitsentwurfs jederzeit geändert oder entfernt werden können.
Ausführliche Informationen finden Sie unter https://go.microsoft.com/fwlink/?linkid=2045807.

main.cpp
Microsoft (R) Incremental Linker Version 14.38.33133.0
Copyright (C) Microsoft Corporation.  All rights reserved.

/debug
/out:rooster.exe
main.obj
PS F:\dev-workspace\sandbox\CMakeSandbox\002>
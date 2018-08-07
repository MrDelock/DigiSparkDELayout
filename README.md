# DigiSparkDELayout

Da ich immerwieder in Foren gelesen habe, dass einige Personen Probleme mit dem Deutschen Tastaturlayout beim DigiSpark haben, habe ich diesen Code veröffentlicht. Ich habe ihn mir in einer langen Nacht selbst zusammengebastelt, um das Problem zu lösen.

Was macht der Code?

Am Anfang wird Powershell geöffnet, um über den Befehl "Set-WinUserLanguageList -Force en-US" das Layout der Tastatur auf das amerikanische Layout zu setzen. 
Am Ende wird das Layout wieder auf das deutsche Layout zurück gesetzt.

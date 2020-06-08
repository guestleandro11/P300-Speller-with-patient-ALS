eseguire queste procedure per la fase di valutazione:
0) Scompattare l'archivio
1) Copiare dentro la cartella progetto_MOBD_V4.0 sia i 3 file X.txt, Y.txt, C.txt sia i 3 file che ha la professoressa per la fase di valutazione (X_prof.txt, Y_prof.txt, C_prof.txt);
2) Aprire il file "main" dentro la cartella progetto_MOBD_V4.0 e sostituire nella riga 36, testSet_prof <- 1, anzichè NULL in tal modo il programma 
   funzionerà sul testset della professoressa;
3) Sostituire sempre nel main nelle righe 57, 58, 59 al posto di NULL, i nomi dei 3 file X Y e C per la valutazione 
   (ad esempio X_prof <- "X_prof.txt", idem per gli altri 2 file);
4) Eseguire adesso il programma dall'inizio;
5) Per quanto riguarda l'accuratezza essa viene calcolata in termini percentuali, quindi se compare alla fine ad esempio come accuratezza 80 significa
   che sono stati classificati correttamente l'80% dei caratteri; 

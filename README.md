# Report Application

Applicazione per la generazione di Report a partire da dati storicizzati su InfluxDB.

La web application è realizzata con il framework python "Flask".
L'applicazione fornisce una pagina HTML in cui è possibile selezionare l'intervallo temporale di cui ci interessano i dati. Una volta estratti i dati da InfluxDB, sulla stessa pagina appariranno i grafici relativi ai dati e il tasto per scaricare il PDF del report della finestra temporale inserita.

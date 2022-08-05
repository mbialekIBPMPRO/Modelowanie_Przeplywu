# Modelowanie Przeplywu

- [x] **Obsługa błędów (terminale Failure, Catch, node TryCatch, node Throw)**

- [x] **Long-lived variables (SHARED)**

>User Defined Property

>Promote Property

>Wykorzystanie node Trace (do logowania)

- [x] Wysyłanie danych w nagłówkach HTTP

>Operacje SELECT w ESQL

>Callable Flows
   
- [x] **Obsługa Integration Servera w konsoli (sprawdzanie listy serwerów, startowanie i stopowanie serwera, deployment bar, zmiana   propertisów w bar)**

>Działanie parserów XMLNSC i JSON

# Obsługa Integration Servera w konsoli

### **Polecenia wykorzystane przeze mnie w konsoli:**
  - **Utworzenie węzła ->** mqsicreatebrokeR TEST_NODE
  -  **sprawdzanie węzła ->** mqsicvp TEST_NODE
  - **Ustawienie portu administratora ->**  mqsichangeproperties TEST_NODE -b webadmin -o HTTPConnector -n port -v 7602
  - **Uruchomienie węzła ->**  mqsistart TEST_NODE
  -  **Wyświetlanie listy wszystkich węzłów ->**  mqsilist
  - **Utworzenie serwer w węźle ->** mqsicreateexecutiongroup TEST_NODE  -e default -w 90
  -  **utworzenie pliku BAR. ->** mqsipackagebar -w C:\Users\Szef\IBM\ACET12\workspace -a mynewbarfile -k Praca_domowa_obsluga_bledow -y xsd_Lib
  - **Deploy ->** mqsideploy -p 7602 -e default -a newTestFielBar.bar
  - **Sprawdzanie włąsciwości BAR. ->** mqsireadbar [-b  | -r  | -v] 

![](ss_console/ss_2.JPG)
![](ss_console/ss_3.JPG)
![](ss_console/ss_4.JPG)
![](ss_console/ss_5.JPG)
![](ss_console/ss_6.JPG)
![](ss_console/ss_7.JPG)
![](ss_console/ss_8.JPG)
![](ss_console/ss_9.JPG)
![](ss_console/ss_10.JPG)
![](ss_console/ss_11.JPG)

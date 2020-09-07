## Przewidywanie wieku słuchotki (z ang. Abalone) na podstawie pomiarów fizycznych przy użyciu algorytmu ANFIS.

Wartość ekonomiczna słuchatek jest dodatnio skorelowana z ich wiekiem, dlatego dokładne określenie ich wieku jest ważne dla hodowców i klientów w celu ustalenia ceny danego osobnika. Jednak sposób określenia wieku abalone jest dość kosztowny, mało efektywny i przypomina trochę oszacowanie wieku drzewa. Ilość pierścienie na skorpie brzucha słuchotek określa mniej więcej jej wiek. W tym celu należy rozciąć muszlę, wypolerować i zabarwić skorupę słuchotki, a następnie pod mikroskopem określić liczbę pierścieni. Czasami określenie konkretnej liczby pierścieni jest niemożliwe i trudne, ponieważ mogą one zlewać się ze sobą, dlatego do oszacowanej liczy pierścieni dodaje się się 1.5 co daje przybliżony wiek słuchotki. Ta złożona metoda zwiększa koszty i ograniczenia jego popularność. Dlatego badacze są zainteresowani powiązaniem wieku abalone z takimi zmiennymi jak długość, wzrost i waga zwierzęcia. Jeśli można znaleźć dość dokładny model przewidujący wiek Abalone, to hodowcy zminimalizowaliby koszty, a klienci otrzymaliby dobrej jakości produkt.

W projekcie zastosowano algorytm ANFIS (z ang. Adaptive Neuro-Fuzzy Inference System) zaliczanego do systemów neuronowo-rozmytych. Dzięki połączenia sieci neuronowej z logiką rozmytą algorytm jest w stanie uczyć się z danych numerycznych i operować informacjami lingwistycznymi. Cechą systemy NFS jest umiejętność konstruowania samodzielnie reguł logicznych na podstawie dostarczonych danych, który w przypadku problemu określenia wieku słuchotek wydaje się dobrym wyborem.

Architektura  
Są dwa rodzaje procesów- Loop i EventLoop. Pierwsze służą do przetwarzania/ akwizycji danych bez interfejsu użytkownika.   
EventLoop są pętlami interfejsu użytkownika. Struktura obu pętli jest analogiczna (polimorfizm API) różnią się tylko wewnętrzną  
implementacją. Pętla Loop używa f-ji dequeue, która dodaj kolejke procesu do konrektnego repozytorium  
  
Problemy rozwiązane:  
Jednoznaczne API, dwa rodzaje komunikatów - z odpowiedzią i bez odpowiedzi  
Jednolita obsługa błędów i zamykania aplikacji.  
Enkapsulacja komunikacji  
Moduły singleton oraz wieloinstancyjne     

License:  
MIT License  
Copyright (c) [2020] [Bartlomiej Paszkiewicz]


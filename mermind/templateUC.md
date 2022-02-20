```mermaid
 sequenceDiagram
  participant A as ANPR/AppIO
  actor C as CITTADINO
  participant I as INAD

  Note over A: Effettuata autenticazione CITTADINO

  A ->> I: citizen_status_check(CF)
  I -->> A: STATE
```


[torna a readme.md](../readme.md)
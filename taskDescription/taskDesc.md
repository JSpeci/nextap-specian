Chtěli bychom jednoduchou aplikaci, skládající se z jedné komponenty - Carousel.
 
Komponentu by měla být headless. Takzvaně půjde přepoužít napříč aplikacemi bez ohledu na způsob použití. Nezapomeň, že každá část UI by tím měla být lehce nahraditelná při zachování funkcionality.
 
Samotná aplikace by pak měla sloužit k zobrazení dat níže uvedených endpointů v rámci dvou vzhledově rozdílných Carouselů
 
Endpoint pro 1. Carousel vrací list kolekcí, v Carouselu stačí zobrazit “cover_image_url”
https://web-task-api.herokuapp.com/api/v1/collections
 
Endpoint pro 2. Carousel vrací list storek, v Carouselu stačí zobrazit “cover_src”
https://web-task-api.herokuapp.com/api/v1/stories
 
 
Základní UI požadavky:
Šipky pro řízení pohybu
Indikátor aktuálního slidu
 
Základní funkční požadavky:
Možnost pohybu na další slide
Možnost pohybu na předchozí slide
Možnost pohybu na specifický slide
Informace o tom jaký slide je právě aktivní
 
Celkové požadavky:
Typescript
Zaměřit se hlavně na kvalitu kódu a architekturu
Alespoň základní dokumentaci (popis a příklady použití komponenty)
Zamyslet se nad vhodným state managementem
Základní animaci pro přechod mezi slidy
Kód by měl obsahovat alespoň základní set volitelných testů  (unit, e2e, ..)
Nezapomenout na základy sémantiky a přístupnosti na webu
Funkční na mobilním zařízení
Musí to fungovat :)
 
Bonus:
Infinite mód
Přechod mezi slidy za použití gest 
3D přechod mezi slidy
 
Můžete použít jakoukoliv knihovnu, ale být schopný odůvodnit využití.
Základní dokumentace (README.md).
Zdrojový kód k dispozici na githubu.


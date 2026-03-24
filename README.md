Platforma za upravljanje stručnim događajima
Opis projekta

Ova aplikacija predstavlja platformu za upravljanje stručnim događajima u okviru fakulteta. Sistem omogućava organizatorima da kreiraju, uređuju i pregledaju događaje, kao i da upravljaju podacima o predavačima, lokacijama i prijavama učesnika.

Podržani tipovi događaja uključuju:

konferencije
seminare
radionice
predavanja

Cilj sistema je da olakša organizaciju događaja i obezbedi centralizovan pregled svih relevantnih informacija.

Tehnološki stek

C# (.NET) – osnovni programski jezik i framework
ASP.NET Core
SQL Server – baza podataka
Entity Framework – ORM za rad sa bazom
GitHub – verzionisanje koda

Arhitektura sistema

Aplikacija koristi Layered + MVC arhitekturu:

1. Presentation Layer (ASP.NET MVC)
Controllers (EventController, SpeakerController…)
Views (Razor pages)
UI logika
2. Business Logic Layer (Services)
EventService
SpeakerService
RegistrationService
3. Data Access Layer
DbContext (EF Core)
Repozitorijumi (opciono)
4. Domain Layer
Entiteti (Event, Speaker, Location, Registration, Participant)

Dijagram klasa


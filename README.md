# BEYOND HEXAGONAL ARCHITECTURE
The support of our live coding session (made at __[Virtual DDD](https://twitter.com/virtualDDD)__, February 2nd, 2021)

Thanks to [Kenny](https://twitter.com/kenny_baas/) & [Krisztina](https://twitter.com/YellowBrickC/) for their warm welcome!

![Beyond](./Beyond.JPG)

## Slides
https://fr.slideshare.net/ThomasPierrain/beyond-hexagonal-architecture

![HexagonalOrNot](./HexagonalOrNot.JPG)

--- 

## HEXAGONAL ARCHITECTURE VERSION

![Hexa-WrapUp](./Hexa-WrapUp.png)

### Acceptance tests (Outside-in diamond style)
https://github.com/42skillz/livecoding-beyond-hexagonal-architecture/blob/hexagonal/SeatsSuggestions/TheaterSuggestions.Tests/AcceptanceTests/SeatsSuggestionsControllerShould.cs

### The Hexagon (SeatAllocator)
https://github.com/42skillz/livecoding-beyond-hexagonal-architecture/blob/hexagonal/SeatsSuggestions/SeatsSuggestions.Domain/SeatAllocator.cs

### The left-side port (WebController)
https://github.com/42skillz/livecoding-beyond-hexagonal-architecture/blob/hexagonal/SeatsSuggestions/SeatsSuggestions.Api/Controllers/SeatsSuggestionsController.cs

---

## FUNCTIONAL CORE VERSION

![Core-WrapUp](./Core-WrapUp.png)

### The Functional core (SeatAllocator)
https://github.com/42skillz/livecoding-beyond-hexagonal-architecture/blob/functional-core/SeatsSuggestions/SeatsSuggestions.Domain/SeatAllocator.cs


### The Imperative Shell (WebController)
https://github.com/42skillz/livecoding-beyond-hexagonal-architecture/blob/functional-core/SeatsSuggestions/SeatsSuggestions.Api/Controllers/SeatsSuggestionsController.cs



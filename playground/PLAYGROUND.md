# playground/ — your code

## Stack (VyaparOS first, then what is most useful)

| Need | Use | Book used |
|---|---|---|
| Language | Kotlin (Gradle, JVM) | C# / .NET 8 |
| Broker | Kafka | RabbitMQ |
| Database | PostgreSQL | MongoDB/SQL in the book |
| Event store | Kurrent (EventStoreDB) for stage 03 only; VyaparOS has none | Kurrent |
| Containers | Docker Compose | Docker Desktop |

## Folders

- `kotlin/` — **where you write code.** One small example per chapter, e.g. `kotlin/ch07-cqrs-khata/`, each with its own README and one run command. Ported from the book idea, not line by line.
- `csharp/` — a copy of book stage 01, kept only to run the original if you want to see it work. Optional; needs the .NET SDK.

Book-to-Kotlin hints: `record` = `data class`, `async/await` = coroutines, DI container = Koin/Spring, RabbitMQ consumer = Kafka consumer group.

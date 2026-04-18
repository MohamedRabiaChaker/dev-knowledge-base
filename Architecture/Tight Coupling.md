Tight coupling occurs when components depend heavily on each other's implementation details rather than abstractions. Changes to one component force changes throughout the system, making the codebase brittle, hard to test in isolation, and resistant to modification.

Design for loose coupling by depending on interfaces and abstractions, not concrete implementations. Separate concerns so each component has a single responsibility. This makes systems testable, maintainable, and adaptable to change.

Related: [[Spaghetti Code]], [[Poor API Design]], [[Overengineering for Scale]]

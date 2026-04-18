Committing without atomic, logical units makes it impossible to understand what changed and why, hiding bugs and making reverts dangerous.

Commit logically related changes as single units with clear messages describing the why. Keep commits small enough to review and understand. Good version control history is a record of intent, not just code changes.

Related: [[Hardcoding Secrets and Configuration]], [[Dead Code]], [[Spaghetti Code]]

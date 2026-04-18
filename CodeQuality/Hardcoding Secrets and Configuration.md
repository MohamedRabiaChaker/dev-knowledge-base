Embedding API keys, passwords, and environment-specific settings directly in source code exposes secrets to anyone with repository access and breaks applications across environments.

Use environment variables, configuration files, or secrets management systems. Keep secrets out of version control. Different environments get different configs without code changes.

Related: [[Spaghetti Code]], [[Poor Version Control Practices]], [[Ignoring Documentation]]

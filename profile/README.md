### Hi, this is Laridae! 👋 

Laridae enables reversible, zero-downtime schema migrations in PostgreSQL, synchronizing them with application code deployments for apps using AWS Fargate. It allows application instances expecting the pre-migration and post-migration schema to use the same database simultaneously without requiring changes to either version's code. Additionally, recent schema migrations can be reversed without data loss. This is accomplished with minimal interference with usual reads and writes to the database.

Laridae integrates this schema migration functionality into a deployment pipeline hosted on GitHub Actions. It creates the necessary infrastructure inside users’ AWS accounts, allowing GitHub Actions to communicate securely with your private PostgreSQL database and coordinates schema changes with code deployments.

If you'd like to learn more, check out our [website](https://laridae-migrations.github.io/).

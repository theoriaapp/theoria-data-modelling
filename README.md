# Visualise the Prisma Schema using Liam ERD
To visualise the schema.prisma file locally run the following

First cd into the folder, then install liam, build the file, then serve it. (commands below)

```
npx @liam-hq/cli init
npx @liam-hq/cli erd build --input prisma/schema.prisma --format prisma
npx serve dist/
```
## Proposing alternative data models
If you want to propose an alternative data model, re-build and commit your changes.

# WIP Data Model
This is a repo that has been created to kick off discussions for the data model of the Theoria app.
The initial data model is by no means correct or complete. It's just illustrative and a potential place to start.

# Visualise the Prisma Schema using Liam ERD
To visualise the schema.prisma file locally run the following

First cd into the folder, then install liam, build the file, then serve it. (commands below)

```
npx @liam-hq/cli init
npx @liam-hq/cli erd build --input prisma/schema.prisma --format prisma
npx serve dist/
```
## Proposing alternative data models
If you want to propose an alternative data model, 
1. Make a new branch
2. Update the schema.prisma file
3. Re-build npx @liam-hq/cli erd build --input prisma/schema.prisma --format prisma
4. Git Commit/Push your changes

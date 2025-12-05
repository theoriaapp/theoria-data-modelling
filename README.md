# 🚧 WIP Theoria Data Model
This is a repo that has been created to kick off discussions for the data model of the Theoria app.
The initial data model is by no means correct or complete. It's just illustrative and a potential place to start.

# Visualise the Prisma Schema using Liam ERD 
## Locally
To visualise the schema.prisma file locally
First cd into the folder, install liam, build the file, then serve it. (commands below)

```
npx @liam-hq/cli init
npx @liam-hq/cli erd build --input prisma/schema.prisma --format prisma
npx serve dist/
```

## On Liam ERD cloud
If you have committed changes to the schema.prisma, you can also generate an ER diagram by inserting liambx.com/erd/p/ into the URL where the schema file is hosted on our repo/branch:
```
https://liambx.com/erd/p/github.com/theoriaapp/theoria-data-modelling/blob/main/prisma/schema.prisma?showMode=ALL_FIELDS
      👾^^^^^^^^^^^^^^^^^👾
```

# Proposing alternative data models
If you want to propose an alternative data model, 
1. Make a new branch
2. Update the schema.prisma file
3. Re-build npx @liam-hq/cli erd build --input prisma/schema.prisma --format prisma
4. Git Commit/Push your changes

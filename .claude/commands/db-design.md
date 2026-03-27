---
description: Design database schemas, generate ERDs, and create Prisma/Drizzle/TypeORM migrations. Usage: /db-design <describe your data>
---

Help with database schema design for: $ARGUMENTS

Read `engineering/database-schema-designer/SKILL.md` and execute the Schema Design Process:
1. Extract entities from the requirements
2. Identify relationships between entities
3. Generate ERD as a Mermaid diagram
4. Generate migrations (ask user: Prisma, Drizzle, TypeORM, or Alembic?)
5. Generate TypeScript interfaces or Python types
6. Add indexes and RLS policies if needed

Ask what data to model if $ARGUMENTS is empty.

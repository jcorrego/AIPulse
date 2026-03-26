# Data Model (Draft)

## Entities
- **User**
- **Team**
- **UseCase**
- **Task**
- **Output**
- **Review**
- **Risk**
- **Metric**

## Key Relationships
- User → Team
- UseCase → Owner (User)
- Task → UseCase
- Output → Task
- Review → Output
- Risk → UseCase
- Metric → Team / UseCase

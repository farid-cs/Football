# Football League requirements.

These are just possible entities for Football League database.

**Bold** is an entity.
*Italic* is a derived attribute.

- **Players**
    - Player ID
    - Player number(on his back)
    - Fullname
        - Name
        - Surname
        - Patronymic
    - Height
    - Weight
    - Role
    - Age
- **Teams**
    - Team ID
    - Name
- **Trainers**
    - Trainer ID
    - Fullname
        - Name
        - Surname
        - Patronymic
- **Stadiums**
    - Stadium ID
    - Location
        - Country
        - City
        - Address
- **Match**
    - Match ID
    - Date and time
        - month
        - day
        - hour
    - Teams playing
    - Results
        - Winner team
        - *Losing team*
        - Number of goals of winning team
        - Number of goals of losing team

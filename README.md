# University Database

A database project for researching, comparing, and evaluating universities offering Computer Science degrees, postgraduate qualifications, and MBA programmes.

The project aims to centralise university information and facilitate structured comparisons based on predefined academic, institutional, and personal selection criteria.

## Project Structure

```text
.
├── LICENSE
├── .gitignore
├── README.md
├── planning.txt
└── uni_db.accdb
```

## Database

The database is currently implemented using **Microsoft Access** (`.accdb`).

### Tables

| Table | Description |
|---|---|
| `tbl_CS_Masters` | Universities offering relevant Computer Science master's programmes. |
| `tbl_honours` | Universities offering relevant honours programmes. |
| `tbl_MBA` | Universities offering MBA programmes. |
| `tbl_undergrad` | Universities offering relevant undergraduate programmes. |

Additional tables, relationships, and fields may be introduced as the database develops.

## Ranking System

Universities are currently organised according to a prestige-based ranking, from highest to lowest.

The database is intended to support more detailed comparisons using predefined selection criteria. Rankings and selections are subject to revision as additional information is collected and evaluated.

## Planned Features

- [x] Initial Microsoft Access database.
- [x] Initial programme-category tables.
- [ ] Expand university and programme records.
- [ ] Establish database relationships and standardised fields.
- [ ] Implement selection and filtering criteria.
- [ ] Develop a Delphi-based management application.
- [ ] Implement university comparison functionality.
- [ ] Refine and formalise ranking methodology.

## Technology Stack

- **Database:** Microsoft Access
- **Planned management application:** Delphi

## Project Status

<escape>**Work in progress.**</escape>

The database is incomplete and actively being developed. Information, rankings, and selection criteria are subject to change.


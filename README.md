# University Database

A database project for researching, comparing, and evaluating universities offering Computer Science degrees, postgraduate qualifications, and MBA programmes.

The project aims to centralise university information and facilitate structured comparisons based on predefined academic, institutional, and personal selection criteria.

## About

This project is a collaborative effort between a group of technically inclined high-school leavers who share a common frustration with the lack of accessible, centralised, and transparent information surrounding university programmes and admissions.

University applicants frequently encounter information asymmetry, fragmented programme information, unclear admission requirements, and seemingly arbitrary subject prerequisites that can unnecessarily restrict their academic options.

The objective is to address these issues by compiling, organising, and evaluating university information in a structured database, allowing prospective students to make better-informed academic decisions.

### Project Partners & Contributors

This project is a collaborative initiative between:

**Individual Contributors**
- **Janco Nel** — Project founder and contributor.
- **Christo Louwrens** — Project contributor and founder/owner of [LunexCorp](https://github.com/LunexCorp).

**Organisational Partner**
- [LunexCorp](https://github.com/LunexCorp)
- Private organisation, represented by its founder, Christo Louwrens, and project partner.

This is an independent collaborative initiative and is not affiliated with the universities represented in the database.

This is an independent collaborative initiative and is not affiliated with the universities represented in the database.

## Selection Criteria

The initial undergraduate selection criteria are:

- Must offer a **BSc Computer Science** degree, rather than Information Technology or another related qualification. The focus is on Computer Science as a distinct academic discipline.
- Must not require Physical Sciences as a prerequisite for admission with a South African National Senior Certificate (NSC).

Additional selection criteria may be introduced as the project develops.

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
| `tbl_CS_Masters` | International Universities offering relevant Computer Science master's programmes. |
| `tbl_honours` | South African Universities offering Computer Science honours programmes. |
| `tbl_MBA` | International Universities offering MBA programmes. |
| `tbl_undergrad` | South African Universities offering BSc Computer Science undergraduate programmes. |
|`tbl_MFE` | International Universities offering Financial Engineering degrees|

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
- **Database connectivity:** FireDAC

## Project Status

**Work in progress — Early development.**

This project is actively being developed. The current database represents an initial foundation rather than a completed or comprehensive university directory.

Records, rankings, selection criteria, and database architecture are subject to ongoing revision and expansion.

Information is intended to assist with academic research and university selection. Admission requirements and programme details should always be verified against official university sources before making application decisions.

Contributions, corrections, and suggestions are welcome as the project evolves.

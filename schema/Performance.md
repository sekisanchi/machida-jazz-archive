# Performance Schema

Schema Version: v0.1

## Purpose

Represents participation of musicians in an event.

## Permanent ID

PER-000001

## Required Fields

- Performance ID
- Event ID
- Musician ID
- Unit Name
- Instrument
- Role
- Performance Order
- Notes
- Source ID(s)

## Roles

- Leader
- Co-Leader
- Member
- Guest
- MC
- Lecturer
- Other

## Relationships

A Performance belongs to one Event.

A Performance references one Musician.

Multiple Performance records together describe the complete lineup of an Event.

Every Performance must reference at least one Source.

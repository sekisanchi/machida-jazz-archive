# Event Schema

Schema Version: v0.1

## Purpose

Represents a jazz-related event.

## Permanent ID

EVT-000001

## Required Fields

- Event ID
- Event Title
- Event Type
- Start Date
- End Date
- Venue ID
- Organizer ID(s)
- Description
- Source ID(s)

## Event Types

- Live
- Session
- Festival
- Workshop
- Recording
- Lecture
- Competition
- Broadcast
- Other

## Relationships

An Event is held at one Venue.

An Event may involve multiple Organizations.

An Event includes one or more Performances.

Every Event must reference at least one Source.

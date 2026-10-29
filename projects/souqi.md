# Souqi · سُوقي
**Arabic local-services prototype · HTML / CSS / JavaScript**

[Back to profile](../README.md) · [Portfolio](https://badr-elfahm.github.io/Badr-Elfahm/#souqi)

## The problem
Booking a service involves several perspectives: finding a technician, tracking a request, completing work and leaving feedback. Souqi explores those flows in an Arabic interface.

## The implementation
The local prototype includes customer and technician demo profiles, bookings, completed-request reviews, technician responses and illustrative disputes. Role switching makes the different flows easy to explore on one device.

## Current boundaries
This is a browser-local simulation. It does not provide secure accounts, shared production data, payments, SMS verification, live GPS or a production administration service.

The project includes a proposed Supabase schema, row-level security policies and REST connection scaffolding. The interface has not been connected to a deployed database, and the migration has not yet been tested against PostgreSQL.

## Decisions and next steps
Keep the demo's scope explicit, then validate authentication, database policies and request transitions in a separate test environment before connecting real users. The repository contains local logic checks; these do not establish production database security.

**Source access:** private. This overview contains no customer data, credentials or backend configuration.

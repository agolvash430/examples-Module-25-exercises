# Lab 25 — Service Layer Skeleton

## Constructor deps
CustomerRepository  
Notifier (if activation triggers outbound message)  
Logger

## create TODO
Check duplicate id  
Validate transition rules  
Persist new Customer

## get TODO
Fetch by id  
Throw not‑found if missing  
Return domain object (not JSON)

## Forbidden in this class
HTTP status handling  
JSON mapping  
Direct DB access  
Framework annotations like @RestController

## Scope
Pre-lab only.

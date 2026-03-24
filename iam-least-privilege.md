# IAM Least Privilege Design

## Application Task
The application needs to read data from a storage bucket.

## Policy Design
The role is granted only read permissions.

## Example Permissions
- Read objects
- No write or delete access

## Justification
Restricting permissions reduces security risks and prevents accidental data modification.

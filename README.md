# Hoarder
Hoarder is a deduplication-based backup system that supports compression and authenticated encryption. Hoarder shines when there are multiple servers being backed up, as it stores a single copy of a file and maps all duplicates to a single source.

## Why use this?
Well, you shouldn't yet. It is currently work-in-progress.

## What needs to be done?
1. Clean-up the mess (current state is a block of code that does what it should, but in no way organized or even in a useable state)
2. Add the ability to upload the backup to a remote system (ssh? aws?).
3. Add the ability to restore from a backup server.
4. Write some unit tests.
5. Create test backup data.

## Words of Warning
This is in development and is not considered a full, or partial backup system yet.

Security issues should be reported to mike@currazy.com


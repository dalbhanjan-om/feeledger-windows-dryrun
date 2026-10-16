## What I fixed and how I found it
This was a Windows setup dry run, so there was no ticket work; I only confirmed the app installed, ran, and that finish.php could export.

## What I chose not to change
I did not change application logic, tickets, or opencode.json.

## My own feature
Not built in this dry run; the brief was setup and submission flow only.

## Biggest remaining risk
Candidates on Windows who already have MySQL 8.0 (with a password) can get stuck if they follow the XAMPP-empty-root-password path, and `mysql -u root` over localhost can fail while `-h 127.0.0.1` works.

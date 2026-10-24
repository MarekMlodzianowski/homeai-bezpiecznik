# homeai-bezpiecznik

Job queue of Bezpiecznik, the security executor on homeai. Contract and rules:
[HomeLab server/bezpiecznik/README.md](https://github.com/MarekMlodzianowski/HomeLab/blob/main/server/bezpiecznik/README.md).

- `zadania/<id>.json` — jobs written by the thread "Bezpiecznik" (cloud).
- `wyniki/<id>.json` — results written by the executor on homeai.
- `STOP` at the top — the executor does nothing while it exists. Delete it to resume.

Private. The executor's token can write only here.

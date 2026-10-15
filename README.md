# code-playground

A private playground for collaborative coding sessions: a place to try ideas, prototype, and keep what's worth keeping.

## Context

Shared session context (goals, decisions, tasks, notes) lives in the Google Doc:
[Coding Session Context](https://docs.google.com/document/d/1uDvlc-JqnjVhQ6n9s8Olb72TpKVrwZfJc9P2mOxdEsg/edit)

## Layout

Each experiment gets its own folder at the top level, with its own short README covering what it is and how to run it.

```
code-playground/
├── README.md
└── <experiment-name>/
    └── README.md
```

## Workflow

- `main` holds work that runs.
- Start new work on a branch (`feature/<name>` or `experiment/<name>`) and merge through a pull request.
- Record decisions and open questions in the context doc, so the next session can pick up where this one stopped.

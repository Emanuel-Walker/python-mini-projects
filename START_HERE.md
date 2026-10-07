# Start here

## Goal

Use this repository as a catalog of small Python examples.

Do not try to install or run the whole repository at once.

## 1. Read the status

```text
FORK_STATUS.md
```

## 2. Pick one project

Open:

```text
projects/
```

Choose one folder.

Read that folder's `README.md` first when it has one.

## 3. Create an isolated environment

From the project folder you selected:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Windows PowerShell:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

## 4. Install only that project's dependencies

Use the dependency instructions inside the selected folder.

Do not invent a root-level `requirements.txt`. This fork does not have one.

## Definition of done

One mini-project runs and you understand:
- its inputs
- its output
- its dependencies
- its upstream author/source

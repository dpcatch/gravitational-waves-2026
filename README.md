# Gravitational Waves — ETH Zürich, 2026

Course materials distributed to students via JupyterHub (nbgitpuller).

## Structure

- `week01/`, `week02/`, ... — one folder per week/topic. Add new folders as the course progresses.

## Workflow (updating course materials)

1. Edit or add notebooks locally.
2. `git add .`
3. `git commit -m "short description of what changed"`
4. `git push`

Students get the update the next time they open the JupyterHub link in Moodle.

**Important:** avoid renaming, moving, or deleting files once students may have already pulled them —
nbgitpuller merges updates into each student's workspace and never deletes their local copies, so a
renamed file just leaves a stale duplicate behind rather than actually updating. Prefer adding new
files/folders over restructuring existing ones.

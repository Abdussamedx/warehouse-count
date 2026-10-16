# warehouse-count

The company's stock count. Every counter counts one part of the warehouse, and every count comes in
through a **pull request**: nobody pushes to this repository directly. Kaan reviews each pull
request and merges it.

*Development Environments · Istanbul University, MIS · lab repository*

## How to send your count

1. **Fork** this repository (button at the top right). You get your own copy on GitHub.
2. Clone **your fork**, not this repository.
3. Make a branch: `count-<your-github-username>`.
4. Add **one file**: `counts/<your-github-username>.txt`. Look at `counts/kaan.txt` for the format.
5. Commit, push the branch to your fork, and open a pull request to **this** repository's `main`.
6. Fill in the description: what you counted, why, and how you checked it.

## Rules

- One file per person, named after your GitHub username. Never change somebody else's file.
- One product per line: the name, one space, the number. `Stapler 14`. No empty lines.
- If Kaan asks for a change, do not open a second pull request. Commit the fix on the same branch
  and push: the pull request updates itself.

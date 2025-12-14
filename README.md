# make-blueprints

Version-controlled JSON blueprints for Make.com automation scenarios.

## Purpose

This repository stores exported Make.com scenario blueprints so they can be backed up, documented, and tracked over time with Git.

## Structure

- `*.blueprint.json` – Scenario blueprints exported from Make.com.
  - Each file represents a single scenario and can be re-imported into Make as needed.

## Usage

1. Export a scenario blueprint from Make.com as JSON.  
2. Save or move the file into this repository.  
3. Commit and push the changes to update the history.

## Notes

- Sensitive data (API keys, secrets, or personal identifiers) should be removed or stored in Make connections, not inside blueprints.
- Use descriptive filenames (for example, `student-engagement-monitor.blueprint.json`) to make scenarios easy to identify.

## Visuals

Full DevOps CI/CD Event Pipeline (make-scenario-images/Full DevOps CICD Pipeline.png)

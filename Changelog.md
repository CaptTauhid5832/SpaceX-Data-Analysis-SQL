# Create CHANGELOG.md file
changelog_content = """
# Changelog

All notable changes to this project will be documented in this file.

## [1.0.0] - 2026-04-17
### Added
- Initial release of the SpaceX SQL Analysis notebook.
- SQL queries for Tasks 1 through 10 covering:
    - Launch site identification.
    - Payload mass analysis (Average, Total, Maximum).
    - Mission outcome counts and filtering.
    - Landing outcome ranking within specific date ranges.
- SQLite database integration for Jupyter Notebook.
- README and MIT License files.
"""

with open("CHANGELOG.md", "w") as f:
    f.write(changelog_content.strip())

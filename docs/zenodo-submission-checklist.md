# Zenodo Submission Checklist

## Before GitHub Release

- [ ] Confirm the repository contains only public material.
- [ ] Confirm `README.md` accurately describes the public scope.
- [ ] Confirm `CITATION.cff` has the intended creator name.
- [ ] Confirm `.zenodo.json` has the intended title, description, license, and keywords.
- [ ] Confirm the license is appropriate for public reuse.
- [ ] Validate `schemas/teo.schema.json` as JSON.
- [ ] Create a GitHub release tag, for example `v0.1.0`.

## Zenodo Route

1. Enable the repository in Zenodo's GitHub integration.
2. Create a GitHub release.
3. Wait for Zenodo to archive the release.
4. Copy the minted DOI into `README.md` and `CITATION.cff` if desired.

## Notes

For GitHub release archiving, Zenodo uses `.zenodo.json` metadata when that file is present.


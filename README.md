# Start Here

After unzipping:

cd jimothy-protocol
git init
git branch -M main
git add .
git commit -m "Initialize Jimothy Protocol"

Then create an empty GitHub repository named `jimothy-protocol` and run:

git remote add origin https://github.com/YOURNAME/jimothy-protocol.git
git push -u origin main

If you plan to store large binary art, CAD, audio, or video files:

git lfs install
git lfs track "*.psd"
git lfs track "*.stl"
git lfs track "*.step"
git lfs track "*.mp4"

The included `.gitattributes` already contains recommended LFS patterns.

Suggested next commits:

Document earliest Goodwill sighting
Document Jimothy transition into Metal Mart lore
Add independent postal-route report
Define first accepted morphological invariants
Add first visual manifestation lineage

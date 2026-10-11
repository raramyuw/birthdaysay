Happy Birthday site — Vercel deployment

Files:
- index.html: homepage (must remain at the repository root)
- nako.jpeg, bios.jpeg, vila.jpeg, fam.jpeg: add your own photo files beside index.html

Deploy:
1. Upload index.html and all four photo files to the ROOT of the GitHub repository.
2. In Vercel, open the project > Settings > Build and Deployment.
3. Framework Preset: Other.
4. Root Directory: ./ (repository root).
5. For a plain static HTML project, remove any unnecessary Build Command. Make sure the Output Directory is not incorrectly set to a folder such as `public` if your index.html is in the repository root.
6. Commit/push the files to GitHub, then check Deployments. Open the newest deployment and inspect Build Logs if status is Error.

Photo paths in index.html are ./nako.jpeg, ./bios.jpeg, ./vila.jpeg, ./fam.jpeg.
The photo files were not included in the uploaded HTML attachment, so add your originals yourself.

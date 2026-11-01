# Privacy Policies

A **public** repository that hosts privacy policy pages for Ashraf's apps.
It contains static HTML only — **no source code and no secrets** — so it is safe to be public.

## Structure
```
index.html                      -> landing page listing all apps
concrete-calculator/index.html  -> policy for Concrete Calculator (com.ashraf.concrete_calculator)
dem/index.html                  -> policy for Dem | دەم (com.ashraf.dem)
```
Add a new app later by creating another subfolder with its own index.html
and linking it from the root index.html.

## Hosting (GitHub Pages)
1. Push this folder to a PUBLIC repo (any name, e.g. `privacy`).
2. Repo -> Settings -> Pages -> Source: Deploy from a branch -> Branch: main, Folder: / (root).
3. Live URLs:
   - Landing:               https://<username>.github.io/<repo>/
   - Concrete Calculator:   https://<username>.github.io/<repo>/concrete-calculator/
   - Dem | دەم:             https://ashrafatam96.github.io/privacy/dem/

Put the Concrete Calculator URL in the Google Play Console "Privacy policy URL" field.

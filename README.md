# dreams-lab.github.io

The public site for the [DREAMS Laboratory](https://dreams-lab.github.io/) —
Distributed Robotic Exploration and Mapping Systems, Arizona State University.

Hand-written static HTML and one stylesheet. No build step, no JavaScript, no
webfonts, no analytics. GitHub Pages serves the tree verbatim.

## Structure

```
index.html        the whole site: research, teaching, people, assets, publications
css/site.css      the entire design system
img/              project photographs, people, funder logos
.nojekyll         serve the tree as-is, without Jekyll
```

## Content

The content mirrors the Django portal at `deepgis.org/dreamslab/`, where
people, projects, assets, and publications live in a database. That portal is
the place to edit records; this site is a static copy that stays up when the
server does not. When the two drift apart, the portal is authoritative.

Images were downloaded from the portal rather than hot-linked, and resized to
1400px on the long edge. The originals it pointed at ran as large as 36 MB.

## Preview

```powershell
./serve.ps1          # http://localhost:8743
```

Any static file server works; `serve.ps1` exists only because this machine has
no Python.

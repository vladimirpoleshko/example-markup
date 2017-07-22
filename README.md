# example markup

## Frontend

1. Run `npm install gulp -g`
2. Run `npm install`.
3. Run any local server in public_html folder on 8000 port (for example `python -m http.server 8000` or `php -S localhost:8000`).
4. Run `gulp` to start watching for changes on localhost:3000.

## TASKS

1. `gulp watch` watch for changes in sass, images, scripts, templates without browserSync.
2. `gulp build` building full frontend, copying assets after clean, building sass and templates.
3. `gulp serve` running server for browserSync via proxy (localhost:8000 default)


## Development guides

1. All output pages are in public_html folder.
2. Pages partials (head,header,footer,scripts) in src/templates/partials folder.
3. All main styles are in src/assets/scss folder.

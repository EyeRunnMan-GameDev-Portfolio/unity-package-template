name: docs-on-release

on: workflow_dispatch

jobs:
  build-docs:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3

      - name: copy readme
        run: cp ./README.md ./docfx_project/index.md

      - name: copy changelog
        run: cp ./CHANGELOG.md ./docfx_project/CHANGELOG.md

      - name: Generate build
        uses: nikeee/docfx-action@v1.0.0
        with:
          args: docfx_project/docfx.json

      - name: Deploy to GitHub Pages
        uses: peaceiris/actions-gh-pages@v3
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
          publish_dir: ./docfx_project/_site

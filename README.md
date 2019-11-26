
About Me : https://about.me/aakashpadhiyar

Youtube Channel: https://www.youtube.com/channel/UCtuoofxzdxsmtRtEy27710g

Freelance : https://www.fiverr.com/kanopython

Facebook : https://www.facebook.com/pythonkano/

LinkedIn : https://www.linkedin.com/in/aakashpadhiyar/

# Interactive-Python-Dashboards-with-Plotly-and-Dash

## plotly
>https://github.com/plotly/documentation

# Plotly's github-pages api documentation repository

- the [source-design-merge](http://github.com/plotly/documentation/tree/source-design-merge) branch is where edits and contributions are made
- the [gh-pages](http://github.com/plotly/documentation/tree/gh-pages) branch is the deploy branch, automatically updated with `$ rake deploy` inside [source-design-merge](http://github.com/plotly/documentation/tree/source-design-merge)

interested in contributing? see [Contributing.md](https://github.com/plotly/documentation/blob/source-design-merge/Contributing.md)










## Dash 
>https://github.com/plotly/dash-docs

# Dash Userguide

The [Dash Userguide](https://plot.ly/dash): everything that you need to know to be productive with Dash.

The Dash Userguide is hosted online at: [https://plot.ly/dash](https://plot.ly/dash). A [PDF version](/pdf-docs/Dash_User_Guide_and_Documentation.pdf) is also available.

### Running an app locally

To run an app locally:

1. (optional) create and activate new virtualenv or conda env:

```
pip install virtualenv
virtualenv venv
source venv/bin/activate
```

or, with conda:
```
conda create --yes -n dash_docs
source activate dash_docs
```

2. `pip install -r requirements.txt`
3. `gunicorn run:server`
4. open http://127.0.0.1:8000 in your browser


on Windows systems `waitress` can be a replacement for `gunicorn`

3. `pip install waitress`
4. `waitress-serve --listen=*:8000 run:server`
5. open http://127.0.0.1:8000 in your browser


### Contributing

PRs accepted! The Dash user guide is itself a Dash app. Each file in `tutorial` represents a "chapter" of the docs.

Changes to master will get deployed automatically.


* # Building a portfolio 

We will use mkdocs for building portfolio. MkDocs is a static site generator that's geared towards project documentation. It is written in Python and uses the Jinja2 template engine. MkDocs is designed to be easy to use and configure, making it a great choice for building a portfolio website.

Link to the documentation is [here](https://www.mkdocs.org/getting-started/)

## install mkdocs
```bash
conda create -n mkdocs python=3.12 -y
conda activate mkdocs
pip install mkdocs
```
## create a new mkdocs project
```bash
mkdocs new mara_portfolio
cd mara_portfolio
```
## 3- Run the development server
```bash
```
> this is how you can specify the port and host
```bash
mkdocs serve -a 127.0.0.1:8000
```
## 4- Build the project
```bash
mkdocs build
```
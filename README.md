# SystemProgrammingWiki

Based on the [UIUC CS241 System Programming wiki](https://github.com/angrave/SystemProgramming/wiki).

Intended to be more mobile-friendly version, with better search.

Many intra-wiki links are broken, however.

## Local Copy

You will need to install `mkdocs`:

```shell
pip install mkdocs
```
  
Then clone this locally:

```shell
git clone --recursive https://github.com/csresources/SystemProgrammingWiki.git
```

Once you've cloned it:

```shell
cd SystemProgrammingWiki
mkdocs serve
```  

To deploy to GitHub pages:

```shell
mkdocs gh-deploy --clean
```

## 2017-03-07. Tools for accessing climate site data. A hands-on, interactive session.

**[Anthony Arendt](http://www.apl.washington.edu/people/profile.php?last=Arendt&first=Anthony) and [Emilio Mayorga](http://apl.uw.edu/people/profile.php?last_name=Mayorga&first_name=Emilio), UW-APL**

This week we will have a hands-on, interactive session. We will explore various ways to access climate and hydrology data from public websites, each of which has different ways of serving their products. We'll dig into the pros and cons of various existing Python packages, and focus our discussion around some specific problems we're currently working on.

Climate site datasets we'll look at include [Snotel](https://www.wcc.nrcs.usda.gov/snow/). We'll examine Python packages including [climata](https://pypi.python.org/pypi/climata), [ulmo](http://ulmo.readthedocs.io) and [obsio](https://github.com/jaredwo/obsio).

### Staging the problem. Where to start, what's out there?

- "I need Snotel data". Or more broadly: "I need high-frequency climate/met data on land, in the US"
- Google. Now what? No hits, or too many options?
- Did I find Snotel files? How to access (or download) the data? How to parse (read) the data? What do the header column names mean?

#### Choices:
- Find ("discovery") and access from the provider, from a broader "catalog", from a multi-dataset access package, or ...?
- File downloads vs queries, "services"?
- Code package from the data provider?
- Code packages: single-dataset or multi-dataset focus? Well maintained (recent updates)? Single-person project or some community uptake? Documentation? Examples? Ease of use?
- Access "services", "API's" (Application Programming Interfaces). Custom (narrow) vs standard (broader) API?
- How do I typically want the data transformed to, so I can use my tools? Pandas Dataframes? Netcdf files? csv's?
- Go-to catalogs, web sites, packages?
- Pros and cons to every choice!

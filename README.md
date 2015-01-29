# Notes
* Please feel free to edit these tables, change headings as necessary, group databases and codes into relevant sub-groups, and add information dynamically. 
* For now,  hold off on linking to this page externally, as I will be moving it to be within the Globus github if we see usefulness emerging. 
* This page is written using Github markdown, learn [Github Markdown Basics](https://help.github.com/articles/markdown-basics/) here

# Materials-Related Databases

| Database | Description | Contact | API/Docs | Size| 
| ------------- | ------------- |-----------|------|------| 
| [The Materials Project](https://www.materialsproject.org)  | Harnessing the power of supercomputing and state of the art electronic structure methods, the Materials Project provides open web-based access to computed information on known and predicted materials as well as powerful analysis tools to inspire and design novel materials. | Kristin Persson, Gerbrand Ceder | [python](https://www.materialsproject.org/docs/api)  | 58000 compounds, 33000 band structures|
| [Open Quantum Materials Database (OQMD)](http://oqmd.org)  | The OQMD is a database DFT calculated thermodynamic and structural properties. We are providing this online interface for convenient, small scale access; however for more powerful utilization we recommend downloading the entire database and the API for interfacing with it, detailed in the link below. | Chris Wolverton | [python (qmpy)](http://oqmd.org/static/docs/index.html)  | 285780 compounds|
| [Automatic Flow for Materials Discovery (AFLOW)](http://www.aflowlib.org) | A distributed materials properties repository from high-throughput ab initio calculations | Stefano Curtarolo     | [REST](http://aflowlib.duke.edu/aflowwiki/doku.php?id=documentation:start)  | 630000 compounds |

#Relevant Codes
| Code | Description | Maintained by | API/Docs | 
| ------------- | ------------- |-----------|------| 
| [MAterials Simulation Toolkit (MAST)](http://pythonhosted.org/MAST/index.html)  | MAST is an automated workflow manager and post-processing tool.MAST focuses on diffusion and defect workflows that use density functional theory. It interfaces primarily with the Vienna Ab-initio Simulation Package (VASP).| Dane Morgan | [docs](http://pythonhosted.org/MAST/index.html)  |
| [NWChem](http://www.nwchem-sw.org/index.php/Main_Page)  | NWChem aims to provide its users with computational chemistry tools that are scalable both in their ability to treat large scientific computational chemistry problems efficiently, and in their use of available parallel computing resources from high-performance parallel supercomputers to conventional workstation clusters. | PNNL | [docs](http://www.nwchem-sw.org/index.php/Release65:NWChem_Documentation)  |
| [pymatgen](https://pypi.python.org/pypi/pymatgen)  | Pymatgen-db is a database add-on for the Python Materials Genomics (pymatgen) materials analysis library. It enables the creation of Materials Project-style MongoDB databases for management of materials data. A query engine is also provided to enable the easy translation of MongoDB docs to useful pymatgen objects for analysis purposes. | Materials Genome Initiative | [docs](https://pypi.python.org/pypi/pymatgen)  |
| [pymatgen-db](https://github.com/materialsproject/pymatgen-db)  | Pymatgen (Python Materials Genomics) is a robust, open-source Python library for materials analysis. It currently powers the public Materials Project, an initiative to make calculated properties of all known inorganic materials available to materials researchers. | Materials Genome Initiative | [docs](https://github.com/materialsproject/pymatgen-db)  |
| [Swift](http://swift-lang.org/main/)  | Fast easy parallel scripting - on multicores, clusters, clouds and supercomputers. | University of Chicago / Argonne | [docs](http://swift-lang.org/docs/index.php)  |


# Examples

# API Wrappers



Other Databases to Catalog
* Pickard
* NIST SRD

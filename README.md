# Notes
* Please feel free to edit these tables, change headings as necessary, group databases and codes into relevant sub-groups, and add information dynamically. 
* For now,  hold off on linking to this page externally, as I will be moving it to be within the Globus github if we see usefulness emerging. 
* This page is written using Github markdown, learn [Github Markdown Basics](https://help.github.com/articles/markdown-basics/).

# Materials-Related Databases
These databases are sorted by the number of claimed data entries and by existence of a method of programmatic access

| Database | Description | Contact | API/Docs | Size| 
| ------------- | ------------- |-----------|------|------| 
| [Chemspider](http://www.chemspider.com) | ChemSpider is a free chemical structure database providing fast access to over 32 million structures, properties, and associated information. By integrating and linking compounds from ~500 data sources, ChemSpider enables researchers to discover the most comprehensive view of freely available chemical data from a single online search. It is owned by the Royal Society of Chemistry.|      | [REST](http://www.chemspider.com/AboutServices.aspx?) [python (chemspipy)](http://blog.matt-swain.com/post/16893587098/chemspipy-a-python-wrapper-for-the-chemspider)  | 30 M chemicals and compounds |
| [Automatic Flow for Materials Discovery (AFLOW)](http://www.aflowlib.org) | A distributed materials properties repository from high-throughput ab initio calculations | Stefano Curtarolo     | [REST](http://aflowlib.duke.edu/aflowwiki/doku.php?id=documentation:start)  | 630000 compounds |
| [Open Quantum Materials Database (OQMD)](http://oqmd.org)  | The OQMD is a database DFT calculated thermodynamic and structural properties. We are providing this online interface for convenient, small scale access; however for more powerful utilization we recommend downloading the entire database and the API for interfacing with it, detailed in the link below. | Chris Wolverton | [python (qmpy)](http://oqmd.org/static/docs/index.html)  | 285780 compounds|
| [The Materials Project](https://www.materialsproject.org)  | Harnessing the power of supercomputing and state of the art electronic structure methods, the Materials Project provides open web-based access to computed information on known and predicted materials as well as powerful analysis tools to inspire and design novel materials. | Kristin Persson, Gerbrand Ceder | [python](https://www.materialsproject.org/docs/api)  | 58000 compounds, 33000 band structures|
| [Computational Materials Repository (CMR)](https://wiki.fysik.dtu.dk/cmr/index.html) | The Computational Materials Repository (CMR) provides ways to easily store, retrieve and to search for your electronic structure calculations. |      | [docs](https://wiki.fysik.dtu.dk/cmr/cmr-manual/index.html) [python](https://wiki.fysik.dtu.dk/cmr/install/install.html)  |  |
| [3D Materials Atlas](https://cosmicweb.mse.iastate.edu/wiki/display/home/Materials+Atlas+Home) | The Materials Atlas contains a repository for 3D experiments and simulations on a variety of material systems. |   |   |  |
| [Interatomic Potentials Repository Project](http://www.ctcms.nist.gov/potentials/) | This repository provides a source for interatomic potentials (force fields), related files, and evaluation tools to help researchers obtain interatomic models and judge their quality and applicability. | Chandler Becker (NIST), Zachary Trautt (NIST)  |   |  |
| [Web Force-Field (WebFF)](http://www.nist.gov/mml/msed/polymers/webff.cfm) | The Web Force-Field (WebFF) repository consists of three main components: 1) a database, 2) a software engine, and 3) a web-client interface. The repository database supports a multi-table format, where each table is a distinct force field. | Frederick Phelan (NIST)  |   |  |
| [ThermoML](http://trc.nist.gov/ThermoML.html) | This page contains links to ThermoML files, which represent experimental thermophysical and thermochemical property data reported in the corresponding articles published by major journals in the field. These files are posted here through cooperation between the Thermodynamics Research Center (TRC) at the National Institute of Standards and Technology (NIST) and the journal publishers. |   |   |  |


#Relevant Codes
| Code | Description | Maintained by | API/Docs | 
| ------------- | ------------- |-----------|------| 
| [MAterials Simulation Toolkit (MAST)](http://pythonhosted.org/MAST/index.html)  | MAST is an automated workflow manager and post-processing tool.MAST focuses on diffusion and defect workflows that use density functional theory. It interfaces primarily with the Vienna Ab-initio Simulation Package (VASP).| Dane Morgan | [docs](http://pythonhosted.org/MAST/index.html)  |
| [NWChem](http://www.nwchem-sw.org/index.php/Main_Page)  | NWChem aims to provide its users with computational chemistry tools that are scalable both in their ability to treat large scientific computational chemistry problems efficiently, and in their use of available parallel computing resources from high-performance parallel supercomputers to conventional workstation clusters. | PNNL | [docs](http://www.nwchem-sw.org/index.php/Release65:NWChem_Documentation)  |
| [pymatgen](https://pypi.python.org/pypi/pymatgen)  | Pymatgen-db is a database add-on for the Python Materials Genomics (pymatgen) materials analysis library. It enables the creation of Materials Project-style MongoDB databases for management of materials data. A query engine is also provided to enable the easy translation of MongoDB docs to useful pymatgen objects for analysis purposes. | Materials Genome Initiative | [docs](https://pypi.python.org/pypi/pymatgen)  |
| [pymatgen-db](https://github.com/materialsproject/pymatgen-db)  | Pymatgen (Python Materials Genomics) is a robust, open-source Python library for materials analysis. It currently powers the public Materials Project, an initiative to make calculated properties of all known inorganic materials available to materials researchers. | Materials Genome Initiative | [docs](https://github.com/materialsproject/pymatgen-db)  |
| [Swift](http://swift-lang.org/main/)  | Fast easy parallel scripting - on multicores, clusters, clouds and supercomputers. | University of Chicago / Argonne | [docs](http://swift-lang.org/docs/index.php)  |
* DiffPy - http://www.diffpy.org
* Dream3D - http://www.immijournal.com/content/3/1/5
* pyDOE (Design of Experiments) - http://pythonhosted.org/pyDOE/#capabilities
* Scipy
* Numpy
* Pandas
* Nexpy

#Cloud Services

* Globus (https://www.globus.org)
* Globus Data Publication (beta)
* Globus Catalog (beta)
* FigShare
* Center for Open Science (http://centerforopenscience.org)
* Dataverse - http://dataverse.org
* SEAD - http://sead-data.net


# Examples

# API Wrappers



# Other Databases, Codes,  and Efforts to Sort and Catalog
* Pickard
* NIST SRD
* MatNavi (Registration required) - http://mits.nims.go.jp/index_en.html
* The Landolt-Börnstein Database (fee)
* ProQuest Materials Science Collection (fee) http://www.springermaterials.com
* Knovel (subscription required) http://app.knovel.com/web/

* PRISMS - http://prisms.engin.umich.edu/#/prisms
* FigShare - http://figshare.com
* PURR - https://purr.purdue.edu
* ScholarSphere - https://scholarsphere.psu.edu
* ESTest - http://estest.ucdavis.edu
* Quixote
* Computational Materials Repository (CMR) - https://wiki.fysik.dtu.dk/cmr/
* Materials Data Facility (MDF)
* National Data Service (NDS) - http://www.nationaldataservice.org
* NDS-Labs
* CHiMaD - http://chimad.northwestern.edu
* DSpace http://www.dspace.org
* Duracloud - http://duracloud.org
* Fedora - http://duraspace.org/about_fedora
* Quantum Materials Informatics Project (QMIP)
* NIST Computational File Repository - http://nist.matdl.org/dspace/xmlui/handle/11115/52
* Research Data Alliance - https://rd-alliance.org
* European Data Infrastructure - http://www.eudat.eu
* Scientific data repositories on the Web: An initial survey (article) - http://onlinelibrary.wiley.com/doi/10.1002/asi.21339/full
* Dryad (bio) - http://www.datadryad.org
* Registry of Research Databases - http://www.re3data.org

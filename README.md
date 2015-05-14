# Notes
* Please feel free to edit these tables, change headings as necessary, group databases and codes into relevant sub-groups, and add information dynamically. 
* For now,  hold off on linking to this page externally, as I will be moving it to be within the Globus github if we see usefulness emerging. 
* This page is written using Github markdown, learn [Github Markdown Basics](https://help.github.com/articles/markdown-basics/).

# Materials-Related Databases
These databases are sorted by the number of claimed data entries and by existence of a method of programmatic access

| Database | Description | Contact | API/Docs | Size| 
| ------------- | ------------- |-----------|------|------| 
| [Chemspider](http://www.chemspider.com) | ChemSpider is a free chemical structure database providing fast access to over 32 million structures, properties, and associated information. By integrating and linking compounds from ~500 data sources, ChemSpider enables researchers to discover the most comprehensive view of freely available chemical data from a single online search. It is owned by the Royal Society of Chemistry.|      | [REST](http://www.chemspider.com/AboutServices.aspx?) [python (chemspipy)](http://blog.matt-swain.com/post/16893587098/chemspipy-a-python-wrapper-for-the-chemspider)  | 30 M chemicals and compounds |
| [CCDC (Cambridge Crystallographic Data Centre)](http://www.ccdc.cam.ac.uk/Solutions/CSDSystem/Pages/CSD.aspx) | CSD is the world’s repository for small-molecule organic and metal-organic crystal structures. Containing the results of over half-a-million x-ray and neutron diffraction analyses this unique database of accurate 3D structures has become an essential resource to scientists around the world. |      |  | >700k X-ray and neutron diffraction analyses and 3D structures  |
| [Automatic Flow for Materials Discovery (AFLOW)](http://www.aflowlib.org) | A distributed materials properties repository from high-throughput ab initio calculations | Stefano Curtarolo     | [REST](http://aflowlib.duke.edu/aflowwiki/doku.php?id=documentation:start)  | 630000 compounds |
| [Open Quantum Materials Database (OQMD)](http://oqmd.org)  | The OQMD is a database DFT calculated thermodynamic and structural properties. We are providing this online interface for convenient, small scale access; however for more powerful utilization we recommend downloading the entire database and the API for interfacing with it, detailed in the link below. | Chris Wolverton | [python (qmpy)](http://oqmd.org/static/docs/index.html)  | 285780 compounds|
| [The Materials Project](https://www.materialsproject.org)  | Harnessing the power of supercomputing and state of the art electronic structure methods, the Materials Project provides open web-based access to computed information on known and predicted materials as well as powerful analysis tools to inspire and design novel materials. | Kristin Persson, Gerbrand Ceder | [python](https://www.materialsproject.org/docs/api)  | 58000 compounds, 33000 band structures|
| [Computational Materials Repository (CMR)](https://wiki.fysik.dtu.dk/cmr/index.html) | The Computational Materials Repository (CMR) provides ways to easily store, retrieve and to search for your electronic structure calculations. |      | [docs](https://wiki.fysik.dtu.dk/cmr/cmr-manual/index.html) [python](https://wiki.fysik.dtu.dk/cmr/install/install.html)  |  |
| [3D Materials Atlas](https://cosmicweb.mse.iastate.edu/wiki/display/home/Materials+Atlas+Home) | The Materials Atlas contains a repository for 3D experiments and simulations on a variety of material systems. |   |   |  |
| [Interatomic Potentials Repository Project](http://www.ctcms.nist.gov/potentials/) | This repository provides a source for interatomic potentials (force fields), related files, and evaluation tools to help researchers obtain interatomic models and judge their quality and applicability. | Chandler Becker (NIST), Zachary Trautt (NIST)  |   |  |
| [Web Force-Field (WebFF)](http://www.nist.gov/mml/msed/polymers/webff.cfm) | The Web Force-Field (WebFF) repository consists of three main components: 1) a database, 2) a software engine, and 3) a web-client interface. The repository database supports a multi-table format, where each table is a distinct force field. | Frederick Phelan (NIST)  |   |  |
| [ThermoML](http://trc.nist.gov/ThermoML.html) | This page contains links to ThermoML files, which represent experimental thermophysical and thermochemical property data reported in the corresponding articles published by major journals in the field. These files are posted here through cooperation between the Thermodynamics Research Center (TRC) at the National Institute of Standards and Technology (NIST) and the journal publishers. |   |   |  |
* Computational Materials Data Network (CMD Network) - http://www.asminternational.org/web/cmdnetwork

#Cloud Services

* Globus (https://www.globus.org)
* Globus Data Publication (beta)
* Globus Catalog (beta)
* FigShare - http://figshare.com
* Center for Open Science (http://centerforopenscience.org)
* Dataverse - http://dataverse.org
* SEAD - http://sead-data.net
* Citrine Informatics - http://www.citrine.io
* Dryad - http://www.datadryad.org
* PRISMS - http://prisms.engin.umich.edu/#/prisms (in development)
* Zenodo - https://zenodo.org/
* SeedMe - https://www.seedme.org
* DOE Pages - http://www.osti.gov/pages/
* NSF public access repository - TBD
* Socrata - http://www.socrata.com/products/open-data-portal/



#Relevant Codes
| Code | Description | Maintained by | API/Docs | 
| ---- | ----------- |---------------|----------| 
| [MAterials Simulation Toolkit (MAST)](http://pythonhosted.org/MAST/index.html)  | MAST is an automated workflow manager and post-processing tool.MAST focuses on diffusion and defect workflows that use density functional theory. It interfaces primarily with the Vienna Ab-initio Simulation Package (VASP).| Dane Morgan | [docs](http://pythonhosted.org/MAST/index.html)  |
| [NWChem](http://www.nwchem-sw.org/index.php/Main_Page)  | NWChem aims to provide its users with computational chemistry tools that are scalable both in their ability to treat large scientific computational chemistry problems efficiently, and in their use of available parallel computing resources from high-performance parallel supercomputers to conventional workstation clusters. | PNNL | [docs](http://www.nwchem-sw.org/index.php/Release65:NWChem_Documentation)  |
| [pymatgen](https://pypi.python.org/pypi/pymatgen)  | Pymatgen-db is a database add-on for the Python Materials Genomics (pymatgen) materials analysis library. It enables the creation of Materials Project-style MongoDB databases for management of materials data. A query engine is also provided to enable the easy translation of MongoDB docs to useful pymatgen objects for analysis purposes. | Materials Genome Initiative | [docs](https://pypi.python.org/pypi/pymatgen)  |
| [pymatgen-db](https://github.com/materialsproject/pymatgen-db)  | Pymatgen (Python Materials Genomics) is a robust, open-source Python library for materials analysis. It currently powers the public Materials Project, an initiative to make calculated properties of all known inorganic materials available to materials researchers. | Materials Genome Initiative | [docs](https://github.com/materialsproject/pymatgen-db)  |
| [Swift](http://swift-lang.org/main/)  | Fast easy parallel scripting - on multicores, clusters, clouds and supercomputers. | University of Chicago / Argonne | [docs](http://swift-lang.org/docs/index.php)  |
* DiffPy - http://www.diffpy.org
* DANSE - http://danse.us/ReleasePages.html
* QBOX - http://eslab.ucdavis.edu/software/qbox/
* Quantum Espresso - http://www.quantum-espresso.org
* VASP - http://www.vasp.at
* Dream3D - http://www.immijournal.com/content/3/1/5
* pyDOE (Design of Experiments) - http://pythonhosted.org/pyDOE/#capabilities
* Nexpy - https://github.com/nexpy/nexpy
* TomoPy - https://github.com/tomopy/tomopy
* IPython


### Python Machine Learning Stack and Resources
| Code | Description | Docs | 
| ---- | ----------- | ---- | 
|[scikit-learn](http://scikit-learn.org/stable/) | Machine learning in Python. Simple and efficient tools for data mining and data analysis. | [docs](http://scikit-learn.org/stable/documentation.html)|
|[SciPy](http://www.scipy.org) | Python-based ecosystem of open-source software for mathematics, science, and engineering. |[docs](http://www.scipy.org/docs.html) |
|[numpy](http://www.numpy.org) |NumPy is the fundamental package for scientific computing with Python. It contains among other things: a powerful N-dimensional array object; sophisticated (broadcasting) functions;tools for integrating C/C++ and Fortran code;useful linear algebra, Fourier transform, and random number capabilities | [docs](http://docs.scipy.org/doc/)|
|[pandas](http://pandas.pydata.org) |Python package providing fast, flexible, and expressive data structures designed to make working with “relational” or “labeled” data both easy and intuitive. It aims to be the fundamental high-level building block for doing practical, real world data analysis in Python.  | [docs](http://pandas.pydata.org/pandas-docs/version/0.15.2/) |
* [SciPy 2013 scikit-learn Complete Workshop Tutorial](https://www.youtube.com/watch?v=r4bRUvvlaBw)
* [SciPy 2013 scikit-learn Complete Example Code](https://github.com/jakevdp/sklearn_scipy2013)
* [Tutorials on network analysis, Discovery Engines Workshop at Computation Institute, Mar 18 2015] (https://github.com/KnowledgeLab/CI-Workshop-Networks)

# API Wrappers



# Other Databases, Codes,  and Efforts to Sort and Catalog
* NIST SRD - http://www.nist.gov/srd/
* MatNavi (Registration required) - http://mits.nims.go.jp/index_en.html
* ProQuest Materials Science Collection (fee) http://www.springermaterials.com
* Knovel (subscription required) http://app.knovel.com/web/
* PURR - https://purr.purdue.edu
* ScholarSphere - https://scholarsphere.psu.edu
* ESTest - http://estest.ucdavis.edu
* Computational Materials Repository (CMR) - https://wiki.fysik.dtu.dk/cmr/
* Materials Data Facility (MDF) - http://mdf.ncsa.illinois.edu
* National Data Service (NDS) - http://www.nationaldataservice.org
* CHiMaD - http://chimad.northwestern.edu
* DSpace http://www.dspace.org
* Duracloud - http://duracloud.org
* Fedora - http://duraspace.org/about_fedora
* Quantum Materials Informatics Project (QMIP)
* NIST Computational File Repository - http://nist.matdl.org/dspace/xmlui/handle/11115/52
* Research Data Alliance - https://rd-alliance.org
* European Data Infrastructure - http://www.eudat.eu
* Scientific data repositories on the Web: An initial survey (article) - http://onlinelibrary.wiley.com/doi/10.1002/asi.21339/full
* Registry of Research Databases - http://www.re3data.org
* ChemSpider SyntheticPages - cssp.chemspider.com
* MatData.net - http://www.matdata.net/index.js
* MatWeb - http://www.matweb.com
* Granta - http://www.grantadesign.com
* NIST Materials Repositories (DSPACE) - https://materialsdata.nist.gov/dspace/xmlui/
* NIST Materials Data Curation System - https://github.com/usnistgov/MDCS
* NoMad - http://nomad-repository.eu/cms/
* NanoHub - https://nanohub.org/
* NIMS - http://www.nims.go.jp/eng/
* SpringerMaterials - Landolt-Börnstein Database (fee) - http://www.springermaterials.com/docs/index.html
* CatApp - http://slac.stanford.edu/~strabo/catapp/CatApp.html
* Harvard Clean Energy Project - http://cleanenergy.molecularspace.org/
* Software Carpentry (basic) - http://software-carpentry.org/
* Hubzero - https://hubzero.org
* Digital Science - http://www.digital-science.com
* Overleaf - http://www.digital-science.com/products/overleaf
* Dimensions - http://www.digital-science.com/products/dimensions-for-universities
* LabGuru - http://www.labguru.com
* Accelrys (now Biovia?) - http://accelrys.com
* Jupyter - http://jupyter.org
* Parallel.Works - http://parallel.works/
* Inscites (project lead is a contributor to this document)
* NDS-Labs (in development) - http://labsportal.nationaldataservice.org/
* Mendeley - http://www.mendeley.com
* Authorea - https://www.authorea.com/
* Overleaf - https://www.overleaf.com
* Plot.ly - https://plot.ly
* Datacite - https://www.datacite.org/
* Dat Data - http://dat-data.com/
* NIDDK Information Network - http://www.dknet.org/
* DataOne - https://www.dataone.org
* Pickard - can't find...
* Quixote - can't find...
* Islandora - http://islandora.ca
* EuDat - http://www.eudat.eu
* Archivematica - https://ww.archivematica.org/en/
* Jetstream - http://pti.iu.edu/jetstream/
* iRODS - http://irods.org
* Zenodo - http://zenodo.org
* Invenio - http://invenio-software.org
* Data Type Registry - http://typeregistry.org/registrar/
* Schemas - http://schema.org
* Ontologies - http://www.ebi.ac.uk/ontology-lookup/

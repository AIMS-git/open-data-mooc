# Lesson 3.1: Managing datasets

![Photo by Neil Palmer \(CIAT\) licensed under CC BY-SA 2.0](../.gitbook/assets/image%20%2861%29.png)

## Aims and learning outcomes

**The lesson aims to:**

*  explain basic principles behind data management
* introduce the process of preparing a data management plan
* explain concepts on data storage, versioning and documentation practices.

**After studying this lesson, you should be able to:**

*  identify the steps to ensure that good scientific data management practices are followed
* prepare a data management plan 
* understand the potential of using data storage and versioning good practices.

## 1. Data management

Many datasets are inherently ephemeral: market data, production and consumption data, and weather data are good examples. These data are meaningless unless we know the timeframe for them and they are updated regularly. Soil data, for example, are similar, even if not updated as often as weather and market data. They change by location and during the course of – and between – seasons.

In order to build and maintain trust in open data such as these and others, it is necessary to have stable data management principles and practices in place. Good **data management principles** help to ensure that data produced or used are registered, stored, made accessible for use and reuse, managed over time and/or disposed of, according to legal, ethical, funder requirements and good practice. For open data consumers, trust depends on numerous factors:

* _Knowing the source_. Trust in data begins with knowledge of its source.
* _Trusting the source_. If you know that data comes from a trusted source, then you can rely on it, and on the conclusions you draw from it.
* _Timeliness of the data_. Even when from a trusted source, data is not useful if it is outdated.
* _Data quality_. Trusted data must accurately and precisely reflect what it measures.
* _Sustainability_. A trusted dataset must have some guarantee of availability.
* _Discoverability_. Like documents, data is only useful if it is straightforward to find.
* _Documentation and support_. Consumers should be able to access support for data if needed.
* _Interaction_. Consumers should be able to provide feedback if there is a problem with data.

**Data management** therefore, is a process involving a broad range of activities from administrative to technical aspects of handling data \(Gordon ed. 2015\) in a manner that addresses the factors listed above.  A sound data management policy will define strategic long-term goals for data management across all aspects of a project or enterprise.

**A data management policy** is a set of high-level principles that establish a guiding framework for data management. A data management policy can be used to address strategic issues such as data access, relevant legal matters, data stewardship issues and custodial duties, data acquisition, and other issues. As it provides a high-level framework, the data management policy should be flexible and dynamic. This allows for it to readily adapt to unanticipated challenges, different types of projects and potentially opportunistic partnerships while still maintaining its guiding strategic focus. The data management policy will help inform and develop a **data management plan**, which will be discussed more in this lesson.

In order to meet data management goals and standards, all involved parties must understand their associated **roles and responsibilities**. The objectives of delineating data management roles and responsibilities are to:

* clearly define roles associated with functions
* establish data ownership throughout all phases of a project
* instil data accountability
* ensure that adequate, agreed-upon data quality and metadata metrics are maintained on a continuous basis.

**Quality** as applied to data has been defined as fitness for use or potential use. Many data quality principles apply when dealing with species data and with the spatial aspects of those data. These principles are involved at all stages of the data management process, beginning with data collection and capture. A loss of data quality at any one of these stages reduces the applicability and uses to which the data can be adequately put.

All of these affect the final quality or fitness for use of the data and apply to all aspects of the data. Data quality standards may be available for:

* accuracy
* precision
* resolution
* reliability
* repeatability
* reproducibility
* currency
* relevance
* ability to audit
* completeness
* timeliness.

Data quality is assessed by applying verification and validation procedures as part of the quality control process. Verification and validation are important components of data management that help ensure data is valid and reliable.

Some of the data management principles described in this unit also borrow from principles of research data management \(RDM\). Good RDM principles can be applied to open data initiatives with success, thereby ensuring:

* enhanced visibility and discovery of the datasets
* facilitation of longevity and the sharing and reuse of the datasets
* data users’ understanding of the content context and the limitations of datasets
* reduction of the risk of data loss by keeping it safe and secure
* interoperability of datasets and data exchange
* compliance with funders’ and/or institutional expectations and policies
* provision of opportunities for collaboration with others who might engage with the data.

### 1.1.          The diversity of data

Data may be viewed as the lowest level of abstraction from which information and knowledge are derived. Data may also be viewed as the level at which measurements were originally collected, e.g. individual responses to a survey or census; hourly measures of temperature, wind speed and wind direction; number and price of shares traded in each stock buy/sell transaction; etc.

However, the word data means different things to different people in different contexts. Different disciplines have and use discipline-specific language around the subject research data\[[1](http://mantra.edina.ac.uk)\].

**Table 1** Various types of data as encountered in different contexts and disciplines

<table>
  <thead>
    <tr>
      <th style="text-align:left"></th>
      <th style="text-align:left"><b>         Types of Data</b>
      </th>
      <th style="text-align:left"></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">General</td>
      <td style="text-align:left">Social sciences</td>
      <td style="text-align:left">Physical/agricultural data</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <p>&#x25CF;images</p>
        <p>&#x25CF;video</p>
        <p>&#x25CF;mapping/GIS data</p>
        <p>&#x25CF;numerical measurements</p>
      </td>
      <td style="text-align:left">
        <p>&#x25CF;survey responses</p>
        <p>&#x25CF;focus group and individual interview transcripts</p>
        <p>&#x25CF;economic indicators</p>
        <p>&#x25CF;demographics</p>
        <p>&#x25CF;opinion polling</p>
      </td>
      <td style="text-align:left">
        <p>&#x25CF;measurements generated by sensors/laboratory instruments</p>
        <p>&#x25CF;computer modelling</p>
        <p>&#x25CF;simulations</p>
        <p>&#x25CF;observations and/or field studies</p>
        <p>&#x25CF;specimen</p>
      </td>
    </tr>
  </tbody>
</table>Data can therefore be generated for different purposes and through different processes in a multitude of digital formats. The following classification was compiled by the Research Information Network:

* **Observational:** data captured in real time, usually unique and irreplaceable, e.g. brain images, survey data
* **Experimental:** data from experimental results, e.g. from lab equipment, often reproducible, but can be expensive, e.g. chromatograms, microassays
* **Simulation:** data generated from test models where model and metadata may be more important than output data from the model, e.g. economic or climate models
* **Derived or compiled:** resulting from processing or combining 'raw' data, often reproducible but expensive, e.g. compiled databases, text mining, aggregate census data
* **Reference or canonical:** a \(static or organic\) conglomeration or collection of smaller \(peer-reviewed\) datasets, most probably published and curated, e.g. gene databanks, crystallographic databases.

In the next section we will describe the basic data management considerations to be made during the lifecycle of data i.e. from creation and initial storage to the time when it becomes obsolete and is deleted.

### 1.2.          Metadata and documentation

All datasets should be identified and documented to facilitate their subsequent identification, proper management and effective use, and to avoid collecting the same data more than once. To provide an accurate list of datasets held by an organisation, a catalogue of data should be compiled. This is a collection of discovery-level metadata for each dataset, in a form suitable for users to reference. These metadata should provide information about the content, geographic extent, currency and accessibility of the data, together with contact details for further information about the data.

All datasets, once catalogued, should also be documented in a detailed form suitable for users to reference when using the data. These detailed metadata should describe the content, characteristics and use of the dataset, using a standard detailed metadata template.

#### 1.2.1.  Metadata

Metadata, or ‘data about data’ explains your dataset and allows you to document important information for:

* finding the data later
* understanding what the data is later
* sharing the data \(both with collaborators and future secondary data users\).

It should be considered an investment of time that will save you trouble later several-fold.

#### 1.2.2    Examples

* Dublin Core
* Darwin Core
* FGDC \(Federal Geographic Data Committee\)
* DDI \(Data Documentation Initiative\)
* ABCD \(Access to Biological Collections Data\)
* CSDGM \(Content Standard for Digital Geospatial Metadata\).

A distinction that is often cited when dealing with data management is that of data vs. metadata \(i.e. data about data\). There are a number of specific distinctions that these might refer to:

* Metadata as schema. When we collect tabular data, we need to know what the ‘columns’ in the data refer to. Even in non-tabular data, some schema information is helpful for interpreting the data. Many data formats include ways to specify schema metadata, e.g. XSD for XML, RDFS for RDF, and DDL for databases.
* Bibliographic metadata. Librarians and library scientists have used metadata to describe documents \(books, articles, pictures, etc\) for centuries, and have determined structures for recording and searching this kind of metadata. This sort of metadata includes provenance information \(authorship, publication data\), dates, size of the publication \(e.g. in page count\), and is applicable to datasets as well \(e.g. DCAT27 and VoID28\).
* Shared vocabulary. Alignment of different datasets is a challenge in any distributed setting. A key tool in governing such datasets is the use of a shared vocabulary. The vocabulary is used in the content of the data, rather than describing the data per se. For example, the [AGROVOC](http://aims.fao.org/vest-registry/vocabularies/agrovoc-multilingual-agricultural-thesaurus) \(for AGRiculture VOCabulary\) provides \(amongst other things\) terminology for talking about agricultural products, e.g. milk, milk byproducts, milk fat, etc. [Agroportal](http://agroportal.lirmm.fr) and the [VEST registry](http://aims.fao.org/vest-registry) provide access to many vocabularies related to agriculture and land.

#### 1.2.3 File Contents

In order for others to use the data, they must understand the contents of the dataset, including the parameter names, units of measure, formats, and definitions of coded values. At the top of the file, include several header rows containing descriptors that link the data file to the dataset \(for example, the data file name, dataset title, author, today‘s date, the date the data within the file was last modified, and companion file names\). Other header rows should describe the content of each column, including one row for parameter names and one for parameter units. For those datasets that are large and complex and may require a lot of descriptive information about dataset contents, that information may be provided in a separate linked document rather than as headers in the data file itself.

* _Parameters_. The parameters reported in datasets need to have names that describe their contents, and their units need to be defined so that others understand what is being reported. Use commonly accepted parameter names. A good name is short, unique \(at least within a given dataset\), and descriptive of the parameter contents. Column headings should be constructed for easy importing by various data systems. Use consistent capitalisation and use only letters, numerals, and underscores – no spaces or decimal characters – in the parameter name. Choose a consistent format for each parameter and use that format throughout the dataset. When possible, try to use standardised formats, such as those used for dates, times, and spatial coordinates.

All cells within each column should contain only one type of information \(e.g., text, numbers, etc.\). Common data types include text, numeric, date/time, Boolean \(Yes/No or True/False\), and comments, used for storing large quantities of text.

* _Coded Fields_. Coded fields, as opposed to free text fields, often have standardised lists of predefined values from which the data provider may choose. Data collectors may establish their own coded fields with defined values to be consistently used across several data files. Coded fields are more efficient for the storage and retrieval of data than free text fields.
* _Missing Values_. There are several options for dealing with a missing value. One is to leave the value blank, but this poses a problem as some software does not differentiate a blank from a zero, or a user might wonder if the data provider accidentally skipped a column. Another option is to put a period where the number would go. This makes it clear that a value should be there, although it says nothing about why the data is missing. One more option is to use different codes to indicate different reasons why the data is missing.

### 1.3.          Security and storage

Effective data sharing depends on a strong network of trust between data providers and consumers. Infrastructure for data sharing will not be used if the parties who provide and use the data do not trust the infrastructure or one another. If sensitive data is to be shared, there must be provisions in the platform to ensure security of that data. Whether data is closed or shared with specific individuals or organisations, it will need to be hosted in a controlled way. Depending on the sensitivity of the data, this will include some guarantee of security, e.g. against hacking. In the most extreme cases, the security requirements for shared data in agriculture could be as severe as for shared data in the military. These principles are not unique to agricultural data, and have been studied in depth.

The basic concepts behind these principles are that services should be hard to compromise, that a compromise should be easy to detect, and that the impact of a compromise can be contained. For open data, this is much less of a concern, but to build trust among data providers, some support for data security must be in place.

Some important physical dataset storage and archiving considerations for electronic/digital data include:

* _Server hardware and software_. What type of database will be needed for the data?  Will any physical system infrastructure need to be set up or is the infrastructure already in place? Will a major database product be necessary? \(See Lesson 3.3 on Creating Open Data Repositories for software platforms.\) Who will oversee the administration of this system?
* _Network infrastructure_. For open data the database needs to be connected to the internet for accessibility. How much bandwidth is required to serve the target audience? What hours of the day does it need to be accessible?
* _Size and format of datasets_. The size of a dataset should be estimated so that storage space can properly be accounted for. The types and formats should be identified so that no surprises in the form of database capabilities and compatibility will arise.
* _Database maintenance and updating_. A database or dataset should have carefully defined procedures for updating. If a dataset is live or ongoing, this will include such things as additions, modifications, and deletions, as well as frequency of updates. Versioning will be extremely important when working in a multi-user environment.
* _Database backup and recovery requirements_. The requirements for the backing up or recovery of a database in case of user error, software/media failure, or disaster, should be clearly defined and agreed upon to ensure the longevity of a dataset. Mechanisms, schedules, frequency and types of backups, and appropriate recovery plans should be specified and planned. This can include types of storage media for onsite backups and whether off-site backing up is necessary.

### 1.4.          Data access and dissemination

Data production is one thing, its dissemination is another. Open data is useful when it can be delivered into the right hands \(or the right machine\) and within a context where it can be most valuable. In some cases, this might be a laboratory researching the efficacy of a treatment \(for example, the effectiveness of herbicide for treating some pest\). Sometimes the data must be delivered into the field, so it can be used to help a smallholder make informed decisions on which crop varieties to grow or which treatments to apply. There must be a variety of data delivery channels, fine-tuned to each case for data delivery. The ‘fine-tuning’ of data delivery channels can become a business opportunity for data intermediaries in the case where the data is fully ‘open’. An intermediary can provide services to customise data delivery for the vast range of customers that might exist for the data. Open data creates the possibility of a marketplace, where alternative sources of relevant data are available.

To be made available, data has to be stored in a way that makes it accessible. Even in the modern era of cloud deployment, the data and applications are stored on some hardware somewhere, even if it is virtualised. A strategy for sharing data on a global scale must specify where it will be stored and what service level agreements \(SLAs\) will be maintained \(up time, throughput, access controls, etc\).

The following should strongly be considered when deciding how to disseminate data:

* access to the data should be provided in line with the organisation’s data policy and the national laws/acts on access to information
* access to data should be granted without infringing the copyright or intellectual property rights of the data or any statutory/departmental obligations.

## 2. Data management plans

Funders are increasingly demanding the development of data management plans as a condition for funding.\[[2](https://ocw.mit.edu/resources/res-str-002-data-management-spring-2016/workshop-materials/MITRES_STR002S16_IntroDM.pdf)\] The requirements are usually to allow for the sharing of outputs of projects or research, including data \(and publications\). For example, the EU has published [new guidelines on data management](https://ec.europa.eu/research/participants/data/ref/h2020/grants_manual/hi/oa_pilot/h2020-hi-oa-data-mgt_en.pdf) in Horizon 2020 research projects as of December 2013.

The planning process for data management begins with a data planning checklist. A checklist later assists in the development of a data management plan. That checklist might include considering some or all of the following questions.

* What data will you collect or create, how will it be created, and for what purpose?
* How will you manage any ethical issues? How will you manage copyright and intellectual property rights issues?
* What file formats will be used? Are they non-proprietary, transparent and sustainable? What directory and file naming conventions will be used? Are there any formal standards that you will adopt? What documentation and metadata will accompany the data?
* How will the data be stored and backed up? How will you manage access and security? Who will be responsible for data management?
* Are there existing procedures that you will base your approach on? For example, are there institutional data protection or security policies to follow, department or group data management guidelines, defined by your institution or funder that must be considered?
* What is the long-term preservation plan for the dataset? For example, which data should be retained, shared, and/or preserved? How will you share the data, and are any restrictions on data sharing required?
* What resources will you require to deliver your plan? For example, are there tools or software needed to create, process or visualise the data?

More can be added to or subtracted from this suggested list depending on the nature of the project. A more detailed[ checklist](www.dcc.ac.uk/sites/default/files/documents/resource/DMP_Checklist_2013.pdf) is available from the Digital Curation Centre.

**Important to note:** Data management plans must be continuously maintained and kept up-to-date throughout the course of a project or research.

**Table 2** Components of a data management plan

<table>
  <thead>
    <tr>
      <th style="text-align:left">Component</th>
      <th style="text-align:left">Details</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">Administrative information</td>
      <td style="text-align:left">
        <p>&#x25CF; Name and ID of the project</p>
        <p>&#x25CF; Project Description</p>
        <p>&#x25CF; Funding body/bodies</p>
        <p>&#x25CF; Project Data Contact</p>
        <p>&#x25CF; Related Policies</p>
        <p>&#x25CF; Date of First Version</p>
        <p>&#x25CF; Date of Last Update</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Data collection</b>
      </td>
      <td style="text-align:left">
        <p>&#x25CF; Data description, including anticipated type, format and volume</p>
        <p>&#x25CF; Existing datasets to be re-used</p>
        <p>&#x25CF; Methods by which data will be collected or created</p>
        <p>&#x25CF; Structures, naming and versioning system for folders and files</p>
        <p>&#x25CF; Quality assurance processes</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Documentation and metadata</b>
      </td>
      <td style="text-align:left">
        <p>&#x25CF; A list of information you expect will be needed for the data
          to be read and interpreted in the future</p>
        <p>&#x25CF; How you plan to collect or create this documentation and metadata</p>
        <p>&#x25CF; The metadata standards you will use</p>
        <p><b>Some examples of data documentation</b>:</p>
        <p>&#x25CF; Laboratory notebooks &amp; experimental protocols</p>
        <p>&#x25CF; Questionnaires, codebooks, data dictionaries</p>
        <p>&#x25CF; Software syntax and output files</p>
        <p>&#x25CF; Information about equipment settings &amp; instrument calibration</p>
        <p>&#x25CF; Database schema</p>
        <p>&#x25CF; Methodology reports</p>
        <p>&#x25CF; Provenance information about sources of derived data</p>
        <p>Add detailed descriptions for collections or files, e.g. what is in a
          file, where did it come from, how could it be retrieved if needed, any
          existing problems etc.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Ethics and legal compliance</b>
      </td>
      <td style="text-align:left">
        <p><b>Ethics</b>
        </p>
        <p>&#x25CF; Details of consent needed for data preservation and sharing</p>
        <p>&#x25CF; Steps to be taken, if needed, to protect the identity of any
          participants</p>
        <p>&#x25CF; Steps to be taken, if needed, to ensure sensitive data is stored
          and transferred securely</p>
        <p><b>Copyright and Intellectual Property Rights</b>
        </p>
        <p>&#x25CF; Name(s) of the owner(s) of the data</p>
        <p>&#x25CF; Licence(s) for re-use which will be applied (e.g. one of the
          licences available from Creative Commons or Open Data Commons)</p>
        <p>&#x25CF; Restrictions on third party use</p>
        <p>&#x25CF; Any expected delay to data sharing e.g. pending a patent application
          or embargo related to publication in a journal</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Storage and backup</b>
      </td>
      <td style="text-align:left">
        <p>&#x25CF; Where (physically) data will be stored</p>
        <p>&#x25CF; Backup provision</p>
        <p>&#x25CF; Person or team responsible for backup</p>
        <p>&#x25CF; Recovery procedures</p>
        <p><b>Security</b>
        </p>
        <p>&#x25CF; Risks, and how they will be managed</p>
        <p>&#x25CF; Access arrangements</p>
        <p>&#x25CF; Any arrangements, if needed, for safe and secure transfer of
          data collected in the field</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Selection and preservation</b>
      </td>
      <td style="text-align:left">
        <p>&#x25CF; Details of which data should be retained, shared and/or preserved,
          with particular reference to contractual, legal or regulatory requirements</p>
        <p>&#x25CF; Foreseeable research uses for the data</p>
        <p>&#x25CF; Length of time for which data will (or should) be kept beyond
          the life of the project</p>
        <p>&#x25CF; The repository or archive where the data will be held, and any
          associated charges</p>
        <p>&#x25CF; Time and effort needed to prepare data for preservation / data
          sharing</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Data sharing responsibilities and resources</b>
      </td>
      <td style="text-align:left">
        <p>&#x25CF; Named person responsible for implementation of the Data Management
          Plan</p>
        <p>&#x25CF; Named person responsible for each data management activity</p>
        <p>&#x25CF; Hardware and software required (any that is additional to existing
          institutional provision)</p>
        <p>&#x25CF; Additional specialist expertise or training required</p>
        <p>&#x25CF; Charges to be applied by data repositories</p>
      </td>
    </tr>
  </tbody>
</table>## 3. Data organisation

Data files and folders need to be labelled and organised in a systematic way so that they are both identifiable and accessible for current and future users. The benefits of consistent data file labelling are:

* Data files are distinguishable from each other within their containing folder
* Data file naming prevents confusion when multiple people are working on shared files
* Data files are easier to locate and browse
* Data files can be retrieved not only by the creator but by other users
* Data files can be sorted in logical sequence
* Data files are not accidentally overwritten or deleted
* Different versions of data files can be identified
* If data files are moved to another storage platform their names will retain useful context.

There are three main criteria to consider regarding the naming and labelling data files, namely:

* _Organisation_: important for future access and retrieval, and needs to take into account the file naming constraints of the system where the file is located
* _Context_: this could include content specific or descriptive information, independent of where the data are stored
* _Consistency_: choose a naming convention and ensure that the rules are followed systematically by always including the same information \(such as date and time\) in the same order \(e.g. YYYYMMDD\).

### 3.1.          Common elements of a file naming strategy

* Version number
* Date of creation
* Name of creator
* Description of content
* Name of team/department/unit associated with the data
* Publication date
* Project number.

It is important to also consider the following when naming files:

* The use of generic file names that may conflict when moved from one location to another. Ensure filenames are independent of location.
* File names should outlast the file creator who originally named the file.
* How scalable the file naming policy needs to be, e.g. if the project number is limited to two digits, you can only have ninety nine projects.

### 3.2.          Version control

It is important to identify and distinguish versions of datasets consistently. This ensures that a clear audit trail exists for tracking the development of a dataset and identifying earlier versions when needed. Thus you will need to establish a method that makes sense to you that will indicate the version of your dataset.

* A common form for expressing data file versions is to use ordinal numbers \(1, 2, 3, etc.\) for major version changes and decimals for minor changes \(e.g., v1, v1.1, v2.6\)
* Confusing labels should be avoided e.g. revision, final, final2, definitive\_copy, as you may find that these accumulate
* Record ALL changes \(minor and major\)
* Discard or delete obsolete versions \(whilst retaining the original 'raw' copy\)
* Use an auto-backup facility \(if available\) rather than saving or archiving multiple versions
* Turn on versioning or tracking in collaborative documents or storage utilities such as Wikis, GoogleDocs etc
* Consider using version control software e.g. Subversion, TortoiseSVN.

Some structured examples of maintaining version control \[document name\] \[version number\] \[status: draft/final\]:

* Jones\_interview\_July2010\_V1\_DRAFT
* Lipid-analysis-rate-V2\_definitive
* 2001\_01\_28\_ILB\_CS3\_V6\_AB\_edited

## Summary

Good data management principles help to ensure that data produced or used are registered, stored, made accessible for use and reuse \(if appropriate\), managed over time and/or disposed of, according to legal, ethical, funder requirements and good practice.

Data management therefore is a process involving a broad range of activities from administrative to technical aspects of handling data in a manner that addresses the factors listed above.  A sound data management policy will define strategic long-term goals for data management across all aspects of a project or enterprise.

A data management policy is a set of high-level principles that establish a guiding framework for data management. A data management policy can be used to address strategic issues such as data access, relevant legal matters, data stewardship issues and custodial duties, data acquisition, and other issues. Data management plans must be continuously maintained and kept up-to-date throughout the course of a project or research.

Components of a data management plan will include:

* administrative information
* data collection methods and quality assurance processes
* documentation and metadata
* ethics and legal compliance
* storage and backup
* selection and preservation
* data sharing responsibilities and resources.

## Further readings

* Arms, C. R., Fleischhauer, C. and Murray, K. \(2013\). Sustainability of digital formats: planning for Library of Congress collections. Library of Congress, Washington DC, USA. Available at [www.digitalpreservation.gov/formats](http://www.digitalpreservation.gov/formats)
* Beagrie, N. and Houghton, J. \(2014\). The value and impact of data sharing and curation - synthesis of three recent UK studies. Jisc. Available at: repository.jisc.ac.uk/5568/1/iDF308\_-\_Digital\_Infrastructure\_Directions\_Report%2C\_Jan14\_v1-04.pdf
* Charles Beagrie Ltd \(2013\). Keeping research data safe: cost / benefit studies, tools, and methodologies focussing on long-lived data. Available at:  [http://www.beagrie.com/krds.php](http://www.beagrie.com/krds.php) \(accessed 4 August 2014\)
* Digital Curation Centre \(DCC\). \(2010\). Data management plans. Available at: [http://www.dcc.ac.uk/resources/data-management-plans](http://www.dcc.ac.uk/resources/data-management-plans) \(accessed 4 August 2014\)
* Drummond, C.G. \(2009\). Replicability is not reproducibility: nor is it good science. In Proceedings of the Evaluation Methods for Machine Learning Workshop, 26th ICML, Montreal, Canada. Available at: [http://cogprints.org/7691](http://cogprints.org/7691)
* European Commission \(EC\). \(2017\). Guidelines to the Rules on Open Access to Scientific Publications and Open Access to Research Data in Horizon 2020. Available at:  ec.europa.eu/research/participants/data/ref/h2020/grants\_manual/hi/oa\_pilot/h2020-hi-oa-pilot-guide\_en.pdf \(Version 3.2, 21 March 2017\)
* GODAN 2016 A Global Data Ecosystem for Agriculture and Food. GODAN, Wallingford, UK. Available at: http://www.godan.info/documents/data-ecosystem-agriculture-and-food
* Jones, S. \(2011\). How to Develop a Data Management and Sharing Plan. DCC How-to Guides, Digital Curation Centre, Edinburgh, UK. Available at: [www.dcc.ac.uk/resources/how-guides/develop-data-plan](http://www.dcc.ac.uk/resources/how-guides/develop-data-plan)
* UK Data Archive \(UKDA\). Plan to Share. Available at: [www.data-archive.ac.uk/create-manage/planning-for-sharing](http://www.data-archive.ac.uk/create-manage/planning-for-sharing) \(accessed 4 August 2014\)





# Chapter 7
## Business Intelligence
---
>*Business Intelligence:collection of tools and techniques for data management,analysis and decision support*.
>*BI: represents one component of a successful analytical framework.*
>
> # *A Brief History of Data Infrastructure* #
>=============================================
> - *Data remains the most critical ingredient of successful analytical capabilities 
  The evolution of data collection and infrastructure systems can be
  traced back to the early 1990’s when ERP systems started gaining prominence.*
> - *These ERP systems link corporate databases to support various business processes
 like Sales, HR, finance, Customer Service etc.*
> - *This also coincided with the launch of PC (Personal Computer)
 reporting solutions like Crystal Reports, Microstrategy EIS Toolkit, Qlik
Technologies*
> - *The Y2K (Year 2000) phenomenon1 served to acceleraten this ERP “migration” as companies scrambled to revamp IT systems to identify and eliminate the Y2K bug.*
> - *ERP systems offered a “off the shelf” solution that improved the IT and Data infrastructure while also eliminating the Y2K challenges of legacy systems.*
> - *The rising growth of the Internet as a commercial platform, coupled with the
ever reducing cost of storage, and growth of computational capabilities significantly
accelerated the rate and scope of data collection.*
> - **BI Vendors** :*A slew of vendors started selling a variety of solutions that could collect, collate
and query and retrieve large volumes of data very efficiently.*
> - *The 2000s: As organizations began to come to terms with the richness and volume
of data that was available, sophisticated analytical techniques for forecasting
and predictive modeling began to become feasible.*
>
> **The ecosystem started to see two very distinct phenomena.** 
>
 1.                 *The growth of specialized vendors who provided services in the area of statistical
and mathematical modeling.*
 2.                *The logical extension of the BI Vendors rebranding as “Analytics Solution
Providers” by leveraging their data infrastructure and add value added features
and services on top.*
>
**“Analytics”**
 was defined and redefined frequently
and usually to suit the convenience of the people spending the most money*
>
> **some symptoms seen (up to) today become obvious**
  1. A large number BI projects fail—a recent Gartner study estimated that less than
30 % of BI projects were deemed to meet the needs of the Business.
  2. Funding for analytics and BI initiatives will be less dependent on IT budgets,
but rather on Business Units to drive the analytics that they need.
  3. Companies that involve the Business Users in their BI initiative show more success
that those who do not.
>
> # *Business Intelligence for Analytics* #
>=============================================
The evolution of BI data infrastructure can be put into three stages:
 1. *Single-Pass Analytics Systems:This design imagines a situation where data flows linearly from OLTP
to BI to the reports used by analysts. In this case, the data flow looks like it hits a “dead end” in the analyses.*
 2. *Overlapped Analytics Systems (Single-Pass and Looped)—in the real
world, analysts get data from various systems (not just the official BI databases)
and process it in their own analyses that are provided to decision makers,affairs,this
creates data loops, which manifest downstream in overlapping and conflicting
reports.*
 3. *Closed-Loop Analytics Systems:This stage aligns the data-flows and data-stores in support of the analytics
function, and avoids the loops and overlaps in the previous stage,There is a huge conflict in the second stage between analysts who continuously evolve their own models and their IT counterparts who encode models into the
databases and data flows in the form of database designs,this conflict is resolved by separating the concept of input data
(stored in a “Data Arrival Stage”) and model data (stored in “Business Analytics
Databases”).*
>
> # *Business Intelligence in the Analytics Framework* #
>====================================================
 - *The Business Intelligence function includes several assets (databases, systems,
tools) and processes that interact with the other functions of the analytics framework.*
 - *The BI function is responsible for providing the technology underpinning
analytics.*
 - *In any case it helps to assess where the BI technology stands against a scale of
what’s possible:*
1.  *Unable to provide analytics systems (data, tools and infrastructure).*
2.  *Partially provides the analytics systems and data required and refreshes the
data periodically for off-line analyses.*
3.  *Fully provides analytics systems and refreshes the data periodically for
off-line analyses.*
4.  *Enables analytics to be executed in-line, i.e., used seamlessly within business
processes.*
5.  *Delivers enterprise-wide in-line analytics, so the organization can use analytics
at scale and without delay.*
>
> # *Data Sourcing*
>==================
> *Data Sourcing is needed to get input data for analytics, where the customer for
the data is the data stewardship team.* 
> # *Transaction Processing Systems*
> - *Online Transaction Processing systems (OLTP) are a class of systems that facilitate
and manage transaction oriented applications.*
> - *systems are geared to handle large volumes of transactions efficiently and
capture data for each transaction.*
> - *Transactions cannot be completed and logged with
incomplete or inaccurate data*
>
> # *Benchmarks and External Data Sources*
>===========================================
> - *OLTP systems provide significant volumes of data, they tend to be myopic
in that they only address the processes and systems that they support*
> - *BI systems can source data sources external
to the organization.*
> - *For starters, aligning this data against internal hierarchies and dimensions
is fraught with danger, since the process of collation necessarily obfuscates
such organization specific data and instead uses some generic classification. For
instance, the organizations may choose to view the US and Canada as two distinct
sales regions, but the retail sales data may choose to tag them collectively under
“North America”. Such disconnects could make such data unusable for analytics.*
> - *In addition, such data sources are never exhaustive, in that, they never truly
capture all the market activity. Channels that are too new or too small to be
captured under this umbrella will be missed*
> - *It is, therefore, critical to establish a feedback loop to the external data providers
to help assure and improve the quality of the data supply*
> - *Example: Airline reservation systems (Sabre, Galileo etc.) provide participating
carriers a consolidated data set that is a true record of every single ticket sold
through the reservation system. However, this data does not include tickets sold
directly through an airlines web site.*
> - *With increasing adoption of online booking, the “missed” portion of the data assumes
significant proportions.*
>
> # *Survey Tools*
>================
> - *In those cases where surveying is conducted in-house, BI tools provide data from
a variety of survey questionnaires, the most common being Customer Satisfaction
(CSAT) Surveys, Employee Feedback Surveys.*
> - *Other types of Survey data include more generic surveys like Salary Surveys*
> - *The biggest challenge in including Survey data into a data warehouse is the
inability to attach them to the common hierarchies.*
>
> # *Analytical Output*
>======================
>- *A source of data not generally thought of as a “source” per se, is the output and
results of analytics models.*
> - *model output is often used as input to other models.*
>
># *Data Loading*
>==================
> - *Data loading from internal and external databases is used to bring data from multiple
disparate repositories into a location that can be shared by many analysts.*
> - *In many cases, IT teams work to bring these sets of data into a centralized “data
warehouse” that embeds an IT-supported business model to structure the data. This
is achieved through two sets of data manipulations:*
 1. *Extract-Transform-Load4 (ETL) processes that extract data from the source
systems, then transform and load them into the data warehouse.*
 2. *Database designs5 in the forms of tables, views, triggers and stored procedures.
The database can be called a data warehouse or a data mart depending
on its scope and the ambition of its builders.*
>
> # *Solve Data Quality IT Issues*
>================================
> - *the IT contact person for this has to figure out if the problem is really
with IT, and if so to route it to the correct IT team and get it addressed*
> - *Problems are minimized in the case where the organization is in stage three of
their BI evolution, where there is no data manipulation in the data arrival stage or
on the way to it.*
> - *In many cases, this IT complexity leads to the selection of quick-fixes as
opposed to design changes.*
>
> # *Analytical Datasets and BI Assets*
>======================================
> *The data repository represents the single biggest asset of the BI framework and is usually seen as the primary driver
behind the BI framework.*
>
> # *Operational Data Store*
>===========================
> - *An Operational Data Store (ODS) integrates data from disparate sources (through
Data Loading).*
> - *An operational data store may be designed to store only a limited history of data with older data flushed periodically into a Data Warehouse.*
>
> # *Data Warehouse*
>===================
> - *A Data warehouse collects data from operational data stores and stores them for
longer term use. A key aspect of a data warehouse is that data is never deleted
from a warehouse, and once committed to the warehouse, the data becomes a permanent
record. Data warehouses are structured to handle complex queries with
larger data sets.*
> - *In fact a Data Warehouse is so structured that it proves to be a very expensive way to provide BI infrastructure.*
>
> # *Data Mart*
>===============
> - *A Data Mart is a specialized cut from the data warehouse extracted for very specific
business needs. Ownership of these data marts is typically vested with the business units.*
> - *To reduce the management overhead, care should be exercised to avoid “Mart Proliferation”
which is a result of indiscriminate creation of new data marts for every new
business need.*

> # *Data Structuring and Transformation*
>=========================================
>- *One key process in a BI framework is the transformation and structuring of data
into a convenient structure. The choice of structure can be*
  1. *Hierarchical Dimensions and Facts—a Star Schema.*
  2. *A Normalized Structure—also called a Third Normal Form.*
>
> # *Business Analytics Input Databases*
> - *The Business Analytics Input Database is an Operational Data Store into which
data from various sources flows. The data delivered to this stage must be a faithful
representation of data in the source systems.*
> - *The design of this database needs to address how the data is synchronized with its source, and to tune the delay (or
cycle time) and data integrity.*
>
> # *Business Analytics Ready Databases*
>=======================================
> - *A Business Analytics Ready Database is simply a specialized Data Mart upon
which analytics models are built.*
> - *Examples of such databases include the ubiquitous OLAP9 cube that is
very prevalent in providing reporting and visualization analysis.*
>
> # *Analytics Tools*
>=====================
> *Part of a complete BI framework is a set of analytical tools that are deployed for
the analysts to use.*



 
 







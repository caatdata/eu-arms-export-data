# EU Arms Export Data

Figures for all known controlled goods exported from EU member states since 1998.

The data is also available via a searchable application on the [Campaign Against Arms Trade](http://www.caat.org.uk/resources/export-licences-eu) website.

Source data from the [Official Journal of the European Union annual reports on the European Union Code of Conduct on Arms Exports](http://eur-lex.europa.eu/Result.do?arg0=annual+report&arg1=exports&arg2=resolution&titre=titre&chlang=en&RechType=RECH_mot&Submit=Search).


## Explanation


### *exports.csv*

Totals for export licences.

The file contains the following columns, which are separated by a semicolon:

    2003; 0; AT; Austria; DZ; Algeria; AFN; North Africa; ML 4; b; 435148;

-   Year
-   Embargo: 1 = Country under embargo, 0 = Country **not** under embargo.
-   Source country ISO 3166-1 alpha-2 code
-   Source country name
-   Destination country ISO 3166-1 alpha-2 code
-   Destination country name
-   Region code
-   Region name
-   Rating: an EU military rating from 1 to 22. See the [Common Military List of the European Union](http://eur-lex.europa.eu/LexUriServ/LexUriServ.do?uri=OJ:C:2013:090:0001:0037:EN:PDF) for full specifications.
-   Category
    -   a: Number of licences approved
    -   b: Value of licensed goods
    -   c: Value of exported goods
    -   d: Number of licences denied
    -   e1-e8: Number of times a refusal criterion was cited. Values are approximate. Criteria are numbered 1 to 8. See the [EU code of conduct on Arms Export](ec.europa.eu/external_relations/cfsp/sanctions/codeofconduct.pdf) for full details.
-   Value, either:
    -   a number of licences, or
    -   a value in Euros, calculated using contemporary exchange rates, not adjusted for inflation


### *broker.csv*

Totals for brokering licences (for goods traded between two foreign countries by a domestic broker).

The file contains the following columns, which are separated by commas and may be double-quoted or contain multiple values separated by semicolons:

    2008,SE,Sweden,issued,DE; PL,Germany; Poland,1,,ML4,,,DE; PL; NO,Germany; Poland; Norway
    
-   Year
-   Broker country ISO 3166-1 alpha-2 code
-   Broker country
-   Status ('issued' or 'refused')
-   Source country ISO 3166-1 alpha-2 codes
-   Source country names
-   Number of licences
-   Value of licenced items (
-   Rating (see description in exports.csv above)
-   Quantity of brokered items
-   Value of brokered items, in Euros, calculated using contemporary exchange rates, not adjusted for inflation
-   Destination country ISO 3166-1 alpha-2 code
-   Destination country names


### *mission.csv*

Details of exports to UN or other international Missions

The file contains the following columns, which are separated by commas and may be double-quoted:

    2006,AT,Austria,LR,Liberia,United Nations Mission in Liberia (UNMIL),Pistols and components ML 1
    
-   Year
-   Source country ISO 3166-1 alpha-2 code
-   Source country name
-   Destination country ISO 3166-1 alpha-2 code
-   Destination country name
-   Mission name
-   Item details


### *consult.csv*

Numbers of consultations between member states

The file contains the following columns, which are separated by commas:

    2005,RO,Romania,,,1,0,
    2005,,,AD,Andorra,,,3
    
(Each row conatins columns pertaining to either source or destination countries.)

-   Year
-   Source country ISO 3166-1 alpha-2 code
-   Source country name
-   Destination country ISO 3166-1 alpha-2 code
-   Destination country name
-   Consultations initiated by source country
-   Consultations received by source country
-   Consultations concerning destination country



## Feedback

Contact [data@caat.org.uk](mailto:data@caat.org.uk) with any comments, questions or requests for specific data or alternative formats.

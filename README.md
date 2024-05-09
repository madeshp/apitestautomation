During PROD Deployment, an improved query was implemented, leading to a significant reduction in response time.
DDF update:
New data points, such as the Red Indicator Cust Type Code and UID, have been integrated.
Springboot enhancement:
Eliminated Simility response transformation.
Implemented logging of the highest risk score to Splunk and conducted performance testing.
Translated count-status and closure-reason data.
GSQL/load job enhancement:
Developed a new load job for UID.
Expanded load job capabilities to incorporate UID, Red Indicator, Cust Type Code, ACAPS ACCT, and Iovation.
Updated PAE/PE queries to include Red Path Indicator and Cust Type Code, and introduced Peentity search.
UI Enhancements and bug fixes:
Addressed bulk file upload issues for PII search.
Included UID vertex in PII search functionality.
Integrated UID into UI graph explorer.
Resolved case source display discrepancies.
Corrected application display names on the graph explorer.
Incorporated count-status and closure-reason data into PAE/PE details page's account widget.
Revised the risk grade tooltip wording on PAE/PE detail pages.
Displayed red path indicators on ACAPS application and Risk account widgets.
Added PEntity functionality to direct search.
TG schema update:
Introduced new vertices for UID and Iovation Device ID.
Added new elements, including Red Indicator, Cust Type Code, and ACAPS ACCT.
Autosys:
Configured Alert batch processing job.

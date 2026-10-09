# Shipment Data Analysis And Logistics Performance Dashboard

TransGlobal Logistics Pvt. Ltd. is a 3PL (third-party logistics) company that handles last-mile delivery for e-commerce and enterprise clients across India, operating through 6 dispatch hubs (Delhi, Mumbai, Bengaluru, Chennai, Kolkata, Hyderabad) and 5 courier partners (Delhivery, BlueDart, Ecom Express, XpressBees, DTDC).

Every hub's Warehouse Management System (WMS) exports its own shipment log at month-end, and these get merged into one master file by an ops executive using copy-paste. The result — this workbook's RawShipmentData sheet — is large (1,600+ rows) but genuinely messy: inconsistent text casing, dates and weights stored as free text in different formats, costs pasted in as currency text, some duplicate rows from re-exports, and missing values that are sometimes genuine (a shipment still in transit has no delivery date yet) and sometimes just data-entry gaps.

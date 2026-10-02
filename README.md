# Singapore MCST management contacts

Management-contact research for all 3,806 records in the original Building and Construction Authority (BCA) MCST dataset. Research and individual web rechecks were completed on **2 October 2026**.

## Files

| File | Records | Contents |
| --- | ---: | --- |
| [Excel workbook](data/mcst/singapore_mcst_management_contacts.xlsx) | 3,806 | Contacts, Full data, Managing agents and Notes sheets |
| [Complete CSV](data/mcst/singapore_mcst_management_contacts.csv) | 3,806 | All original records and enrichment columns |
| [Has email](data/mcst/mcst_has_email.csv) | 1,920 | Records with a nonblank Management email field |
| [No email found](data/mcst/mcst_no_email.csv) | 1,886 | Records with a blank Management email field |

The two email lists partition the complete CSV. They retain all 45 columns. The full dataset preserves the original 16 columns and original row order.

## LinkedIn follow-up — 3 October 2026

Every one of the **109 records with neither phone nor email** in the original research snapshot received two individual public LinkedIn searches. Promising matches received further role, company or project checks.

| File | Rows | Contents |
| --- | ---: | --- |
| [LinkedIn follow-up workbook](data/mcst/mcst_linkedin_contact_followup.xlsx) | 109 records, 33 lead relationships | Records, Leads and Notes sheets with clickable source links |
| [All 109 follow-up records](data/mcst/mcst_linkedin_contact_followup.csv) | 109 | Best available lead, outcome, evidence, limitations and the two search queries |
| [All referral leads](data/mcst/mcst_linkedin_referral_leads.csv) | 33 | One person–MCST relationship per row, including alternatives |

- **27 records have a referral lead; 82 remain unresolved.** There are **21 distinct people** across the 33 relationships. Subsidiary MCSTs and related developments can share a person.
- Leads include facilities management, quantity surveying, project management, engineering, design and developer or managing-agent staff. Unknown titles, historical work and company-level referrals are labelled.
- **3 records have a published referral email**: MCST 2173 has a selling-agent business email; 4956 and 4979 have a shared developer enquiries email. These are not confirmed MCST management mailboxes. Eight records have a published company/referral phone.
- Savills' own announcements support its managing-agent appointments for Kopar at Newton and North Gaia. Winnie Wong is a company leadership referral; the listed number is the shared property-management office.
- The suggested Tri Property appointment at Mooi Residences is from a third-party directory and requires confirmation. The original July BCA field is blank. MCST 0289 also carries a sourced warning about its historically listed agent's striking-off notice.

Read **Relationship**, **Evidence period**, **Contact scope** and **Limitations** before using a lead. A public profile or former project role does not prove a current estate appointment. No outreach, private-contact lookup or email guessing was performed. The 3,806-row snapshot and its original email lists remain unchanged. This supplement covers the 109 no-contact records, not all 1,886 records without email.

## Coverage and interpretation

- 3,697 records have at least one phone or email route; 109 have neither.
- Of the 1,920 records with emails, 72 have building-specific mailboxes and 1,848 use shared agency mailboxes. The addresses are not unique recipients: multiple buildings can use the same agency inbox.
- Of the 1,886 records without an email, 1,777 still have a phone contact.
- Each record includes its research result, source links, search query, check date and relevant changes. Building-specific, shared agency, dated publication and directory-only evidence are distinguished.

These are checks of published information. No telephone calls or email-delivery tests were performed. A listed contact is not a guarantee of current reachability. A blank email means no usable email was established by this research. Dated, conflicting and directory-only contacts remain labelled for confirmation.

## Sources

- [Original BCA dataset on data.gov.sg](https://data.gov.sg/datasets/d_1f9391a2f1476cdaf4f05a8d3a05c257/view): page updated 6 April 2026; 3,806 records.
- [Newer BCA reference](https://data.gov.sg/datasets/d_f988c57e16e99ad3a649aa04572efd1c/view): page updated 29 July 2026; 3,818 records.
- Public property websites, managing-agent websites, industry directories and publications linked in the files.

The newer reference was matched by MCST number and Sub MCST number. Four original records were absent from that reference and are flagged. Its 16 additional records were outside the original dataset and were not appended. Publication dates do not guarantee that each underlying contact was refreshed on that date.

## Using the data

Use the workbook to preserve identifiers and leading zeros. When importing CSV files, treat MCST identifiers, postal codes and phone fields as text. CSV files use UTF-8 with a byte-order mark.

Start with the **Management email**, **Email scope**, **Research status** and source columns. Consult the notes before using dated or unconfirmed contacts.

The government source is subject to the [Singapore Open Data Licence](https://data.gov.sg/open-data-licence). Consult the respective source terms for supplemental contact information. This repository does not grant additional rights over third-party material.

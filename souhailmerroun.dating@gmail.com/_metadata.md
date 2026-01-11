Contact Metadata Fields
=======================

Each contact folder contains a metadata.yml file with the following fields:

Fields
------

name
  The contact's display name. Often includes prefixes like "d " for dating contacts
  or platform indicators like "ig." for Instagram, "tinder" for Tinder, etc.
  Example: "d tinder ig.ikram_is_"

phone
  Phone number in international format.
  Example: "+212 6 87 11 63 08"

email
  Email address. Empty string if not available.

address
  Physical address or location. Can be multi-line.
  Example: "Tangier, MA"

birthday
  Date of birth. Empty string if not known.

notes
  Free-form text with context about the contact, how you met, relationship status,
  thoughts, etc.

photo
  URL to the contact's profile photo from Google Contacts.

gender
  Gender of the contact.
  Values: "male", "female", or empty string if not specified.

status
  Current relationship phase with this contact.
  Values:
    - lead: Someone you've identified but haven't contacted yet
    - contacted: Initial message sent, awaiting response
    - talking: Active conversation going on
    - planned: Date scheduled but not happened yet
    - dating: Went on at least one date
    - seeing: Regularly seeing each other, not exclusive
    - exclusive: In a committed relationship
    - paused: Conversation went cold, might resume
    - rejected: She declined or unmatched
    - ghosted: No response after contact
    - archived: No longer pursuing

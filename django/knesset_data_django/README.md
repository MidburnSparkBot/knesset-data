# knesset_data_django

## committees

### management commands

  * **[get_committees_data](/django/knesset_data_django/committees/management/commands/get_committees_data.py)**
    * **--members-attendance** - exports a csv file with data about members attendance in committees
  * **[scrape_committees](/django/knesset_data_django/committees/management/commands/scrape_committees.py)** -
    Fetch and update committees data
  * **[scrape_commitee_meetings](/django/knesset_data_django/committees/management/commands/scrape_commitee_meetings.py)** -
    Fetch and update committee meetings data

## models

  * **Committee**
  * **CommitteeMeeting**

## mks (members of Knesset)

### models

  * **Member**
  * **Knesset**

### utils

  * **get_all_mk_names** - get the names of all current Knesset members.

## persons

### models

  * **Person**
  * **PersonAlias**
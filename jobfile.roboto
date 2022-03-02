*** Settings ***
Documentation     <ID - Title> \n\n
...               Description: <description of this jobfile> \n\n
...               Procedure: \n\n
...               1. Example Test 1 \n\n
...               Variable File To Edit/Modify: \n\n
...               (Update the line below with the file used or delete if not applicable): \n\n
...               - variable_file.yaml \n\n
...               Custom Keyword File: \n\n
...               (Update the line below with the file used or delete if not applicable): \n\n
...               - keyword_file.robot \n\n
# Replace the following tags with relevant information to the test case
# Force Tags        <Customer>   <Platform>   <OS>   <Feature>

# CXTA
Library  CXTA
Resource  cxta.robot

# Include all the keywords from the opensource libraries from robot framework:
# http://robotframework.org/robotframework/#standard-libraries
Library     String
Library     BuiltIn
Library     Dialogs
Library     DateTime
Library     Collections
Library     OperatingSystem

# Update/uncomment the line below with the file used or delete if not applicable
# Variables   /path-to/variable_file.yaml

# Update/uncomment the line below with the file used or delete if not applicable
# Resource    /path-to/keyword_file.robot

Suite Setup     Run Keywords
...             load testbed

Suite Teardown      Run Keywords
...                 Disconnect From All Devices

*** Test Cases ***
1. Example Test 1
  [Documentation]  This is an example test
   Should Be True  2==2

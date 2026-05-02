 # Email Automation using Zapier

## why i built this

i was thinking about how many times people manually 
send the same emails over and over when someone fills 
a form or adds data to a sheet. it just felt like 
something that should happen automatically. so i 
figured out how to do that using Zapier without 
writing a single line of code.

------------------------------------------------------------------

## what it does

this workflow watches a Google Sheet for new rows. 
the moment someone adds data — like a name, email 
and a message — Zapier picks it up and Gmail sends 
an email to that person automatically. no one has 
to do anything manually after the sheet is updated.

-------------------------------------------------------------------

**step 1 — Google Sheets (Input)**
data is entered into the sheet. this acts as the 
starting point of the whole workflow. fields can be 
anything like name, email address, message etc.

**step 2 — Zapier Trigger (Automation)**
Zapier is connected to the sheet and watches for 
new rows. the moment a new row appears, the Zap 
fires and the workflow starts running.

**step 3 — Gmail (Output)**
Gmail sends a fully formatted email to the recipient 
mentioned in the sheet. the email content is also 
dynamic — it pulls the name and message directly 
from the sheet row.

---------------------------------------------------------------

## tools used

| Tool | Purpose |
|---|---|
| Google Sheets | data input and trigger source |
| Zapier | automation and workflow engine |
| Gmail | email delivery |

---------------------------------------------------------------

## key features

- fully automated — no manual sending needed
- trigger based — fires only when new data appears
- dynamic emails — content pulled from sheet data
- real time — email goes out within seconds of 
  new row being added
- no code — built entirely using no-code tools

## how it works

## Workflow Explanation

### 1. Input Data (Google Sheets)
![Input](google-sheets-input.png.png)

### 2. Automation Workflow (Zapier)
![Workflow](workflow-automation.png.png)

### 3. Final Output (Result)
![Result](final-result.png.jpeg)


## what i learned

- how trigger based automation actually works 
  behind the scenes
- how to connect two completely different apps 
  without any code
- how no-code tools like Zapier can replace hours 
  of repetitive manual work
- importance of testing each step before the 
  full workflow runs
- how dynamic data mapping works — pulling specific 
  fields from a sheet into an email template

------------------------------------------------------------

## use cases

this kind of workflow is useful in a lot of real 
situations like —

- sending confirmation emails when someone fills 
  a registration form
- notifying a team when a new lead is added to 
  a tracker sheet
- automating follow up emails for any kind of 
  data collection process

--------------------------------------------------------------

## status
✅ workflow built and tested  
✅ screenshots documented  
✅ emails delivered successfully in testing

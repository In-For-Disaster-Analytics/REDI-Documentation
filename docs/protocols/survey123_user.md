# ArcGIS Survey123 Connect

## Onboarding / Credentialing
- Get username and password from Administrator (Paul).  Requires name and email
- Paul puts them into group, either existing or new
- user receives email with temporary access creds
- Forgotten creds: email Paul, and he can reset the user password and sends password reset email

### Onboarding Information provided
- Username
- Tempoary Password
- Connection url
- Custom generated url for Trusted Conenction with ESRI cloud and local portal

## Launching Application
- **TAKE SCREENSHOTS WHEN DOING THIS FOR FIRST TIME**
- desktop app (download and install.  Get links from Paul)
- requires liscensing from server
- upper right hamburger = utilities
- settings --> Add connection (*onboarding*)
- onboarding doc will provide url. if valid url, connection will work.
- select connection, click OK
- login (sites and stories server is very slow)
- Icont in top right infers which user / server you're in

## Creating new survey
- Click 'New Survey' button
- Give new survey a meaningful name
- Samples has a lot of precreated sample surveys that feature different features / functions.  Can use as tutorials and delete later
- Select and create survey
- Form (preview view), with options on left.
    - XLSForm opens spreadsheet that is driving the form
    - Update syncs spreadsheet to preview (but doesn't save changes in excel!). (Save in excel also does this.)
    - Files opens to local file system
    - Tools (analyze survey, etc.)
    - Publish, syncs to the portal and creates series of links to share
- Details
    - Description field
- Options
    - Set user permissions, etc.
- Map
    - Set overview and zoom for overall map in survey (?does it do this for multiple?)
- Media, basically project folder
    - CSVs for options
- Linked Content
    - Have to be published at least once for feature to turn on
    - ex. linked maps
- Scripts
    - Custom javascript
- Schema
    - Displays Layers/Tables, fields, field properties 

## Modifying XLS spreadsheet
- [documentation](https://doc.arcgis.com/en/survey123/desktop/create-surveys/xlsformessentials.htm)


## Publish
- Use defaults
- Analyze survey.  will give info on issues in form (basically a debugger)
- Resolve issues and publish
- Check on cloud survey123: put cutom url into new browser window address bar 
    - Repeat login with the same credentials
    - if says 'timed out', click login again

## Review Forms online
- Browser windows with tiles for forms, most recent in top left
- Opens into overview of submissions
- Collaborate
    - Survey share links under 
    - Controls for who can see, submit, etc.
    - Options to create Shared Update Group for collaborative form development and administration 

## Notes
- forms ONLY live locally until published
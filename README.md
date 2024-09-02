# teste

# Id google calendar
949eba08a1d7e03564c6357aad606eb9b2cd44370c6f3a3743af2be366b04c6c@group.calendar.google.com

# install de library
npm install googleapis@105 @google-cloud/local-auth@2.1.0 --save

# Donwload credentials.json at
https://console.cloud.google.com/apis/credentials?project=healthy-dolphin-430818-p2

# git clone https://github.com/randomBrainstormer/MMM-GoogleCalendar.git

# run node authorize.js

# add de module
{
    module: 'MMM-GoogleCalendar',
    header: "My Google Private Cal",
    position: "top_left",
    config: {
        calendars: [
            {
              symbol: "calendar-week",
              calendarID: "MyGoogleCalendarIDHere"
            },
            // To add more calendars, replicate the above entry within this array with the respective ID
        ],
    }
},


{"installed":{"client_id":"860843709262-8a7liou6mn8se792gshcq6i9kgjtocu8.apps.googleusercontent.com","project_id":"healthy-dolphin-430818-p2","auth_uri":"https://accounts.google.com/o/oauth2/auth","token_uri":"https://oauth2.googleapis.com/token","auth_provider_x509_cert_url":"https://www.googleapis.com/oauth2/v1/certs","client_secret":"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","redirect_uris":["http://localhost"]}}

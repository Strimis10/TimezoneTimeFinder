# TimezioneFinder

Timezonefinder is a package that lets you know in what timezones it's a specific time

* 24 hour version 

    * getTimezones

        GetTimezones is a function that lets you input the current time and it will respond with a list of time zones where it currently is that specific time.


        `from TimezoneFinder import TimezoneFinder24h
        print(TimezoneFinder24h.getTimezone("13:29"))`


        RESULT:

        `
        ['Africa/Blantyre', 'Africa/Bujumbura', 'Africa/Cairo', 'Africa/Ceuta', 'Africa/Gaborone', 'Africa/Harare', 'Africa/Johannesburg', 'Africa/Juba', 'Africa/Khartoum', 'Africa/Kigali', 'Africa/Lubumbashi', 'Africa/Lusaka', 'Africa/Maputo', 'Africa/Maseru', 'Africa/Mbabane', 'Africa/Tripoli', 'Africa/Windhoek']`



    * getTimezone

        GetTimezone is a function that lets you input the current time and it will respond with a one time zone where it currently is that specific time.
        
        
            
        `
        from TimezoneFinder import TimezoneFinder24h
        print(TimezoneFinder24h.getTimezone("13:29"))`


        RESULT:

        `Atlantic/Cape_Verde`
    
    **Inputs:**

        * Both functions takes an input of the time as a string with a colon deviding hours from minutes.

        
        * Both has a minuteCeck input that is turned on by default but by setting it as False it skips the checks for minutes and only looks for hours, wich means that you don't need to input the CURRENT minute.  



* 12 hour version
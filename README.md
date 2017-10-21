what is meta?
=============

meta is an attempt to learn monorepos and how small teams can effectively use monorepos. 


[![pipeline status](https://gitlab.com/privatehunanpanda/meta/badges/master/pipeline.svg)](https://gitlab.com/privatehunanpanda/meta/commits/master)

also note that the karma.conf.js has changed for front end 

    browsers: ['Chrome'],
    customLaunchers: {
            Headless_Chrome: {
                    base: 'Chrome',
                    flags: [
                        '--no-sandbox',
                        '--disable-gpu'
                    ]
                  }
    },
 
this is because chrome can't run as root without the --no-sandbox flag 


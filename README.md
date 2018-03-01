# chuckfacts
Ever Node application needs to be able to produce a Chuck Norris fact. You're welcome.

## Usage

Returns a promise. So, using async/await...

    (async () => {
        const chuck = require('./chuck.js');`
        const line = await chuck.getChuckNorrisFact();
        console.log(line);
    })();
        

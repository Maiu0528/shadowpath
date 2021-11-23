# What is this?

Get perfect shadows every time for the non-designer.

# Instalation
npm i shadowpath --save

Then...

'''

import { shadowpath } from 'shadowpath';

    shadowpath({
        shadow_type: 'hard',
        padding: false
});
'''

## Options
shadowpath supports 2 options, oth of which are optional:

* *shadow_type* - hard | soft (Default is soft)
* *padding* - boolean (Default is false)

## Error   cannot find module 'd:\cmw\nest-tut\testing\hyperlaunch\apps\backend\dist\main' at function.module._resolvefilename 
solution:- In nest-cli.json file add a line   "entryFile": "/backend/src/main", if not present or path accroding to your project 



Base Entity model

import { BaseEntity, Entity, Property } from "@mikro-orm/core";


@Entity()
export class UserRoundAttempt extends BaseEntity{
    @Property()

    constructor({}:{}){
        super();
    }
}

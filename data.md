```javascript
let data = {
    // TODO: insert your data structure that contains 
    // users + quizzes here
    users: [ {
        id: number,
        firstName: string,
        lastName: string,
        score: number,
        rank: number,
        email: string,
        password: string,
        numSuccessfulLogins: number,
        numFailedPasswordsSinceLastLogin: string,
        quizzes: number,
        timeCreated: number,
        timeLastEdited: number,
    } 
        

    ]
    quiz: [ {
        id: number,
        name: string,
        description: string,
        NumQuestions: string[], // array of questions
        Users: string[] // array of users
        Leaderboard: number[], // array of users in order of points
        timeCreated: number,
        timeLastEdited: number,
    }
    ]
}
```

[Optional] short description: 

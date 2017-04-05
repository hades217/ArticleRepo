# Notes

```
[].concat(vendorModules, coreModules, appModules, pageModules);

```

### Jira



## Enhancement Request Process

1. Idea
2. Seen
2. Scoping
3. Validating
4. M&D Only
5. Project
6. Requirements
7. In Progress
8. Delivered
9. Closed
10. Waiting

## items
- agile team
- agile process
- agile board
- agile delivery vehicles: epic, story, version ,sprint
- https://www.atlassian.com/agile
- agile story points, fibonacci-like format, planning poker
- no tasks more than 16 hours
- scrum
- sprint
- daily standup
- git method
- bitbucket/ gitlab/ github
- commits,commits message format
- push
- pull
- pull request
- approval
- merge
- rebase
- jira
- jira epic
- jira reporter
- jira assignee
- jira watched
- story point
- epic
- acceptance criteria
- jira create branch
- bamboo
- user story (epic)

##

Singleton
Web Architecure

Tips Url: https://github.com/loverajoel/jstips

##

###
Agile Team Training 200


### Webpack 2 fetures

- ES6 modules
- Code splitting with es6
- Dynamic expressions
- System.import
- babel and webpack


### Singleton in javascript

```javascript

var singleton = function(fn){
    var result;
    return function(){
        return result || (result = fn.apply(this,arguments));
    }
}
var createMask = singleton(function(){
    return document.body.appendChild(document.createElement('div'));
})

```
s
```ecmascript 6

export default class singleton {
    static instance;
    
    constructor(){
        if(instance){
            return instance;
        }
        this.instance = this;
    }
}


```

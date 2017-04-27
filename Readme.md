# Notes

```
[].concat(vendorModules, coreModules, appModules, pageModules);

```

### Jira

https://rangle.io/
https://www.freecodecamp.com/map#nested-collapseBasicJavaScript

### WEChat

https://medium.com/javascript-and-opinions/state-of-the-art-javascript-in-2016-ab67fc68eb0b
https://medium.freecodecamp.com/how-you-can-land-a-6-figure-job-in-tech-with-no-connections-6eed0de26ea4
https://medium.com/conquering-corporate-america/here-are-the-top-tech-companies-secrets-to-hiring-the-best-people-33f432c39db2
https://medium.com/@writerpollock/australia-the-startup-capital-of-brunch-surfing-and-frontier-tech-e0555de6ea7c
https://medium.com/@Atlanta_Lants/startup-accelerators-in-australia-95c9868c99b7
https://medium.com/@iamwormify/a-list-of-australian-startups-that-you-should-know-about-part-1-1-25-71a0baf2c2af

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

### js
```javascript

emtyFunc = function() {
    return function() {
      
    }
}

```


### Es6

https://leanpub.com/understandinges6/read/

- TDZ(Temporal dead zone)
- block bindings let and const
- use const by default and only use let when you know a variable's value needs to change

#### ES6 String
- includes
- startsWith
- endWith
- 'string'.repeat(3)

### Agile Team Training 300

##### Proposal

- name: wangpai vs wangpai
- team argument and competations
- scrum
- one memeber as a scrum master
- sceniro
- git bitbucket/ jira
- web basics
- ux presentation 
- job introduction 


### Webpack 2 fetures

- ES6 modules
- Code splitting with es6
- Dynamic expressions
- System.import
- babel and webpack

### Webpack & Rollup
- Code-splitting
- Static assets
- use pkg.module


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

### Angular 1.6
- component has a defualt controllerAs of $ctrl
- diasable isolate scope in component : scope:{},

what makes a good component?
- Isolated
- Focused
- One-way Binding
- Use Lifecycle Events
- Well Defined API
- Emit Events

Architecture
- Smart & dumb components
- Presentation % container components

Dirctory Structure

* app/[asset]/[collection]/[feature]/

* app/[asset]/
* app/[asset]/[feature]/
* app/[asset]/[collection]/[feature]/[asset]/[feature]/

### Angular 1 Guide

https://github.com/kevinvanhove/angular-structure-styleguide

### Angular 1 Documenting a component

```javascript
/**
 * @ngdoc component
 * @name moduleName.component:videoOfBook
 *
 * @description <video-of-book> component, description of this component.
 */


```
### Angular vs React

https://www.sitepoint.com/choosing-between-react-and-angular/

### Online Chat Provider
- LivePerson


### UX Presentation - Donuts and learn
Tools: Reveal.js

- UX definition
    - Everything user experiences, physically and mentally
- UX examples
    - Loading animation, one by one or one sudden
    - Both side poles on the road to naturally influence drivers
    - UX influence factors: weather, current conditions
- distract users
    - Loading icon
    - Facebook app, loading icon, who blames
- bad examples - to find which things are wrong
    - led lights in LA
    - Ignore language specific features in different country
- Team discussion Topics: one scenario
    - Discuss and solutions
- Stress practice : who can get quote first, aami, allianz, Suncorp
- Solutions
    - raw backs
    - Steps
        - Obeservation
        - Generate Idea
        - Investigation
        - Prototyping
        - Testing
        - Repeat

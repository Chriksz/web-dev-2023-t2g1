## The purpose of the web site

- Selling tickets.
- Advertising of the different entertainments and services.


## Content of the web site
### Theme
- Theme park itself is for children but the target audience (the users) of the website will be adults who want to buy tickets, etc. Hence the design can stay conversative and functional, instead of too animated and colorful.
- Something similar to The Flintstones. Roller coasters and animals match well with that cartoon.

### Entertainments
- Roller coaster
- Zoo

### Type of services
- Medical team
- Ticketing service
- Event organization (e.g. birthday parties)
- Food and drinks

## Structure of the web site

- Every page should have unified header (logo, navigation bar) and footer sections (useful infos, logo).
- Its landing page should show basic information (opening hours, etc) and ticketing along some nice eye catching visuals
- It should have a page, detailing the different entertainments  (list view with pictures and description)
- It should have a page dedicated to ticket selling (shopping cart)

## Used Technologies

### Principles

- According to the webinar, it is not recommended to use third party libraries. 
- It is also not recommended to focus on JavaScript too much. 
- Make sure to reference any copied material.
- Related webinar: https://zoom.us/rec/play/dbQrZyovedP15gyOlLruFQ419KHbxVGWpCy4OA8DL41R5NuBIS0OcfnJbbEX_wq_-wHIOUcLbH8Jmh1P.ZqUrzvqZsw9NfLQl?canPlayFromShare=true&from=share_recording_detail&startTime=1702641492000&componentName=rec-play&originRequestUrl=https%3A%2F%2Fzoom.us%2Frec%2Fshare%2FOLdKd1YiU_Iusnwl9bTlT5xL7HpG-COe6cEVbjlnaepQKEhyV__G0gDvKjBikPvE.qEgeT8tyXILvjlPW%3FstartTime%3D1702641492000%26utm_medium%3Demail%26utm_source%3Dother%26utm_campaign%3Dgroup.r8ksATtgEe6LnwqzOmLjmQ.opencourse.targetedmessages.group_announcement~group.r8ksATtgEe6LnwqzOmLjmQ.rBkw7pWXQfWMkab-Q3o9mg

### Techniques

- Use semantic tags
- CSS and HTML files should be separeted
- In case of using class or id attributes, use BEM convenction
- Use css flexbox for layout
- The code should be well commented
- The midterm is mostly about LG, SM is only nice to have
- Produced code has to be valid in W3C validator

### Proposed File and Directory Structure
- Base includes shared css rules
- index.html refers to the landing page. Hence there is no HTML directory there.

```
|--->base
|       |--->css
|--->pages
        |--->landingpage
        |    |---> css
        |--->page2
        |    |---> html
        |    |---> css
        |--->page3
        |    |---> html
        |    |---> css
|--->index.html
```
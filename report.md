# Missing Data & API :octocat:

**_NOTE PAGES ARE FINISHED FROM MY SIDE THE ONLY THING LEFT IS LINKING THEM WITH THE RIGHT APIS_**

This report will walk throgh pages, page by page with all details

<br />

---

<br />

## 1 - Page Clients Surveys

url: <http://172.16.100.14:3000/Surveys/ClientsSurveys>

### API

**Geting Data:** /survey/SurveyClient/GetClientSurveys

> This table shows the data in the old project in comparison with the new data I get from API

|      DaTeTime      | Application |       Caller       |       Called       |      AgentID       |     SurveyType     |       Rating       |     questions      |
| :----------------: | :---------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: |
| :heavy_check_mark: |     :x:     | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |

<br />

---

<br />

## 2 - Page Survey Follow Up

url: <http://172.16.100.14:3000/Surveys/SurveyFollowUp>

### APIs

#### Main Page

**Getting Data:** /survey/SurveyClient/GetClientSurveys  
**Adding&Editing Comment:** /survey/FollowUP/SaveComment

> This table shows the data in the old project in comparison with the new data I get from API

> In old project this page is similar to the previos page but it has add comment action and Compeleted Switch button so for that I think same API for getting data is used

|      DaTeTime      | Application |       Caller       |       Called       |      AgentID       |     SurveyType     | Rating             |
| :----------------: | :---------: | :----------------: | :----------------: | :----------------: | :----------------: | ------------------ |
| :heavy_check_mark: |     :x:     | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |

#### Completed sub page

**Getting Data:** /survey/FollowUP/GetFollowUP  
**Adding&Editing Comment:** /survey/FollowUP/SaveComment  
**Delete Follow UP:** /survey/FollowUP/DeleteFollowUP

> This table shows the data in the old project in comparison with the new data I get from API

| DaTeTime | Application | Caller | Called | AgentID | SurveyType | Rating | CommentDate | Supervisor | Comment |
| :------: | :---------: | :----: | :----: | :-----: | :--------: | :----: | :---------: | :--------: | :-----: |
|   :x:    |     :x:     |  :x:   |  :x:   |   :x:   |    :x:     |  :x:   |     :x:     |    :x:     |   :x:   |

<br />

---

<br />

## 3 - Page Agents Rating

url: <http://172.16.100.14:3000/Surveys/AgentsRating>

### APIs

**Getting Data:** /survey/FollowUP/GetFollowUP

> This table shows the data in the old project in comparison with the new data I get from API

> This Page is satesfied by the API for the previous page

|      AgentID       |     FirstName      |      LastName      |     Extension      |        Team        |   Surveys Count    |       Rating       |
| :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: |
| :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |

<br />

---

<br />

## 4 - Page Settings/Surveys

url: <http://172.16.100.14:3000/Surveys/Survey>

### APIs

**Getting Data** /survey/Survey/GetSurveys  
**Editing/Adding Data** /survey/Survey/SaveSurvey  
**Deleting Data** /survey/Survey/DeleteSurvey

> The APIs For This Page were very clear and found easly with no lack of data

<br />

---

<br />

## 4 - Page Settings/Questions

url: <http://172.16.100.14:3000/Surveys/Question>

### APIs

**Getting Data** No API return a full list of questions  
**Editing/Adding Data** /survey/Survey/SaveQuestion  
**Deleting Data** /survey/Survey/DeleteQuestion

<br />

---

<br />

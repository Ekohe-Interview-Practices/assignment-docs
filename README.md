# Assignment docs

## Requirements 

* (I) [Backend API](reqs/assignment.api.pdf) pdf

* (II) [Front end](reqs/assignment.frontend/README.md) md

## Solution and status

The main idea of the solution is a hypothetical system with these following parts. You'll find some elements not relevant to the original requirements, only provided and implemented as suggestions and presented all to provide the idea of a full hypothetical system. *In the matter of facts, elements in italic are not finished or implemented yet.* 

- (**A**) The backend as a Rails app with classic API/UI to use the UI part as an Admin interface.

  - ⚙ PostgreSQL, Rails 6, Ruby 3, [Hotwired](https://hotwire.dev/), *Material components*[1]. 

  - 🚀 Rails app and Database deployed (CI) to Heroku.
  - ▶  **[Github project ekohe-backend](https://github.com/Ekohe-Interview-Practices/ekohe-backend)**.

- (**B**) The frontend as an Angular app that in adition to the assignment can invoke our API.

  - ⚙ Angular 12 with Angular Material. Standard CSS media queries.
  - 🚀 Static app deployed (CI) to Cloudflare Pages.
  - ▶ **[Github project ekohe-frontend](https://github.com/Ekohe-Interview-Practices/ekohe-frontend)**.

- (**C**) ...

![](solution/runtime 2.png)



## Notes

**[1]** It refers to [pure implementation of material for web](https://material.io/develop/web/getting-started), could be any choice like TailwindCSS, Boostrap, etc, or even just Rails Admin if preferable. BUT nothing it's really implemented.



